The credit for most of the contents goes to: panique (GitHub) -> https://github.com/panique
Link to the GitHub repository -> https://github.com/panique/huge
Link to the Packagist -> https://packagist.org/packages/panique/php-login?fbclid=IwAR2PRnfXi7kAZsLxdxTP8W5vswiN9JNgJEXMEwk3YoYA19aspJY-WsY1uew


Firstly import the .sql files serially as present inside the php-login/application/_installation file directory.

Then configure the database settings inside the config.development.php (from line number 64) located inside php-login/application/config/config.development.php

Now you're free to run your project.


*** Most of the files are just as they were, except for a few changes in mail settings(currently disabled)


*** Likewise the user details are as:
username	password	account_type
admin		12345678	7 (admin)
demo_user	12345678	1 (normal user)
premium_user	testtest	2 (premium user)

Likewise, as the mail settings were removed, and as for such the activation link is not available (I was not able to find the exact file related with it), and as for so the account activation should be manually managed in from the database.

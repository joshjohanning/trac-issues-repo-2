# Migrate Trac tickets

See: https://github.com/trustmaster/trac2github

1. Edit the file 'trac2github.cfg'. You can also edit the `trac2github.php` above the 'DO NOT EDIT BELOW' comment.
2. Run the php file from the shell, e.g.:
`$ php trac2github.php`

Requirements:
1. PHP (e.g. on Ubuntu `apt-get install php`) (I prefer `apt-get install php-fpm` to not install apache over my existing web server)
2. Support for the trac database format, e.g. `php-mysql`, `php-sqlite3`, etc.
3. `apt-get install php-curl`

Athenticating with GitHub, including with two-factor authentication:
1. Set up a GitHub personal access token, see https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/
2. Set the username field in the configuration to your GitHub username
3. Set the password field in the configuration to your GitHub personal access token


test

Chess Club Central
------------------

Open Source software released under the GNU Public Licence (GPL).

Author: Geoff Peters 

Description:
PHP/MySQL software for managing rankings for amateur chess clubs, 
such as for school groups or other groups of chess enthusiasts.  
It uses a standard chess rating formula that can be modified to 
suit your club. Data entry feature for game results and player info.

---------
Features:
-add player
-set initial player statistics
-add new game
-calculates and updates rankings
-allows you to modify player statistics
-supports one chess club only
-password system allows only administrator to modify information but anyone can view it.
-to change password, modify password configuration in chess.php.

---------------------------------------
To get started, follow the steps below:

1. Create a new MySQL database with a user account 
and execute the commands in the file chessschema.sql to 
create the database tables.

2. Modify chessdb.php with the Database server name,
database name, username, and password of the database
you just created.

3. Modify chess.php to change the password. The password
config is at the top of the file. Also change the name
of your chess club in this file.

4. Put the php files on your web server and you are ready to
go!

----------------
Release history:

0.1.2 - Maintenance release.
Date: May 23, 2008
Author: Geoff Peters
Changes:
-Just a couple of minor updates.
-Now works with PHP 4.1.0 and above.
-Removed requirement on php_setglobals, now can be run without setglobals.
-Fixed rounding error in $change calculation.

0.1.1 - First alpha release. 
Date: March 10, 2005
Author: Geoff Peters
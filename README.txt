
BOOKCASE                                                                                                                         

A CMS (Content Management System) Project developed in DRUPAL.
The website displayed book reviews.
Primarily books were from following genres: Mysteries, Fiction and Thrillers.
Users could create accounts, login and read these reviews.
Users could also comment on the book reviews.

Technologies:
Drupal 7.5, Wamp, Php, MySql.

Future Implementations:
•	Add more genres and more books in each genre.
•	Bridge the Social gap through Facebook pages and Twitter handles.
•	Collaborate with world renowned authors and publish dates of release of books.


This site is hosted on Wamp.
Wamp server
Wamp 3.0.4 was used throughout this project 
U can download it from their official site
Php any version above 7


Views
View module is extended for creating views.

Steps to download/implement in your workstation
1)Install Wamp server 
2)Install Notepad++
3)Go into www directory of wamp.(wamp's default directory is in C/programfiles/wamp, unless you have changed it during installation.wamp and wamp64 refer to the same directory.(32 bit or g4 bit))
4)Paste this buycase directory in www directory.
5)Start your wamp server.
6)For importing the database ,you need to go to your localhost.phpmyadmin/ and creare a new database named "buycase".
7)Then open that database in phpmyadmin and click on import button present at rop right corner.
8)Select the buycase/buycase.sql file as the database(If max size is less than 9 MN then change your wamp settings by "http://stackoverflow.com/questions/20264324/how-to-import-1gb-sql-file-to-wamp-phpmyadmin").
9)This may take time so please wait until all the tables have been imported.
10)Once done,go to localhost/buycase
11)The Drupal installation menu will open you select choices as shown in buycase/screenshots/screenshots/docx.
12)This takes some time once you have completed the installation the site will be shown.
13)Now,when you click on anylink in the site it will redirect you to localhost(wamp servers homepage).
14)To solve this enable apache's rewrite_module from the wamp console.
15)Now again visit your site localhsot/buycase
Enjoy the book reviews
admin login is
uname:admin
pw:admin
Thank you

Also please refer to the Screenshots present at home/screenshots/screenshots.docx.
If you have any problems u can always pm me at delta501405@gmail.com


Below is some information about drupal in general


CONTENTS OF THIS FILE
---------------------

 * About Drupal
 * Configuration and features
 * Appearance
 * Developing for Drupal

ABOUT DRUPAL
------------

Drupal is an open source content management platform supporting a variety of
websites ranging from personal weblogs to large community-driven websites. For
more information, see the Drupal website at http://drupal.org/, and join the
Drupal community at http://drupal.org/community.

Legal information about Drupal:
 * Know your rights when using Drupal:
   See LICENSE.txt in the same directory as this document.
 * Learn about the Drupal trademark and logo policy:
   http://drupal.com/trademark

CONFIGURATION AND FEATURES
--------------------------

Drupal core (what you get when you download and extract a drupal-x.y.tar.gz or
drupal-x.y.zip file from http://drupal.org/project/drupal) has what you need to
get started with your website. It includes several modules (extensions that add
functionality) for common website features, such as managing content, user
accounts, image uploading, and search. Core comes with many options that allow
site-specific configuration. In addition to the core modules, there are
thousands of contributed modules (for functionality not included with Drupal
core) available for download.

More about configuration:
 * Install, upgrade, and maintain Drupal:
   See INSTALL.txt and UPGRADE.txt in the same directory as this document.
 * Learn about how to use Drupal to create your site:
   http://drupal.org/documentation
 * Download contributed modules to sites/all/modules to extend Drupal's
   functionality:
   http://drupal.org/project/modules
 * See also: "Developing for Drupal" for writing your own modules, below.

APPEARANCE
----------

In Drupal, the appearance of your site is set by the theme (themes are
extensions that set fonts, colors, and layout). Drupal core comes with several
themes. More themes are available for download, and you can also create your own
custom theme.

More about themes:
 * Download contributed themes to sites/all/themes to modify Drupal's
   appearance:
   http://drupal.org/project/themes
 * Develop your own theme:
   http://drupal.org/documentation/theme

DEVELOPING FOR DRUPAL
---------------------

Drupal contains an extensive API that allows you to add to and modify the
functionality of your site. The API consists of "hooks", which allow modules to
react to system events and customize Drupal's behavior, and functions that
standardize common operations such as database queries and form generation. The
flexible hook architecture means that you should never need to directly modify
the files that come with Drupal core to achieve the functionality you want;
instead, functionality modifications take the form of modules.

When you need new functionality for your Drupal site, search for existing
contributed modules. If you find a module that matches except for a bug or an
additional needed feature, change the module and contribute your improvements
back to the project in the form of a "patch". Create new custom modules only
when nothing existing comes close to what you need.

More about developing:
 * Search for existing contributed modules:
   http://drupal.org/project/modules
 * Contribute a patch:
   http://drupal.org/patch/submit
 * Develop your own module:
   http://drupal.org/developing/modules
 * Follow best practices:
   http://drupal.org/best-practices
 * Refer to the API documentation:
   http://api.drupal.org/api/drupal/7


Project Flipkart
Instructions
● HTML, JS, CSS, and PHP code should be in separate files, none of the codes must co-exist in the same file.
● Only use Jquery AJAX for interacting with the backend (strictly no usage of form submission).
● CSS can be used but the form must be designed in bootstrap in order to maintain page responsiveness.
● Use MySql for storing the registered data and MongoDB for Storing the details of the user profiles
● In MySQL always use Prepared Statements, with no usage of simple SQL statements.
● The login session should be maintained only using browser localstorage (Do not use PHP Session)
● Use Redis to store the session information in the backend.

To achieve the above task the steps are needed to be as follows
First create the file structure
For Your Reference: ![image](https://github.com/IONHAX04/Flipkart-task/assets/93087438/b3eeb82d-9eba-478d-a1ab-a0943f14a149)

Next use composer init
![image](https://github.com/IONHAX04/Flipkart-task/assets/93087438/d2ce839a-3ad5-4ecb-86cc-9e6be9078b47)
use the package type as project for this
FYR: Package Type (e.g. library, project, metapackage, composer-plugin) []: project

Use the following commands to isntall the packages
composer require vlucas/phpdotenv predis/predis mongodb/mongodb
![image](https://github.com/IONHAX04/Flipkart-task/assets/93087438/72a32ebe-719e-468c-acb6-edd9a940a654)

Before this,check that the php, mongodb, mysql all are installed or not


use command 
- composer require twbs/bootstrap-icons
- composer require twbs/bootstrap:5.3.3

to install bootstrap icons & bootstrap
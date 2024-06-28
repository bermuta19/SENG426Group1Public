# Ucrypt Final Version 

## New Feature: 
   As an admin I want to view how many new accounts are waiting to be accepted so that i can go to the admin panel and accept them 
## What files did I change to implement this feature?
### Frontend only
   I have modified these files: (1. UCryptPortal\src\app\modules\admin\components\admin-layout\admin-layout.component.ts, 2.UCryptPortal\src\app\modules\admin\components\admin-layout\admin-layout.component.html)

## Bug Fix:
   I have fixed the Triple DES key generation bug
## What files did I modify to fix this bug?
### Backend only
crypto-back\src\main\java\io\uranus\ucrypt\services\support\encryption\impl\TripleDesEncryptionHandler.java

## To run the application: 
   * You need to have Docker Desktop and MySQL Server
   * You need a fresh ucrypt database on your MySQL Server
   * You can modify the application.properties file to change the admin email and password.
   * For MySQl connection, you will need to modify the file application.properties and docker-compose.yml file (username, password, etc.
   * Then start the Docker Desktop(better to delete old images and containers if any)
   * Then open the repo and cd to crypto-back and run "docker-compose build" wait for it to finish successfully, and then run "docker-compose up".
   * Visit localhost obviously port 80.
   * Try changing role.
   * Try uploading and then deleting files at admin resources section.

  

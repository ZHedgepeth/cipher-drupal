# _Cipher application on Drupal_

#### _A site that allows for the user to enter a direction to shift, a value to shift, and a phrase to cipher to allow a user to encrypt a message._

#### By _**Zach Hedgepeth**_

## Description

_This application allows a user to encrypt a message by entering a value to shift, a direction to shift, and a phrase. Then by submitting all of the requirements Cipher will output an encrypted message with the aforesaid inputs._

## Specifications

_User enters a shift value, a direction, and a phrase and is returned with an encrypted message_
    * eg input: 1, right, Cipher
    * eg output: Djqifs

_User enters a shift value, direction, or phrase that is out of scope with the correct qualifications_
    * eg input: q, upsy, 4()&
    * eg output: "Phrase is incompatible with Cipher"

## Setup/Installation requirements

    * _enter "git clone (repository url)" into terminal_
    * _Start MAMP and in preferences set "cipher" as document root._
    * _Use MAMP to start Apache and MySQL servers._
    * _Open PHPMyAdmin in browser and select the import tab._
    * _Select the .sql.zip file saved in cipher/sites/db-backup_
    * _Create a user in the newly created database w/ credentials the same as those stored in the settings.php file. In this case all credentials are cipher_

## Running/Development

    * Visit your application at http://localhost:8888

## Support and Contact Details

    * _Contact my email at Zhedgepeth1124@gmail.com_

## Known Bugs

    * _none_

# Technologies used

    * _Drupal_
    * _PHP_

# License

    * _Copyright 2016 Zach Hedgepeth  Epicodus license_

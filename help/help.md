#Known configurations:

## Gmail
* Host : smtp.gmail.com
* Username : your gmail address (ex:foobar@gmail.com)
* Password : your gmail password
* Port : 465
* Encryption : ssl
* Authentification : yes

You must activate less secure app on gmail, as new security requirement are not currently supported in phpmailer.   
Go to:
https://www.google.com/settings/security/lesssecureapps

Security advice:   
* Create a new email just for this purpose and put a strong password on it.   
* Kana must stored in plain text your password so it could use it.

## Outlook
* Host : smtp-mail.outlook.com
* Username : your outlook address (ex:foobar@outlook.com)
* Password : your outlook password
* Port : 587
* Encryption : tls
* Authentification : yes

## Your internet provider
Some Internet provider let you send email without identification as long as you do it from your own connection.
* Host : smtp.[PROVIDER].com (ex:smtp.free.fr)
* Username : any adresses you want (ex: master@internet.org) (but you should better use your own address)
* Password : no password needed
* Port : 25
* Encryption : none
* Authentification : none

## Others
https://support.mozilla.org/en-US/kb/isp-configuration-settings


# [Contribute to this document](https://github.com/madnerds/kana-email/blob/master/help/help.md)

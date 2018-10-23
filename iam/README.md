# Things to do for new 'Root' account:
* Setup correct Name, address, Telephone
* Setup strong password: minimum 15 characters (My Security Credentials)
* Setup credit card information
* Note the Root Account ID
* Setup 2FA/MFA for root account
* Setup challenge questions and answers (under main user name -> My Account)
* Setup alternate email contacts for billing, admin, and operations (My Account)
* Do not setup any Access keys, because you will never use this account for doing anything at AWS - at all.
* Setup Alerts in Billing and Cost Management
* Setup strong password policy for all future users under the root account.
* Setup a group with some admin rights
* Setup a normal user and make it a member of that group
* Setup good password for this new user, enable MFA, and setup Access Keys, etc.
* Use this new user for all general work you do on AWS
* Use your Root account only for super admin tasks like billing, and creating more groups and users, etc.


# Note on passwords (in general):
Passwords must always be easy to remember, but difficult to guess. 
* At least 15 characters, so brute-force attacks become meaningless
* Ideally non-english words, so dictionary attacks cannot work
* Use a mix of Urdu, Panjabi, Arabic, Farsee, French , etc.
* Do not use special language characters, which are locale specific. For example, in case of norwegian, do not use Å Ø Æ characters in passwords. Stick to standard US/UK/English letters, numbers and other general special characters.
* 

## Some easy to remember passwords / examples:
* Purana-Neela-Sweater : Pur@n@-N331@-5w3@t3r
* Puranee-Kalee-Patloon : Pur@n33-K@133-P@t100n
* Pink-Dubl33-Murghee : P!nk-Du6133-Mur9h33
* Gulabee-Anda-Muchlee: Gu1@633-And@-Much133


# Setup 2FA/MFA for your AWS account
Setup Two Factor Authentication / Multi Factor Authentication for your AWS account.

First, install a mobile app on your mobile phone. e.g. Google Authenticator

Then, in your AWS console, login as the user you want to setup 2FA/MFA for. From the main interface, go to IAM->Users->Security credentials. Use the following screens as example to setup MFA using your mobile phone.

![Setup-MFA-1.png](Setup-MFA-1.png)
![Setup-MFA-2.png](Setup-MFA-2.png)
![Setup-MFA-3.png](Setup-MFA-3.png)


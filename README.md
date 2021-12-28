
**Table of Contents**
  - [Purpose](#purpose)
  - [Usability vs Security](#usability-vs-security)
- [Password Managers](#password-managers)
  - [Overview](#overview)
  - [Types of Password Managers: Browser vs Cloud](#types-of-password-managers-browser-vs-cloud)
  - [Password Manager Examples](#password-manager-examples)
- [URL Spoofing](#url-spoofing)
- [Secure Web Browsing](#secure-web-browsing)
- [Two-Factor Authentication](#two-factor-authentication)
- [Risks of Public Wifi](#risks-of-public-wifi)
- [Software Updates](#software-updates)
- [Periodic Backups](#periodic-backups)

### Purpose

In my experience working in tech, colleagues and coworkers routinely share up-to-date information with each other on how increase personal security. Best practices are readily shared and encouraged to use. Sometimes I take this for granted when I talk with immediate family and close friends that they do not employ similar practices. I believe there's a gap in knowledge where the learning curve may appear to be too steep or unknown altogether for individuals who cannot spend many hours learning what a best security practice is, why is recommended to use, the risky effects of not employing it, and the different products available to aid in applying that security practice. This is a need that I personally believe has been looked over far too often, especially with how many new malicious practices are created to exploit ordinary people.

If COVID has taught the world anything, it’s that the people you are connected to can have a massive effect on your physical health. One person in your network has risky behavior, it can jeopardize everyone’s health within your network.  The same principle applies to digital health. Using the same password, or passwords with slight variations for every single account one uses is like going to a packed house party during the first covid lockdown--you’re asking to get sick and eventually pass that sickness unto others. The “sickness” in this analogy could be your bank information, social security number, addresses, contacts, etc being dumped on the dark web for another person to buy for pennies. That information is sold to subsequent parties to steal identities, empty bank accounts, dox people, or even just use your personal information without giving informed consent. While no one’s security is fool-proof, there are easy steps to take to make your life easier and reduce the risk of your information falling into malicious hands. This short document is meant to increase the average person’s tech health without having to do extensive research on their own and to make this process as quick and painless as possible.

### Usability vs Security
A common sentiment in technical security is that the more secure something is, the harder it is to use. The same goes for the opposite: the easier something is to use, the less secure it is. While this is not applicable across the board, one will likely encounter this concept when reading through these recommended practices. The goal is for one to determine what their own sweet spot of ease-of-use and security. This answer will vary by person. This information intends to give a few possible solutions to the reader. 

## Password Managers
*Time to implement: 5 min to 1 hour* 
### Overview

Password managers are extremely useful because they can keep track of sensitive information instead of the user trying to remember every username, password, security questions, etc from the hundreds of accounts the world expects us to have nowadays. In addition, they can generate secure passwords, look up to see if that password/hacked, and notify you when the password needs to be changed. Many password managers can be used over multiple devices as well as between family members.

### Types of Password Managers: Browser vs Cloud
There are many different types of password managers. However only two will be discussed--browser-based and cloud-based. If you use Google's browser, Chrome, or Safari, you are probably familiar with a browser password manager. Chrome and Safari typically ask the user whether they want to save their passwords or for the browser to create a password for the user. The advantage of using this type of password manager is the ease of use. If you use the same browser across devices with the same account on all of them, then it's quick and easy to use. The disadvantes of this type of password manager are that they typically never log the user out, internet is required and no advanced features included. If a device is stolen, all passwords (and most likely web history) are compromised. If you use the Chrome passowrd manager for your bank information, the malicious actor could look at the user's browser activity, see the bank website was visited, and then automatically login with the browser password manager.

A cloud-based password is recommended because it is more secure than a browser-based manager, it can easily sync across multiple devices, store different types of information from login usernames/passwords, driver liscense information, healthcare information, misc. notes, vehicle information, addresses, and much more. These managers scan for when users' passwords have been compromised and recommends users to update passwords on a regular basis. Internet is only needed to sync across devices. Other than that, these managers do not need internet. 

TODO: add bit about how there's a learning curve. Once that's achieved, then ease-of-use rather than "usability" greatly increases. 

### Password Manager Examples
[Google Chrome](https://passwords.google.com)\
[Bitwarden](https://bitwarden.com/pricing) \
[Last Pass](https://www.lastpass.com/pricing)

There are directions on the links shared above that show how to install both of them. There are free versions for each, but I recommend investing in the paid versions. You will only need one.

Note: It takes a lot of time to remember every account you use and add that account to a password manager. It takes weeks/months to transfer all accounts into password managers. Start with important and/or vulnerable accounts such as financial and healthcare information.

## URL Spoofing
Most, if not all people have seen a URL. A URL is the web address that directs users to a specific website or document. Example: *www.google.com*. There are a few types of URL spoofing. The first type of URL spoofing is when malicious actors use a URL that looks like a common or realistic URL that you would normally be accustomed to clicking on and going to. Example: *www.gooogle.com*. If you look close at the previous URL, there is an extra 'o' added to 'google'. In this case, it will not direct you to google, but to another website instead. Many times, these URLs are misspelled by a letter or number that if the user is not paying attention, they will not catch. 

By redirecting users to different sites, actors could be stealing your personal information, accesssing your devices, accessing the networks you are on, or install malware on those devices. 

I was discussing the creation of this document with a colleague the other day and this collegue related a personal story of spoofing that had recently happened to her. She has a venmo account where here transactions with friends and family are public. For privacy reasons, I'll give her the username of `janedoe151`. A malicious actor decided to create a new account with the username `janedoe251` and used the original account's avatar as the fake account's avatar. The fake account then preceded to request a few hundred dollars from groceries from her mom and her friends. She recieved a text from her mom saying, "Sent payment!" and another from a friend saying "Why do you need money for groceries?" It was only then that my colleague realized another account was impersonating her and her mother had sent money to a stranger. Her friend identified the strange behavior and verified with my colleague before sending payment, which is the correct move. If they had all originally looked a bit closer then they could've realized that this username was fake.

## Secure Web Browsing
TODO

## Two-Factor Authentication
TODO

## Risks of Public Wifi
TODO

## Software Updates
*Time: ~3 minutes*

We've all seen the notifications on our phones, computers, browsers, etc. that tell us to constantly update our software. It's so easy to think it's an unimportant hassle. However, updates are quite important. Commonly, updates are used to fix security flaws. If those flaws are not fixed, it leaves your devices at risk for malicious parties to exploit your devices and information. So, when you see the next notification for an update, make sure to do so. 

## Periodic Backups
TODO


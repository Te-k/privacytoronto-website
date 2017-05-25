+++
date = "2017-05-24T23:10:05-04:00"
title = "Feedback - Privacy 101: An Open Discussion"
+++

Our first event took place the 16th of May, and it was amazing ! Here is a short summary of our discussions that day.

## Threat Models

When we consider physical security, we are constantly developing models in order to be secure in our daily life : don't drive when you are drunk, be careful when going in certain areas... These models are really personals, each one of us develop a different threat model depending on where we live, what activities we have, who we are (in terms of race, gender, sexual orientation...) etc.

For some reason, creating these models is not as intuitive when it comes to digital security. So it is interesting to consider consciously how we create these models. The EFF in the [Security Self Defense guide](https://ssd.eff.org/en/module/introduction-threat-modeling) list five steps to think about our threat models :

1. What do you want to protect?
2. Who do you want to protect it from?
3. How likely is it that you will need to protect it?
4. How bad are the consequences if you fail?
5. How much trouble are you willing to go through in order to try to prevent those?

Access Now has published [some interesting examples of threat models](https://www.accessnow.org/cms/assets/uploads/2017/05/A-first-look-at-digital-security_DigitalCopy.pdf) like this one:

{{< figure src="/media/threatmodel.png">}}

We think that Threat Modeling is a very powerful and empowering tool because it clearly state that each one of us is responsible to define our own security. It is very easy when it come to privacy and security to fall into scarying or shaming discussions (like "how can you use Facebook if you want privacy?") and we think that it is a very bad approach. We consider that privacy and security discussions should be empowering and give tools for everyone to take conscious decisions about what risk we are ready to take and what compromise we want to do.

## Strategies of Resistance

We then did a workshop developed by [Tactical Tech](https://tacticaltech.org/) called "Strategies of Resistance" (see the description [here](https://myshadow.org/ckeditor_assets/attachments/226/strategies_of_resistance.pdf)). There are four different strategies to increase your security and privacy :

* **Reduction** : share less information ! During the workshop, we mentioned that it is for instance possible for activists to avoid speaking about the content of a meeting online, and keep the discussion face to face.
* **Obfuscation** : mix your real data with a lot of fake information on you so that people cannot identify what truely come from you. An example of this is the software [TrackMeNot](https://cs.nyu.edu/trackmenot/) which send random requests to search engines in the background, so that they cannot create an accurate profile of your researchs.
* **Compartmentalisation** : segregate data for different aspects of your life. You may do this quite naturally by using a different computer for you work, but another example is for instance to have different social media profiles for different aspects of your life.
* **Fortification** :  increase protection of your data. This category includes many common ways to protect yourself like strong passwords, or encryption of personal data.

Each one of us wrote post-its with solutions we have to protect our security/privacy and we drew a map on a paper board:

{{< figure src="/media/reduction.png">}}

{{< figure src="/media/obfuscation.png">}}

{{< figure src="/media/compartementalisation.png">}}

{{< figure src="/media/fortification.png">}}

## Passwords

We finally had a short presentation about passwords (you can find the slides [here](http://slides.com/tekk/passwords#/)). There are three important steps to secure your accounts with passwords :

* Use strong passphrases
* Use a password manager
* Use 2 Factor Authentication

### Passphrases

Here is an interesting way to create strong passphrases :
* Think about passphrases and not passwords
* Take four words that make sense to you
* Add special characters, capital letters and numbers.

The reason for choosing passphrases over passwords is well explained by xkcd [here](https://xkcd.com/936/) :

{{< figure src="/media/password_strength.png">}}

### Password Managers

A password manager is a software which will store securely passwords for you, so that you just have to remember one passphrase : the one to open the password manager. Passwords managers can be offline (the file is stored on your computer, you have to be careful not to loose it and you have to manage synchonisation between devices by yourself) or online (stored on a server but you have to trust the company hosting your passwords). During the workshop we presented three different tools

* [KeePass](http://keepass.info/) is an offline open source password manager available for Windows, Mac and Linux
* [LastPass](https://www.lastpass.com/) is a free online password manager (with a premium option)
* [1password](https://1password.com/) is a online password manager (costs $3/month)

[Marting Shelton](https://twitter.com/mshelton) has done some nice articles explaining how to choose between these solutions and how to use them:

* [Password Managers for Beginners](https://medium.com/@mshelton/password-managers-for-beginners-d1f49866f80f)
* [KeePass for Beginners](https://medium.com/@mshelton/keypass-for-beginners-dc8adfcdad54)
* [LastPass for Beginners](https://medium.com/@mshelton/lastpass-for-beginners-e921f35d4114)
* [1Password for Beginners](https://medium.com/@mshelton/introduction-to-password-managers-5e15baa8b26e)

### 2 Factor Authentication

2 Factor Authentication is a very powerful tool to increase your security. The idea is to have something additional to your password when your authenticate. It can be based on three different tools :

* **A text message** (or phone call) to your phone number with a token that you have to enter in the website with your password when you authenticate. This method is easy to use but we know that for skilled attacks, it is possible to steal sms by abusing the phone network, it is thus not recommended for at risk users
* **An application** on your phone like [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en). These apps generate a new code every 30 seconds that you have to enter with your password.
* **A specific USB key** like the [YubiKey](https://www.yubico.com/product/fido-u2f-security-key/) that you have to plug in your computer in addition to your password when you login. Few platforms support this option for now and it is only possible with Chrome but it is a strong solution.

[This good website](https://twofactorauth.org/) list platforms supporting 2 Factor authentication and link to their documentation, it is a good start to configure it. (Most social media and email platforms today support 2FA, see for instance [here for Google](https://www.google.com/intl/en-US/landing/2step/features.html), [here for Twitter](https://support.twitter.com/articles/20170388) or [here for Facebook](https://www.facebook.com/help/148233965247823))

One last important thing to remember with 2FA is that **you can get locked out of your account if you loose your second factor**. So be sure to **save backup codes when you setup 2FA** (backup codes are one-time code that you can use instead of your second factor in case of problem with it). A password manager may be a good place to save them :)


Thanks again to everyone who participated to the event, and thanks to [the 519](http://www.the519.org/) for giving us a room! Feel free to contact us [on Twitter](https://twitter.com/torontoprivacy) or by email (torontoprivacy AT protonmail.com) if you have any question.



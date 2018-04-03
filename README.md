# Online Security and Privacy for the Paranoid
A master checklist to secure your online life. 

This is forever a work in progress. If you have any suggestions, please send a PR or tweet [@adilmajid](https://www.twitter.com/adilmajid).

Note: I'm not affiliated with any products linked below, nor do I get any kind of commission/freebies/highfives for linking to them. They're just good products for the job that I have used.

### Table of Contents
- [TLDR](#tldr)
- [Beginner](#beginner)
  - [Logins](#logins)
  - [Cleanup](#cleanup)
  - [Browsers](#browsers)
  - [Banking](#banking)
  - [Your Phone](#phones)
  - [Your Computer](#computers)
- [Advanced](#advanced)
- [Google](#google)
- [Facebook](#facebook)
- [Credit Security](#credit)

<hr>

## TLDR

### If you only do five things...
* [ ] Set up 2FA on all of your Logins
* [ ] Set different passwords for all of your accounts. Use a password manager like [1Password](https://1password.com), [LastPass](https://www.lastpass.com), or [KeePass](https://keepass.info).
* [ ] Pay attention to whether a website uses http or https. Never type a password or other sensitive info into a website that only uses http.
* [ ] Update your Google settings to limit what Google tracks and update Facebook to limit what you share with others. ([see below](#google))
* [ ] Install a VPN on your computer and phone [Reviews](https://www.pcworld.com/article/3198369/privacy/best-vpn-services-apps-reviews-buying-advice.html)

<hr>

## Beginner

### Logins
* [ ] Set up 2FA (two-factor authentication) on all of your accounts that support it. [Twofactorauth.org](https://twofactorauth.org/) has a full list of apps that support 2FA.
* [ ] Set up login notifications on apps/services that allow it. If somebody does manage to compromise that account, you'll be notified and can take action to get it back.
* [ ] Use different passwords for all of your accounts
* [ ] Generate secure passwords [LastPass Generate](https://lastpass.com/generate)
* [ ] Use a password manager like [1Password](https://1password.com), [LastPass](https://www.lastpass.com) or [KeePass](https://keepass.info). Change the master password periodically.
* [ ] Update login information (or entirely delete the account) for compromised accounts
* [ ] On services that allow it, check for active sessions, and delete any unused, forgotten, or unapproved sessions

### Cleanup
* [ ] Delete your all of your unused and unnecessary accounts
* [ ] Use [Have I Been Pwned](https://haveibeenpwned.com) to see if any of your accounts have been compromised

### Browsers
* [ ] Pay attention to when a website is using https, and never type a password or other sensitive info into a site that doesn't use https
* [ ] Use a browser plugin like [uBlock Origin](https://github.com/gorhill/uBlock), privacy badger, and ghostery to prevent third parties from tracking you
* [ ] Switch away from Google Chrome and Microsoft Edge and use [Firefox](www.firefox.com) or [Brave](www.brave.com) instead
* [ ] Set cookies, history, etc to delete after 30 days (or less!)


### Banking
* [ ] Use [Privacy.com](http://privacy.com) when doing online transactions. Enable transaction notifications to be notified every time money is spent from those cards
* [ ] Disable paper bank statement mailings (they can be lost/stolen)


### Phones
* [ ] Keep your OS and apps updated
* [ ] Set a passcode / password of 6+ characters
* [ ] Disable TouchID / fingerprint unlock. If a federal agent wants to search your device, they are allowed to ask for your fingerprint, but not your passcode.
* [ ] Restrict what someone can see/do with your phone from the lock screen (lock screen widgets, notification privacy, Apple Pay/Android Pay/Samsung Pay)
* [ ] Disable location services for any app that doesn't really need it. Disable "always on" location services from all apps.
* [ ] Get rid of your Android and get an iPhone (not intentionally pretentious - it's hard to fully secure an Android device. And there are great iPhones at basically any price point these days.)
* [ ] Install a VPN
* [ ] Install a content blocker to prevent you from being tracked by advertisers


### Computers
* [ ] Keep your OS and apps updated
* [ ] Turn on Firewall on your Mac (via System Preferences -> Security)
* [ ] Cover your computer webcam with a Post-it
* [ ] Set a short screensaver time - 5 min or less - so your laptop locks itself once you're away
* [ ] Require password immediately once your computer goes to sleep
* [ ] Install [Micro Snitch](https://www.obdev.at/products/microsnitch/index.html) to monitor when your webcam and microphone are turned on
* [ ] Install [Malwarebyte](http://malwarebytes.org) on your computer, and run it periodically to check for malware
* [ ] Set Mac lockscreen notifications to private
* [ ] For the super-paranoid, not tied to Mac or Windows: consider using [QUBES OS](https://www.qubes-os.org) or [Tails OS](https://tails.boum.org)


### Other
* [ ] Secure your Skype account, if you need it. Delete it if you don't need Skype. (Good alternative is Google Duo, which saves some metadata but has encrypted calls.) Skype is a top offender for getting hacked.
* [ ] Delete your Yahoo account. If you need it for Flickr, set a long password, set up 2FA, and enable login notifications. Yahoo is another common offender
* [ ] Set strict privacy options on Facebook (see below). They have a lot of your info, important to protect it
* [ ] Set strict privacy options on Google (see below). Same as FB, they know a looooot about you
* [ ] Don't buy knockoff smart home appliances. This includes security cameras
* [ ] Get rid of your Amazon Alexa and Google Home. They're listening

<hr>

## Advanced

### Secure Browsing
* [ ] Use [Tor](https://www.torproject.org) for web browsing. The more people use it the better the network is
* [ ] Use [Firefox Focus](https://itunes.apple.com/app/id1055677337) on iOS
* [ ] Use [Panopticlick](https://panopticlick.eff.org) to test whether your browser setup is safe against tracking
* [ ] Don't use unsecured wifi networks without a VPN
* [ ] Install a VPN client on your computer. Check out [PCWorld's reviews of popular VPN clients](https://www.pcworld.com/article/3198369/privacy/best-vpn-services-apps-reviews-buying-advice.html).
* [ ] Install a VPN client on your phone ([Encrypt.me](https://encrypt.me) and [Tunnelbear](http://tunnelbear.com) are pretty good)
* [ ] Install [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) to monitor outgoing connections (basically a reverse Firewall).

### Secure Communication
* [ ] Use encrypted communication methods - [Signal](https://whispersystems.org), [ProtonMail](https://protonmail.com/)
* [ ] Make sure that any device or app you store sensitive info in is encrypted.  (Evernote, Day One, etc.) You can generally find out from their marketing site or FAQ, and if its not there, then contact their support team.

### Secure Your Offline Life
* [ ] Consolidate external hard drives and USB thumbdrives so you have fewer things to keep track of.
* [ ] Consolidate notebooks and papers that could have sensitive info, shred the ones you don't need. Archive papers by scanning into (a secured) Evernote account if you don't need the physical copy.
* [ ] Wipe unused old computers, phones, tablets, hard drives, etc.

<hr>

## Google

### Secure Login
* [ ] Set up 2FA
* [ ] Set up login notifications
* [ ] Review your active sessions and end sessions you don't recognize
* [ ] Review what apps have access to your data via Google login

### Reclaim Your Data
* [ ] Clear search history
* [ ] Disable search history
* [ ] Clear location history
* [ ] Disable maps and location history
* [ ] Check Google+ for what data Google has made public, set anything you don't like to private

### Beast Mode
* [ ] Switch to [DuckDuckGo](https://duckduckgo.com) as your  main search engine. (You can set it as default for Safari, Chrome, Firefox, and iOS Safari now)

<hr>

## Facebook

### Secure Login
* [ ] Set up 2FA
* [ ] Set up login notifications
* [ ] Review your active sessions and end sessions you don't recognize
* [ ] Review what apps have access to your data via Facebook login

### Reclaim Your Data
* [ ] Set up "Approve Posts on Your Timeline". This allows you to approve posts on your Timeline and photos/statuses you're tagged in.
* [ ] Remove excess info on your profile. Go through your "About" section — most of these are set to public or Friends. Limit them as you see fit, and remove excess info.
* [ ] Limit past posts to "Friends", make sure these aren't public
* [ ] Go through each of your Profile Pictures and set them to Friends or stricter. Profile Pictures are Public by default.
* [ ] Go through each of your Cover Photos and set them to Friends or stricter. Your current Cover Photo will always be Public, but older ones can be restricted to Friends.
* [ ] Go through old photos and clean up! If necessary, ask friends to take down ones you no longer want online.
* [ ] Use [Dataselfie](http://dataselfie.it) to see how machine learning algorithms map your personality

## Credit
Whether you've been affected by the Equifax hack or not, take the following steps to secure your credit.
* [ ] Freeze your credit reports with all three agencies: [Equifax](https://www.freeze.equifax.com/Freeze/jsp/SFF_PersonalIDInfo.jsp), [Experian](https://www.experian.com/freeze/center.html), and [Transunion](https://www.transunion.com/credit-freeze/place-credit-freeze).
* [ ] Sign up for Identity Theft Monitoring. There are a number of services offered that you can Google. I personally use [Civic](https://www.civic.com).
* [ ] Stop getting prescreened offers of credit. [You can learn more about prescreened offers of credit here](https://www.consumer.ftc.gov/articles/0497-credit-freeze-faqs). The FTC recommends this service for opting-out, aptly named [OptOutPrescreen.com](https://www.optoutprescreen.com/?rf=t). 
* [ ] These guys have GARBAGE websites. So you'll probably need to get live phone support. Equifax: Call 888-202-4025 and select option 6. Experian: Call 714-830-7000, press 2 (the business line option), then ask for live help. TransUnion: 800-916-8800. 

# Online Security and Privacy for the Paranoid

_"Only the paranoid survive."_

A master checklist to secure your online life. 

This is a work in progress. Comments and feedback are much appreciated. If you have any suggestions, please submit a PR or tweet [@adilmajid](https://www.twitter.com/adilmajid).

Note: I'm not affiliated with any products linked below, nor do I get any kind of commission/freebies/highfives for linking to them. They're just good products for the job that I have used.

Disclaimer: this is a list of good practices, but no guarantees, obviously.

### Table of Contents
- [TLDR](#tldr)
- [Lockdown](#lockdown)
  - How to secure your online accounts, phone, laptop, and finances. 
- [Control the data you've shared](#cleanup)
  - What to do about the data you've already shared.
- [Go Pro](#go-pro)
- Other Stuff
  - [Be Good](#be-good)
  - [Best Practices](#best-practices)
  - [Reign in Google](#google)
  - [Reign in Facebook](#google)
  - [Secure your Crypto](#crypto)
  - [Prevent SIM Swap Attacks](#sim-swap-attack-protection)

<hr>

# TLDR

### If you only do five things...
* [ ] Set up 2FA on all of your logins
* [ ] Set different passwords for all of your accounts. Use a password manager like [1Password](https://1password.com), [LastPass](https://www.lastpass.com), or [KeePass](https://keepass.info).
* [ ] Pay attention to whether a website uses http or https. Never type a password or other sensitive info into a website that only uses http.
* [ ] Update your Google settings to limit what Google tracks and update Facebook to limit what you share with others. ([Google](#google))([Facebook](#facebook))
* [ ] Delete online accounts you don't need or use

<hr>

# Lockdown
Virtually every online service you use stores some of your personal information. It could be as basic as your name and email address. Or it could be highly personal, like your sexual orientation, your notes and documents, your credit card information, your messages… so on.  This is information you want kept safe. 

Many services are broadcast platforms, meaning you want to make sure nobody should be able to access these accounts other than you.

## Secure your online accounts
* [ ] Use a different password for every online service.
* [ ] Generate secure passwords using [1password Password Generator](https://1password.com/password-generator/) or [LastPass Generate](https://lastpass.com/generate). A secure password is not necessarily composed of complicated combinations of special characters. These are difficult to remember. Instead, a long password (like an easy-to-remember phrase of 5 or more words) is more secure because it has more characters is harder to guess by brute force. 
* [ ] Use a password manager like [1Password](https://1password.com), [LastPass](https://www.lastpass.com) or [KeePass](https://keepass.info). Change the master password periodically.
* [ ] Set up two-factor authentication (2FA) on your accounts where its available. [Twofactorauth.org](https://twofactorauth.org/) has a full list of apps that support 2FA.
* [ ] Set up login notifications on apps/services that allow it. If somebody does manage to compromise that account, you'll be notified and can take action to get it back.

## Secure your phone
* [ ] Keep your OS and apps updated
* [ ] Set a passcode / password of 6+ characters
* [ ] Disable TouchID / fingerprint unlock. If a federal agent wants to search your device, they are allowed to ask for your fingerprint, but not your passcode.
* [ ] Restrict what someone can see/do with your phone from the lock screen (lock screen widgets, notification privacy, Apple Pay/Android Pay/Samsung Pay)
* [ ] Disable location services for any app that doesn't really need it. Disable "always on" location services from all apps.
* [ ] Get rid of your Android and get an iPhone (not intentionally pretentious - it's hard to fully secure an Android device. And there are great iPhones at basically any price point these days. And Google doesn't get to vacuum up all your data.)
* [ ] Install a VPN
* [ ] Install a content blocker to prevent you from being tracked by advertisers

## Secure your computer
* [ ] Keep your OS and apps updated
* [ ] Turn on Firewall on your Mac (via System Preferences -> Security)
* [ ] Cover your computer webcam with a Post-it
* [ ] Set a short screensaver time - 5 min or less - so your laptop locks itself once you're away
* [ ] Require password immediately once your computer goes to sleep
* [ ] Install [Micro Snitch](https://www.obdev.at/products/microsnitch/index.html) to monitor when your webcam and microphone are turned on
* [ ] Install [Malwarebyte](http://malwarebytes.org) on your computer, and run it periodically to check for malware
* [ ] Set Mac lockscreen notifications to private

## Secure finances

### Banking
* [ ] Use [Privacy.com](http://privacy.com) when doing online transactions. Enable transaction notifications to be notified every time money is spent from those cards
* [ ] Disable paper bank statement mailings (they can be lost/stolen)

### Credit
Whether you've been affected by the Equifax hack or not, take the following steps to secure your credit.
* [ ] Check your credit report. Make sure there are no unexpected hard pulls on your credit.
* [ ] Freeze your credit reports with all three agencies: [Equifax](https://www.freeze.equifax.com/Freeze/jsp/SFF_PersonalIDInfo.jsp), [Experian](https://www.experian.com/freeze/center.html), and [Transunion](https://www.transunion.com/credit-freeze/place-credit-freeze).
* [ ] Sign up for Identity Theft Monitoring. There are a number of services offered that you can Google. I personally use [Civic](https://www.civic.com).
* [ ] Stop getting prescreened offers of credit. [You can learn more about prescreened offers of credit here](https://www.consumer.ftc.gov/articles/0497-credit-freeze-faqs). The FTC recommends this service for opting-out, aptly named [OptOutPrescreen.com](https://www.optoutprescreen.com/?rf=t). 
* [ ] These guys have GARBAGE websites. So you'll probably need to get live phone support. Equifax: Call 888-202-4025 and select option 6. Experian: Call 714-830-7000, press 2 (the business line option), then ask for live help. TransUnion: 800-916-8800. 

## Secure your offline life
Most people don't think about this one, but it matters. Leaving personal information lying around is a liability.

* [ ] Consolidate external hard drives and USB thumbdrives so you have fewer things to keep track of.
* [ ] Consolidate notebooks and papers that could have sensitive info, shred the ones you don't need. Archive papers by scanning into (a secured) Evernote account if you don't need the physical copy.
* [ ] Wipe unused old computers, phones, tablets, hard drives, etc.

<hr>

# Cleanup
You have personal data in all of your accounts. Some of those accounts can broadcast information to the internet on your behalf (think Instagram, Twitter, or a blog). If you aren’t using an account, delete it. They’re a vulnerability.

* [ ] Delete accounts you no longer use.
* [ ] Use [Have I Been Pwned](https://haveibeenpwned.com) to see if any of your accounts have been compromised
* [ ] Secure your Skype account, if you need it. Delete it if you don't need Skype. Skype is a top offender for getting hacked.
* [ ] Delete your Yahoo account. If you need it for Flickr, set a long password, set up 2FA, and enable login notifications. Yahoo is another common offender

## Limit what companies can track about you
* [ ] Limit what Google tracks about you. See how
* [ ] Limit what Facebook tracks about you. See how
* [ ] Think carefully about new services you sign up for and the data you share with them.. Do you trust them with your data? 
* [ ] Be careful when granting Location permissions to apps on your phone. Google and Facebook apps, for instance, keep a horrifyingly detailed log of your location history. 
* [ ] Be careful when granting Contacts access to apps on your phone. Are they going to sync your contacts to their server? FYI: Messenger does! And is super shady about it.

<hr>

# Go Pro
So... You want to go pro.

You've secured your accounts and deleted the ones you don't use. Now you want to go dark.

Unfortunately, that's near impossible, but you can do certain things to get close.

## Use privacy-friendly services
* [ ] Use [Tor](https://www.torproject.org) for web browsing. The more people use it the better the network is
* [ ] For the super-paranoid, not tied to Mac or Windows: consider using [QUBES OS](https://www.qubes-os.org) or [Tails OS](https://tails.boum.org)
* [ ] Use [Signal](http://signal.org) or [WhatsApp](https://whatsapp.com) for end-to-end encrypted messaging
* [ ] Use [ProtonMail](https://protonmail.com) for encrypted email
* [ ] Install [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) to monitor outgoing connections (basically a reverse Firewall). Your computer sends a lot of dat in the background that you might not know about. With Little Snitch you can see when and where information from your computer is being sent
* [ ] Use [DuckDuckGo](https://duckduckgo.com) as your search engine. They're great, they don't track you, and they're profitable, so no need to worry about them shutting down one day

## Browse Securely
* [ ] Use a browser plugin like [uBlock Origin](https://github.com/gorhill/uBlock), privacy badger, and ghostery to prevent third parties from tracking you
* [ ] Don't use unsecured wifi networks without a VPN
* [ ] Install a VPN client on your computer. Check out [PCWorld's reviews of popular VPN clients](https://www.pcworld.com/article/3198369/privacy/best-vpn-services-apps-reviews-buying-advice.html). My favorite is [Mullvad](http://mullvad.net). They don't require any personal info, like name or email address, for registration, and you can pay in cash or crypto.
* [ ] Install a VPN client on your phone ([Encrypt.me](https://encrypt.me) and [Tunnelbear](http://tunnelbear.com) are pretty good). I prefer Mullvad here as well.
* [ ] Use [Panopticlick](https://panopticlick.eff.org) to test whether your browser setup is safe against tracking
* [ ] Use [DNS Leak Test](https://www.dnsleaktest.com) to test whether your VPN setup is working
* [ ] Switch away from Google Chrome and Microsoft Edge and use [Firefox](www.firefox.com), Apple Safari, or [Brave](www.brave.com) instead
* [ ] Use [Firefox Focus](https://itunes.apple.com/app/id1055677337) on iOS
* [ ] Set cookies, history, etc. to delete after 30 days (or less!)

## Last but not least...
* [ ] Delete Facebook and Google. Yes, this is obviously easier said than done. But Facebook and Google are the worst offenders against individual privacy. They vacuum personal data like a surveillance state. They are dishonest about hacks and data leaks.

<hr>

# Other Stuff

## Be Good
* [ ] Support companies that protect your data. By support, I mean pay for their services. If you don’t, they’ll go out of business, and all we’ll have left are free products that vacuum up all of the user data they can.
* [ ] Follow the [Electronic Frontier Foundation](https://www.eff.org). And [donate](https://supporters.eff.org/donate/join-eff-today)! They do great work.

## Best Practices
* [ ] Don’t use phone numbers for 2FA. See [SIM Swap Attack Protection](#sim-swap-attack-protection) below.
* [ ] Do a regular security audit. Regularly passwords for your “key” accounts. Check for active logged-in sessions that you don’t recognize.
* [ ] Make sure that any device or app you store sensitive info in is encrypted.  (Evernote, Day One, etc.) You can generally find out from their marketing site or FAQ, and if its not there, then contact their support team.
* [ ] Don't buy knockoff smart home appliances. This includes security cameras.
* [ ] Get rid of your Amazon Alexa and Google Home. They are listening!

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
* [ ] Switch to [DuckDuckGo](https://duckduckgo.com) as your  main search engine. (You can set it as default for Brave, Safari, Chrome, Firefox, and iOS Safari now)
* [ ] Switch to [Brave Browser](https://brave.com) as your browser instead of Chrome.

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

## Crypto
* [ ] Don't keep your coins on an exchange. Always make sure you control your private key. 
* [ ] Use a paper wallet or hardware wallet like Ledger Nano S or Trezor. 
* [ ] MetaMask users: be aware of these risks: [6 Ways a Site Can Attack your MetaMask](https://blog.hellobloom.io/6-ways-a-site-can-attack-your-metamask-190e6651e400)

## SIM Swap Attack Protection
A SIM swap attack is when a hacker calls your cell provider and convinced them to transfer your phone number to them. They then use your number to gain access to your other accounts. [More Info](https://www.wired.com/story/sim-swap-attack-defend-phone/?mbid=BottomRelatedStories_Sections_1)
* [ ] Set a pin on your SIM
* [ ] Don't use SMS for two-factor authentication. Use Google Authenticator, Authy, or a USB-key instead.

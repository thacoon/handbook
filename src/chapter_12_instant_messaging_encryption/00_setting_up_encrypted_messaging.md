Setting up Encrypted Instant Messaging
======================================

Android - Conversations
-----------------------
[https://github.com/siacs/Conversations](https://github.com/siacs/Conversations)

Conversations is an open source Android XMPP/Jabber client and you can encrypt your chats with OMEMO, OTR or OpenPGP. Conversations relies on the XMPP protocol and does not require a Google Account or Google Cloud Messaging (GCM). You can get it from Google Play store or F-Droid.

You can securly chat with other app that uses the XMPP Protocol and uses one of the three encryptions supported by Conversations.

Android - Installing Zom (previously known as ChatSecure and Gibberbot)
-----------------------------------------------------------------------
[https://github.com/zom/Zom-Android](https://github.com/zom/Zom-Android)

Zom Android is a secure messaging app that uses open standards like XMPP/Jabber and OTR encryption. Accordingly, it uses end-to-end encrypted and a decentralized approach. Zom does not require a Google Account or Google Cloud Messaging (GCM). You can install Zom from the official website by downloading the apk file ([https://zom.im/](https://zom.im/)), there is also a link to Google Play store and iOS Appstore.

You can securly chat with other apps like Conversations.

Android/iOS - Signal
--------------------

[https://whispersystems.org](https://whispersystems.org)

Signal is another open-source secure messaging app that uses end-to-end encryption. It relies on the Signal Protocol which is also used by closed-source apps like WhatsApp. The Signal protocol is designed for encrypting instant messaging. Unlike OTR not both users have to be online at the same time. But Signal cannot be directly used without Google Cloud Messaging. Although Signal is open source and rely on a secure and tested protocol every Signal account is tied to a phone number. This means by using Signal you are still exposing more metadata than necessary that can be analyzed. Analyzing your metadata can be used to gain knowledge about personal information. There is a scientific paper about "Evaluating the privacy properties of telephone metadata" at [http://www.pnas.org/content/113/20/5536.full](http://www.pnas.org/content/113/20/5536.full).

iOS - Installing ChatSecure
---------------------------

[http://chrisballinger.info/apps/chatsecure/](http://chrisballinger.info/apps/chatsecure/)

ChatSecure is a secure chat client capable of end-to-end encryption. It works with Google, Facebook, any Jabber or XMPP server. ChatSecure uses the Off-the-Record encryption standard (OTR) to enable true verifiable end-to-end encrypted communications.

You can install ChatSecure through the iTunes store

You can securely chat with other programs with OTR support such as Adium, Pidgin on the desktop, Gibberbot on Android or ChatSecure on iOS.

Ubuntu - Installing Pidgin
--------------------------

[http://pidgin.im/](http://pidgin.im/)

Pidgin is a secure chat client capable of end-to-end encryption. It works with Google, Facebook, any Jabber or XMPP server. Pidgin uses the Off-the-Record encryption standard (OTR) to enable true verifiable end-to-end encrypted communications.

You can install via Ubuntu Software Center, search for pidgin-otr to install pidgin and the pidgin otr plugin.

Once installed you can enable otr for any account you setup in pidgin.

You can securely chat with other programs with OTR support such as Adium, Pidgin on the desktop, Gibberbot on Android or ChatSecure on iOS.

OS X - Installing Adium
-----------------------

[http://www.adium.im/](http://www.adium.im/)

Adium is a secure chat client capable of end-to-end encryption. It works with Google, Facebook, any Jabber or XMPP server. Adium uses the Off-the-Record encryption standard (OTR) to enable true verifiable end-to-end encrypted communications.

Installing Adium is similar to installing most Mac OS X applications.

 1. Download the Adium disk image from [http://www.adium.im/](http://www.adium.im/).
 2. If an Adium window does not open automatically, double click the downloaded file
 3. Drag the Adium application to your Applications folder.
 4. "Eject" the Adium disk image, which has an icon of a drive
 5. The Adium disk image will still be present in your download folder (probably on your desktop). You can drag this file to the trash, as it is no longer needed.
 6. To load Adium, locate it in the Applications folder and double click.

You can securely chat with other programs with OTR support such as Adium, Pidgin on the desktop, Gibberbot on Android or ChatSecure on iOS.

Windows - Installing Pidgin
---------------------------

[http://pidgin.im/](http://pidgin.im/)

Pidgin is a secure chat client capable of end-to-end encryption. It works with Google, Facebook, any Jabber or XMPP server. Pidgin uses the Off-the-Record encryption standard (OTR) to enable true verifiable end-to-end encrypted communications.

To use Pidgin with OTR on Windows, you have to install Pidgin and the OTR plugin for Pidgin.

 1. Download the latest version of Pidgin for Windows from [http://www.pidgin.im/download/windows/](http://www.pidgin.im/download/windows/)
 2. Run the Pidgin Installer
 3. Download the latest version of "OTR plugin for Pidgin" at [http://www.cypherpunks.ca/otr/#downloads](http://www.cypherpunks.ca/otr/#downloads)
 4. Run the OTR Plugin Installer

Now you can use OTR with any account you setup in Pidgin.

You can securely chat with other programs with OTR support such as Adium, Pidgin on the desktop, Gibberbot on Android or ChatSecure on iOS.

All OS - crypto.cat
-------------------

[https://crypto.cat](https://crypto.cat)

Cryptocat is an open source web application intended to allow secure, encrypted online chatting. Cryptocat encrypts chats on the client side, only trusting the server with data that is already encrypted. Cryptocat is delivered as a browser extension and offers plugins for Google Chrome, Mozilla Firefox and Apple Safari.

Cryptocat intends to provide means for impromptu, encrypted communications that offer more privacy than services such as Google Talk, while maintaining a higher level of accessibility than other high-level encryption platforms, and furthermore allows for multiple users in one chat room.

Chat Log Files
--------------

Some of the Chat Clients listed above e.g. Adium, store plaintext, unencrypted Chat Logs, often by default, even when the OTR "security / privacy" plug-in is installed.

If you are taking OTR precautions to protect your chats from snoopers over the wire or over the air, you should either double check that you have manually switched off Chat Session Logging, or ensure that the Chat Logs you deliberately intend to keep are created on an encrypted disk drive or volume, in case your computer is lost, stolen or seized. It is also worth asking the person you are chatting with if they are inadvertently logging the chat with their own Chat Client software.

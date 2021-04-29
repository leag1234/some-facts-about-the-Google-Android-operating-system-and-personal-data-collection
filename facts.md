**About Android**

Android (AOSP) is an open source operating system maintained by Google. In its commercial version, that ships in 80% of the smartphones on the market, “Google Android” includes a proprietary layer called “Google Play Services”.

In the following, we refer to:
- “Android” when talking about the core open source Android OS (AOSP
- “Google Android” when talking about the commercial version of Android that ships in most Android smartphones.

**What we found in the Android operating system**

- DNS (Domain Name Service): Google DNS servers (like 8.8.8.8 and 8.8.4.4) are used by default in Android. This lets Google potentially trace all calls to any internet servers and services from the operating system or applications run by the user.
    “Connectivity Check”: when an Android phone is powered on, a Connectivity Check function is performed as an HTTP request against some Google servers to ensure that Internet access is available in IPv4 and IPv6. This lets Google learn that a Google Android device as been started.
- NTP (Network Time Protocol). Traditionally, NTP servers are maintained by voluntary organizations all over the world to help any operating system synchronize with correct time over the Internet network. Google operates its own NTP servers and Android uses Google NTP servers by default
- The “Google Play Services” layer offers applications a number of services to applications. One of these services is the “Network Location Provider”. It’s a geolocation service that helps making geolocation faster and more efficient in some case, especially for indoor use. By default the Google geolocation service is used. Google is therefore aware of the geo-location of all Android smartphones with Internet access, in real time and worldwide.
- The push notifications used by applications in Google Android use the Google Push Notification services over the GCM/FCM cloud messaging infrastructure.
- The application store in Google Android is by default the Google Play Store. Its API is not public and the Terms of Services of Google Play Store a priori prohibit[TO BE CHECKED] accesses to the Google Play Store without going through the official service. Google Play Store is not interoperable at all.
- The SafetyNet feature in Google Android offers application developers and publishers the possibility to verify that the smartphone on which the application is running is so called “safe”. This feature makes it difficult for even legitimate Android vendors to allow applications using this feature to run. It is also generally accepted that SafetyNet does not actually offer any security guarantee to applications: false positives and false negatives are possible in all cases.
- The Google Chrome web browser is installed by default in Google Android, with Google Search set by default
- Google Chrome now defaults to DoH (DNS over HTTPS) using Google DNS servers, potentially allowing Google to track the user’s entire browsing history in real time
- It is almost impossible to use Android without a Google account set in the running OS
- The default mail application in Google Android is Gmail, and it will in most cases be configured immediately with a Google Gmail account.
- Gmail emails are not encrypted server side: Google has access to them and implicitely addmits in the GMail Terms of Services that all Gmail contents are analysed automatically.
- Payment solution: Google Pay by default in Google Android

**Studies on systematic data collection in Google Android**

- One Google Android phone = 12 MB of personal data/day to Google (Apple users are not forgotten: 6MB/day to Google, in exchange for a $13 Billion check per year).
    “Google Data Collection,” Douglas C. Schmidt, Professor of Computer Science at Vanderbilt University – 2018
    https://digitalcontentnext.org/blog/2018/08/21/google-data-collection-research/
- “Even with minimal phone configuration, in standby, both iOS and Google Android share data with Apple/Google, on average every 4.5 minutes” “when a SIM is inserted both iOS and Google Android send details to Apple/Google. Users have no way of escaping this, and to date there are few, if any, realistic alternatives to protect against this information sharing.”
    Mobile Handset Privacy: Measuring The Data iOS and Android Send to Apple And Google – Professor Doug Leith at School of Computer Science and Statistics at Trinity College Dublin – 2021
    https://www.scss.tcd.ie/doug.leith/apple_google.pdf

**Pressure on Manufacturers**

  - Google does not want any other version of Android on the market. The Android anti-fragmentation agreement called “MADA” – that is effective worldwide except in the EU – prohibits smartphone manufacturers from offering non-Google Android smartphones as long as they already sell Google Android smartphones.
  - Likely: informal pressure “to stay friends” and cooperative

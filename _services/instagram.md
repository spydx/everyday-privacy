---
name: Instagram
slug: instagram
logo: /assets/img/services/instagram/logo.svg
owner: Facebook, Inc.
recent_breach:
tags:
  - Proprietary
  - Free
  - Social Media
desc: >-
  Photo and video sharing social network, usually connected to your Facebook account.

security:
  - desc: Activate Two-Factor Authentication (2FA)
    device:
      - name: app
        steps:
          - Go to your profile
          - Go to the hamburger menu -> <b>Settings</b>
          - Select <b>Security</b>
          - Select <b>Two-factor authentication</b>
          - Now you can setup with the method of your choice, it is recommended to use an <b>Authentication App</b> instead of <b>Text Message (SMS)</b>
          - Depending on the choice you make here, you will need to follow the instructions with the method you choose.
  - desc: Verify where you are logged in
    device:
      - name: app
        steps:
          - Go to your profile in the bottom right corner
          - Go to the hamburger-menu in top right corner
          - Tap <b>Settings</b>, choose </b>Security</b>
          - Verify where you are logged in
          - If there are some you do not recognize, or you are not sure, it is recommended to use <b>Log out of all sessions</b>-button.
  - desc: Choose a strong password
    device:
      - name: browser
        steps:
          - Go to <b>Settings</b>
          - Select <b>Change Password</b> on the left side
          - Use a unique password with at least 16 characters with lower- and uppercase characters, numbers and special symbols. (preferably from a <a href="/password-manager">password manager</a>)
      - name: app
        steps:
          - Go to your profile in the bottom right corner
          - Go to the hamburger-menu in top right corner
          - Tap <b>Settings</b>, choose </b>Security</b>
          - Then choose <b>Password</b>
          - Use a unique password with at least 16 characters with lower- and uppercase characters, numbers and special symbols. (preferably from a <a href="/password-manager">password manager</a>)

privacy:
  - desc: Disable contact syncing
    device:
      - name: app-only
        steps:
          - Go to your profile in the bottom right corner
          - Go to the hamburger-menu in top right corner
          - Tap <b>Settings</b>, choose </b>Account</b>
          - Go to <b>Contact syncing</b>
          - Toggle it off
  - desc: Delete synced contacts
    device:
      - name: browser-only
        steps:
          - Go to <b>Settings</b>
          - Select <b>Manage Contacts</b> on the left side
          - Click <b>Delete All</b>
  - desc: Disable data sharing with advertisers
    device:
      - name: app-only
        steps:
          - Go to your profile in the bottom right corner
          - Go to the hamburger-menu in top right corner
          - Tap <b>Settings</b>, choose </b>Ads</b>
          - Go to <b>Data About Your Activity From Partners</b>
          - Toggle off <b>Use Data from Partners</b>
  - desc: Download your data
    device:
      - name: app
        steps:
          - Go to your profile in the bottom right corner
          - Go to the hamburger-menu in top right corner
          - Tap <b>Settings</b>, choose </b>Security</b>
          - Choose <b>Download Data</b>
          - Input your email and tap <b>Request Download</b>
          - It may take up to 48 hours to receive the data
      - name: browser
        steps:
          - Go to <b>Settings</b>
          - Select <b>Privacy and Security</b> on the left side
          - Under <b>Data Download</b>, click <b>Request Download</b>
          - Choose HTML for easiest to read data and click <b>Next</b>
  - desc: Delete your account
    device:
      - name: browser-only
        steps:
          - Go to the <a href="https://instagram.com/accounts/remove/request/permanent/">Delete Your Account</a>-page
          - Select an option
          - Click <b>Delete [username]</b>

breaches:
  - name: Facebook probes breach of millions of influencer accounts, Instagram
    url: https://www.bbc.com/news/world-asia-india-48347592
    date: 2019-05-21
  - name: 533 million Facebook users' phone numbers and personal data have been leaked online
    url: https://www.businessinsider.com/stolen-data-of-533-million-facebook-users-leaked-online-2021-4
    date: 2021-04-03
  - name: Facebook admits year-long data breach exposed 6 million users
    date: 2013-06-22
    url: https://www.reuters.com/article/net-us-facebook-security/facebook-admits-year-long-data-breach-exposed-6-million-users-idUSBRE95K18Y20130621
  - name: Facebook Bug Made Up to 14 Million Users Posts Public for Days
    date: 2018-07-06
    url: https://www.wired.com/story/facebook-bug-14-million-users-posts-public/
  - name: Facebook–Cambridge Analytica data scandal
    date: 2018-01-01 #TODO: need to verify this
    url: https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal

headlines:
  - name: Facebook Buys Instagram For $1 Billion
    url: https://www.forbes.com/sites/bruceupbin/2012/04/09/facebook-buys-instagram-for-1-billion-wheres-the-revenue/
    date: 2012-04-09
  - name: Facebook Says It’s Your Fault That Hackers Got Half a Billion User Phone Numbers
    url: https://www.vice.com/en/article/88awzp/facebook-says-its-your-fault-that-hackers-got-half-a-billion-user-phone-numbers
    date: 2021-04-07
  - name: "Facebook's privacy problems: a roundup"
    url: https://www.theguardian.com/technology/2018/dec/14/facebook-privacy-problems-roundup
    date: 2018-12-15

collect: # What they collect
  - what: Information in camera viewport
    how: Using the camera in the app, everything is analyzed in order to provide filters, masks and tips for using the camera.
  - what: Communications (Content, location data, who and when)
    how: Through posts, photos and messages.
  - what: Network and connections
    how: Who you are in contact with, people, pages, groups, hashtags.
  - what: Your usage
    how: How you interact with all of their products, engagement, who you share with, duration of interaction.
  - what: What others share and say about you
    how: What others say about you, shares with and about you. How people interacts with your profile, and imports from address books.
  - what: Debit or credit card number
    how: If you make any purchases using Facebook, these details will be saved and collected for 7 years.
  - what: Device information
    how: Via computers, phones, connected TVs and other web-connected device. Operating system, hardware and software versions, battery level, signal strength, available storage space, browser type, app and file names, types and plugins (browsers).
  - what: Device operations
    how: Operations and behaviors performed on the device, such as whether a window is foregrounded or backgrounded, mouse movements.
  - what: Identifiers
    how: Device IDs from your devices, ad identifiers from Facebook and other services, family device IDs.
  - what: Information from partners (even without an account)
    how: >-
      Your interactions with apps, ads using Facebook's Analytics tools. These partners provide information about your activities off Facebook - including information about your device, websites you visit, purchases you make, the ads yu see, and how you use their services, whether or not you have a Facebook account or are logged into Facebook.
  - what: Activities from other Facebook products
    how: They connect information about your activities on different Facebook products and devices.
  - what: Location information
    how: Current location, where you live, places you liked to visit, businesses and people near you to see what you enjoy and might enjoy.

last_update: 2021-05-09
---

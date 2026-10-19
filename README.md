# Awesome Ionic [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]

<p alt="Awesome Ionic" align="center"><img src="awesome-ionic.png" /></p>

> A curated list of awesome Ionic libraries, resources, and solutions for the latest versions of Ionic Framework and Capacitor.

This repository is maintained by [Dayana Jabif](https://github.com/djabif). For discussions about PRs and contributions, contact Dayana via DM on [twitter](https://twitter.com/djabif).

# Resources by Version

- [General](#general)
- [Ionic Angular](#ionic-angular)
- [Ionic React](ionic-react.md)
- [Ionic Vue](ionic-vue.md)
- [Capacitor](#capacitor)
- [Capawesome](#capawesome)
- [Live Updates](#live-updates)
- [Built with Ionic](#built-with-ionic)
- [Stencil](https://stenciljs.com/)

# General

- [Official Website](https://ionicframework.com/)
- [Blog](https://ionic.io/blog)
  - [Community Spotlight: Ionic Theme iOS 27](https://ionic.io/blog/introducing-ionic-theme-ios27)
  - [Announcing a Partnership with Capawesome](https://ionic.io/blog/%f0%9f%9a%80-announcing-a-partnership-with-capawesome)
  - [The Road to Capacitor 9](https://ionic.io/blog/the-road-to-capacitor-9)
- [Documentation](https://ionicframework.com/docs/)
- [Github Repository](https://github.com/ionic-team/ionic-framework)
- [Community Forum](http://forum.ionicframework.com/)
- [Capacitor](https://capacitorjs.com/)
- [Appflow](https://ionic.io/appflow) - reaches end of life on December 31, 2027, see [Live Updates](#live-updates) for the migration path
- [Ionic Framework MCP Server](https://capawesome.io/docs/ai/mcp/ionic-framework/) - Ionic docs for your AI assistant, by Capawesome
- [Ionic AI Agent Skills](https://capawesome.io/docs/ai/skills/) - `ionic-expert`, `ionic-angular`, `ionic-react`, `ionic-vue`, `ionic-app-creation`, `ionic-app-upgrades` and more, by Capawesome
- [Ionic Theme iOS 27](https://github.com/rdlabo-dev/ionic-theme-ios27) - community theme that brings the iOS 26 Liquid Glass look to Ionic
- [Ionic Youtube Channel](https://www.youtube.com/channel/UChYheBnVeCfhCmqZfCUdJQw)

# Capacitor

- [Official Website](https://capacitorjs.com/)
- [Documentation](https://capacitorjs.com/docs)
- [Capacitor Plugins](https://capacitorjs.com/docs/plugins)
- [Blog](https://capacitorjs.com/blog)
- [Forum](https://forum.ionicframework.com/c/capacitor)
- [Github Project](https://github.com/ionic-team/capacitor)
- [Twitter](https://twitter.com/capacitorjs)
- [Capacitor MCP Server](https://capacitor-mcp.capawesome.io/mcp) - Capacitor docs for your AI assistant
- [Awesome Capacitor](https://github.com/capawesome-team/awesome-capacitorjs) - curated list of Capacitor plugins, tools and resources, by Capawesome

## Capawesome

[Capawesome](https://capawesome.io/) is Ionic's official partner for Capacitor plugins, Live Updates, Native Builds and App Store Publishing.

- [Capawesome Cloud](https://capawesome.io/cloud/) - Live Updates (OTA), Native Builds and App Store Publishing for Capacitor and Cordova apps
- [Capawesome Plugins](https://capawesome.io/plugins/) - 100+ Capacitor plugins (SQLite, Biometrics, OAuth, Live Update, NFC, Background Geolocation, AdMob, Health...)
- [Capacitor Firebase Plugins](https://github.com/capawesome-team/capacitor-firebase)
- [Capacitor ML Kit Plugins](https://github.com/capawesome-team/capacitor-mlkit)
- [Capacitor Electron Platform](https://github.com/capawesome-team/capacitor-electron) - desktop apps from your Capacitor project
- [Capacitor Tauri Platform](https://github.com/capawesome-team/capacitor-tauri)
- [Documentation](https://capawesome.io/docs/)
- [Blog](https://capawesome.io/blog/) - Capacitor tutorials and guides
- [YouTube Channel](https://www.youtube.com/@capawesomeio)
- [Github Organization](https://github.com/capawesome-team)
- [Awesome Capacitor](https://github.com/capawesome-team/awesome-capacitorjs) - Capawesome's curated list of Capacitor resources

# Live Updates

Live Updates (also called OTA or over-the-air updates) let you push changes to the web layer of your Ionic app directly to users, without waiting for an app store review. Ionic Appflow, the original Live Updates service, reaches end of life on December 31, 2027. Ionic [officially recommends](https://ionic.io/blog/%f0%9f%9a%80-announcing-a-partnership-with-capawesome) Capawesome Cloud as its successor.

## Tools

- [Capawesome Cloud Live Updates](https://capawesome.io/docs/cloud/live-updates/) - channels, gradual rollouts, rollbacks, code signing and Electron support
- [Capacitor Live Update Plugin](https://capawesome.io/docs/sdks/capacitor/live-update/) - `@capawesome/capacitor-live-update`, the client SDK for Capacitor apps
- [Capawesome CLI](https://capawesome.io/docs/cloud/cli/) - upload bundles and manage channels from the terminal or CI
- [Live Update GitHub Action](https://github.com/capawesome-team/cloud-live-update-action) - deploy a bundle on every push
- [Capawesome Cloud Open Source Program](https://capawesome.io/blog/capawesome-cloud-open-source-program/) - free Live Updates for open source apps
- [Cordova Live Update Demo](https://github.com/capawesome-team/cordova-live-update-demo)

## Migrating from Ionic Appflow

- [Ionic Appflow Is Shutting Down: Here's Your Migration Plan](https://capawesome.io/blog/migrating-from-ionic-appflow-to-capawesome-cloud/)
- [Appflow Migration Docs](https://capawesome.io/docs/cloud/migrations/ionic-appflow/) - import your Appflow apps with a single CLI command
- [Migrating Ionic Portals Live Updates to Capawesome Cloud](https://capawesome.io/blog/migrating-ionic-portals-live-updates-from-appflow-to-capawesome/)
- [Alternative to Ionic Appflow](https://capawesome.io/blog/alternative-to-appflow/)
- [Announcing Our Official Partnership with Ionic](https://capawesome.io/blog/announcing-partnership-with-ionic/)
- [Ionic Appflow Migration: Export & Import into Capawesome Cloud](https://www.youtube.com/watch?v=NuK571iCaNA) (video)
- [Migrate from Ionic Appflow in ONE Command](https://www.youtube.com/watch?v=N-H_mtCZiPA) (video)

## Guides

- [Capacitor Live Updates: The Complete OTA Guide](https://capawesome.io/blog/capacitor-live-updates-guide/)
- [How Capacitor Live Updates Work Under the Hood](https://capawesome.io/blog/how-live-updates-for-capacitor-work/)
- [The Right Way to Update Your Capacitor App Remotely](https://capawesome.io/blog/the-right-way-to-update-your-capacitor-app-remotely/)
- [How to Gradually Roll Out Live Updates for Capacitor Apps](https://capawesome.io/blog/how-to-gradually-roll-out-capacitor-live-updates/)
- [How to Reduce the Bundle Size of Capacitor Live Updates](https://capawesome.io/blog/how-to-reduce-the-bundle-size-of-capacitor-live-updates/)
- [Capacitor Live Updates: Signing vs Encryption](https://capawesome.io/blog/capacitor-live-updates-end-to-end-encryption/)
- [Best Live Update Tools for Capacitor](https://capawesome.io/blog/best-ota-update-tools-for-capacitor/)
- [Cordova Live Updates: A Complete Guide to OTA Updates](https://capawesome.io/blog/cordova-live-updates-guide/)
- [Exploring the Capacitor Live Update API](https://capawesome.io/blog/exploring-the-capacitor-live-update-api/)
- [How to Restrict Capacitor Live Updates to Native Versions](https://capawesome.io/blog/how-to-restrict-capacitor-live-updates-to-native-versions/)
- [Channel Pausing for Capawesome Cloud Live Updates](https://capawesome.io/blog/capawesome-cloud-channel-pausing/)
- [Channel Surfing with Capacitor Live Updates](https://capawesome.io/blog/capawesome-cloud-channel-surfing/)
- [Forced Channel Assignments for Capawesome Cloud Devices](https://capawesome.io/blog/capawesome-cloud-forced-channel-assignments/)
- [Capacitor Live Updates: Reliability & Uptime](https://capawesome.io/blog/capacitor-live-updates-reliability-and-uptime/)
- [Live Updates for Nuxt Capacitor Apps](https://capawesome.io/blog/live-updates-for-nuxt-capacitor/)
- [How Live Updates Are Changing Mobile App Deployment](https://capawesome.io/blog/how-live-updates-are-changing-mobile-app-deployment/)
- [Case Study: snapAddy Ships Live Updates to 1M+ Installations](https://capawesome.io/blog/case-study-snapaddy-live-updates/)

## Videos

- [Capacitor Live Updates Setup: Ship OTA Updates Without App Store Review](https://www.youtube.com/watch?v=rF1yxzR8tnE)
- [Capacitor Live Updates: Channels & Gradual Rollouts Explained](https://www.youtube.com/watch?v=Hg0ObWno3Zc)
- [Secure Capacitor Live Updates with Code Signing](https://www.youtube.com/watch?v=Z-Qu2f-ODv8)
- [Cordova Live Updates in 2026](https://www.youtube.com/watch?v=xmgyVkaqx48)

# Built With Ionic

- [Ionic Showcase](https://ionic.io/showcase) - companies building with Ionic, including T-Mobile, BBC, Mastercard, Morgan Stanley and Fidelity
- [National Health Service (NHS)](https://ionic.io/resources/case-studies/national-health-service) - case study
- [EGYM](https://ionic.io/resources/case-studies/egym) - case study
- [H&R Block](https://ionic.io/resources/case-studies/hrblock) - case study
- [Southwest Airlines](https://meetmaestro.com/work/southwest/) - case study

# Ionic Angular

## Complete projects

### Boilerplate/Demo Apps

- [Update your App](https://github.com/NextFaze/ionic-manup) ![](ionic.png)

### Open source apps

- [Capacitor SQLite Angular Demo](https://github.com/capawesome-team/capacitor-sqlite-angular-demo) ![](ionic.png)
- [Capacitor SQLite React Demo](https://github.com/capawesome-team/capacitor-sqlite-react-demo)
- [Capacitor OAuth Demo](https://github.com/capawesome-team/capacitor-oauth-demo)
- [Capacitor Biometrics Demo](https://github.com/capawesome-team/capacitor-biometrics-demo)
- [Capacitor Firebase Plugin Demo](https://github.com/capawesome-team/capacitor-firebase-plugin-demo)
- [Conference App](https://github.com/driftyco/ionic-conference-app) ![](ionic.png)

# Tutorials

#### Video Tutorials

**Capacitor & Capawesome**

- [Angular Web App to Native iOS & Android (Free Starter)](https://www.youtube.com/watch?v=cr3i03LNmG4)
- [Turn Your Lovable App Into a Real iOS & Android App](https://www.youtube.com/watch?v=_5l-wiVYkVY)
- [Getting Started with Capawesome Cloud: Your First App Setup](https://www.youtube.com/watch?v=RoFOASn83LE)
- [Build Your First iOS App in the Cloud (Free Certificate + Simulator Build)](https://www.youtube.com/watch?v=7N64zrcNE2M)
- [Build Your First Android App in the Cloud](https://www.youtube.com/watch?v=LygUq4BqRs8)
- [Test an iOS App on Your iPhone Without TestFlight (No Mac Needed)](https://www.youtube.com/watch?v=bGWnGNgXzxE)
- [Deploy iOS Builds to TestFlight Automatically](https://www.youtube.com/watch?v=6DY6kY8mUb8)
- [Automate Capacitor Builds with Git-Based Triggers](https://www.youtube.com/watch?v=39WNZroLZOE)
- [Environment Variables & Secrets in Cloud Builds](https://www.youtube.com/watch?v=aF1xIVZIuN8)
- [Free iOS Certificate & Android Keystore Generator: Signing Setup](https://www.youtube.com/watch?v=tKt3NNcFiCM)
- [Capacitor SQLite Tutorial: CRUD, Transactions & Local Database Setup](https://www.youtube.com/watch?v=JJg2r1UIxlk)
- [Capacitor Biometrics Plugin: Face ID & Fingerprint Auth](https://www.youtube.com/watch?v=ixUvTX6n7x8)
- [Capacitor Vault Plugin: Secure Sensitive Data with Face ID & Touch ID](https://www.youtube.com/watch?v=wCNMqVBnQqs)
- [Capacitor OAuth Tutorial: Auth0, Okta & Azure AD Login Done Right](https://www.youtube.com/watch?v=Cr1dJNN6Urw)
- [Capacitor Privacy Screen: Hide App Content & Block Screenshots](https://www.youtube.com/watch?v=eAjR2JkLFfg)
- [Capacitor Share Target Plugin: Receive Links, Text & Files From Other Apps](https://www.youtube.com/watch?v=a64fF_q69po)
- [Background Audio in Capacitor: Lock Screen Controls & Playlists](https://www.youtube.com/watch?v=y_REeVs_jAE)
- [Capawesome Insiders Setup: Get a License Key & Install SDKs via npm](https://www.youtube.com/watch?v=N4uH4VehMj8)

### Basics

- [Convert a Web App to a Mobile App in 11 Steps](https://capawesome.io/blog/11-steps-to-get-your-web-app-on-the-app-store/)
- [Capacitor Setup Guide for Any Web Framework](https://capawesome.io/blog/build-mobile-apps-with-any-web-framework-and-capacitor/)
- [Capacitor + Angular: Turn Your Web App into iOS & Android](https://capawesome.io/blog/how-to-wrap-an-angular-app-with-capacitor-and-firebase/)
- [How to Create Your Apple and Google Developer Accounts](https://capawesome.io/blog/how-to-create-apple-developer-and-google-play-accounts/)
- [How to Prepare Your App Store Listing](https://capawesome.io/blog/how-to-prepare-your-app-store-listing/)

#### Theming

- [Community Spotlight: Ionic Theme iOS 27](https://ionic.io/blog/introducing-ionic-theme-ios27) - Liquid Glass theme for Ionic
- [Install Tailwind CSS with Ionic Framework](https://capawesome.io/blog/install-tailwind-css-with-ionic-framework/)
- [Tailwind CSS Plugin for Ionic Framework](https://capawesome.io/blog/tailwind-css-plugin-for-ionic-framework/)

#### Authentication

- [How to Add Authentication to a Capacitor App](https://capawesome.io/blog/how-to-add-authentication-to-a-capacitor-app/)
- [How to Sign In with Apple Using Capacitor](https://capawesome.io/blog/how-to-sign-in-with-apple-using-capacitor/)
- [How to Sign In with Google Using Capacitor](https://capawesome.io/blog/how-to-sign-in-with-google-using-capacitor/)
- [How to Sign In with Auth0 Using Capacitor](https://capawesome.io/blog/how-to-sign-in-with-auth0-using-capacitor/)
- [How to Sign In with Okta Using Capacitor](https://capawesome.io/blog/how-to-sign-in-with-okta-using-capacitor/)
- [How to Sign In with Azure Entra ID Using Capacitor](https://capawesome.io/blog/how-to-sign-in-with-azure-entra-id-using-capacitor/)
- [How to Use Better Auth in Ionic and Capacitor Apps](https://capawesome.io/blog/how-to-use-better-auth-in-capacitor-apps/)
- [Firebase Authentication in Capacitor: Setup & Best Practices](https://capawesome.io/blog/capacitor-firebase-authentication-guide/)
- [How to Securely Store Credentials with Capacitor](https://capawesome.io/blog/how-to-securely-store-credentials-with-capacitor/)

#### Capacitor Plugins

- [How to Use SQLite in a Capacitor App](https://capawesome.io/blog/how-to-use-sqlite-in-a-capacitor-app/)
- [Encrypting SQLite Databases in Capacitor](https://capawesome.io/blog/encrypting-capacitor-sqlite-database/)
- [How to Use Drizzle ORM with Capacitor and SQLite](https://capawesome.io/blog/how-to-use-drizzle-orm-with-capacitor-and-sqlite/)
- [How to Use TypeORM with Capacitor and SQLite](https://capawesome.io/blog/how-to-use-typeorm-with-capacitor-and-sqlite/)
- [Capacitor Push Notifications: The Complete Guide](https://capawesome.io/blog/capacitor-push-notifications-guide/)
- [Capacitor File Handling: The Complete Guide](https://capawesome.io/blog/capacitor-file-handling-guide/)
- [Capacitor Edge-to-Edge & Safe Areas: The Complete Guide](https://capawesome.io/blog/capacitor-edge-to-edge-and-safe-areas-guide/)
- [The Complete Guide to Capacitor Device Sensors](https://capawesome.io/blog/capacitor-device-sensors-guide/)
- [How to Build an Ionic Barcode Scanner with Capacitor](https://capawesome.io/blog/how-to-build-an-ionic-barcode-scanner-with-capacitor/)
- [How to Scan and Write NFC Tags with Capacitor](https://capawesome.io/blog/exploring-the-capacitor-nfc-api/)
- [How to Track Location in the Background with Capacitor](https://capawesome.io/blog/how-to-track-location-in-the-background-with-capacitor/)
- [How to Add Geofencing to an Ionic App](https://capawesome.io/blog/how-to-add-geofencing-to-an-ionic-app/)
- [How to Detect the Network Status in Capacitor](https://capawesome.io/blog/how-to-detect-the-network-status-in-a-capacitor-app/)
- [Downloading Files in the Background in Capacitor](https://capawesome.io/blog/how-to-download-files-in-the-background-in-capacitor/)
- [How to Build a Heart Rate Monitor with Capacitor](https://capawesome.io/blog/how-to-build-a-heart-rate-monitor-with-capacitor/)
- [Reading Step Counts on iOS and Android with Capacitor](https://capawesome.io/blog/how-to-read-step-counts-in-a-capacitor-app/)
- [How to Handle AdMob GDPR Consent (UMP) in a Capacitor App](https://capawesome.io/blog/how-to-handle-admob-gdpr-consent-in-a-capacitor-app/)
- [Tips for Setting Up In-App Purchases with Capacitor](https://capawesome.io/blog/tips-for-setting-up-in-app-purchases-with-capacitor/)
- [How to Use Apple Intelligence in a Capacitor App](https://capawesome.io/blog/how-to-use-apple-intelligence-in-a-capacitor-app/)
- [How to Use Gemini Nano in a Capacitor App](https://capawesome.io/blog/how-to-use-gemini-nano-in-a-capacitor-app/)
- [How to Build an Apple Watch App for Your Capacitor App](https://capawesome.io/blog/how-to-build-an-apple-watch-app-for-your-capacitor-app/)
- [How to Build a Wear OS App for Your Capacitor App](https://capawesome.io/blog/how-to-build-a-wear-os-app-for-your-capacitor-app/)
- [Build a Desktop App with Capacitor and Electron](https://capawesome.io/blog/how-to-build-a-desktop-app-with-capacitor-and-electron/)
- [How to Patch a Capacitor Plugin](https://capawesome.io/blog/how-to-patch-a-capacitor-plugin/)

#### CI/CD, Builds & Publishing

- [CI/CD for Capacitor Apps: Choosing the Right Approach](https://capawesome.io/blog/choosing-the-right-ci-cd-approach-for-capacitor-apps/)
- [Best CI/CD Platforms for Capacitor Apps](https://capawesome.io/blog/comparing-ci-cd-platforms-for-capacitor-apps/)
- [CI/CD Pitfalls in Capacitor & How to Avoid Them](https://capawesome.io/blog/ci-cd-for-capacitor-common-pitfalls/)
- [How to Build and Deploy iOS Apps Without Owning a Mac](https://capawesome.io/blog/how-to-build-and-deploy-ios-apps-without-a-mac/)
- [How to Sign & Build Capacitor Apps in the Cloud](https://capawesome.io/blog/how-to-sign-and-build-your-capacitor-app-in-the-cloud/)
- [iOS Certificates and Provisioning Profiles Explained](https://capawesome.io/blog/ios-certificates-and-provisioning-profiles-explained/)
- [How to Distribute iOS and Android Apps to Testers](https://capawesome.io/blog/how-to-distribute-ios-and-android-apps-to-testers/)
- [Auto-Submit a Capacitor App to TestFlight and Google Play](https://capawesome.io/blog/auto-submit-capacitor-app-to-testflight-and-google-play/)
- [Build and Deploy iOS Apps with GitLab CI/CD](https://capawesome.io/blog/build-and-deploy-ios-apps-with-gitlab-ci-cd/)
- [Build & Ship iOS Apps with Bitbucket Pipelines](https://capawesome.io/blog/build-and-deploy-ios-apps-with-bitbucket/)
- [Publish a Capacitor App on Huawei AppGallery](https://capawesome.io/blog/how-to-publish-a-capacitor-app-on-huawei-appgallery/)
- [Lovable to Mobile App: iOS & Android Without a Mac](https://capawesome.io/blog/convert-lovable-app-to-mobile-app/)

#### Upgrades & Troubleshooting

- [How to Upgrade Your Capacitor App to Capacitor 8](https://capawesome.io/blog/how-to-upgrade-your-capacitor-app-to-capacitor-8/)
- [How to Migrate a Capacitor App to Swift Package Manager](https://capawesome.io/blog/how-to-migrate-a-capacitor-app-to-spm/)
- [Support 16 KB Page Sizes in Android with Capacitor](https://capawesome.io/blog/support-16kb-page-sizes-with-capacitor/)
- [Apple's New Xcode 26 Requirement for Capacitor Apps](https://capawesome.io/blog/xcode-26-requirement-for-capacitor-apps/)
- [The iOS Troubleshooting Guide for Capacitor](https://capawesome.io/blog/troubleshooting-capacitor-ios-issues/)
- [The Android Troubleshooting Guide for Capacitor](https://capawesome.io/blog/troubleshooting-capacitor-android-issues/)
- [Alternatives to Ionic Enterprise Plugins](https://capawesome.io/blog/alternatives-to-ionic-enterprise-plugins/)

#### AI-Assisted Development

- [How to Use AI Agents in Capacitor App Development](https://capawesome.io/blog/how-to-use-ai-agents-in-capacitor-app-development/)
- [Open Source AI Agent Skills for Capacitor](https://capawesome.io/blog/announcing-open-source-ai-agent-skills-for-capacitor/)
- [Ionic Framework MCP Server for Your AI Assistant](https://capawesome.io/blog/ionic-framework-mcp-server/)

#### Cordova Plugins

- [Kommunicate Live Chat Plugin for Customer Support](https://docs.kommunicate.io/docs/cordova-installation.html) ![](ionic.png)

#### Backend as a Service

- [How to Use Firebase in a Capacitor App](https://capawesome.io/blog/how-to-use-firebase-in-a-capacitor-app/)
- [Capacitor Firestore: Real-Time Data & Offline Sync](https://capawesome.io/blog/capacitor-firebase-cloud-firestore-guide/)
- [Upload & Manage Files with Firebase Storage in Capacitor](https://capawesome.io/blog/capacitor-firebase-cloud-storage-guide/)
- [Crash Reporting in a Capacitor App with Crashlytics](https://capawesome.io/blog/capacitor-firebase-crashlytics-guide/)

# Tools

- [Capawesome Tools](https://capawesome.io/tools/) - free online tools for mobile developers
  - [iOS Certificate Generator](https://capawesome.io/tools/ios-certificate-generator/) - create an iOS signing certificate without a Mac
  - [Android Keystore Generator](https://capawesome.io/tools/android-keystore-generator/) - create an Android keystore in the browser
  - [iOS UDID Finder](https://capawesome.io/tools/ios-udid-finder/) - find a device's UDID without a computer
- [Capawesome CLI](https://capawesome.io/docs/cloud/cli/) - manage Live Updates, builds and app store submissions from the terminal or CI
- [Capver](https://github.com/capawesome-team/capver) - version management for Capacitor apps
- [Capawesome GitHub Actions](https://github.com/capawesome-team/cloud-build-action) - native builds and [Live Updates](https://github.com/capawesome-team/cloud-live-update-action) from GitHub workflows
- [AI Agent Skills for Capacitor & Ionic](https://capawesome.io/skills/) - open source skills for Claude Code, Cursor, Copilot and other agents ([Ionic skills on GitHub](https://github.com/capawesome-team/skills/tree/main/skills/ionic-expert))
- [MCP Servers](https://capawesome.io/docs/ai/mcp/) - [Capacitor](https://capacitor-mcp.capawesome.io/mcp), [Ionic Framework](https://ionic-framework-mcp.capawesome.io/mcp) and [Capawesome](https://mcp.capawesome.io/mcp) docs for AI assistants

# Components

### Animations

- [Lottie Animation](https://github.com/chenqingspring/ng-lottie) ![](angular.png)
- [Lottie Animation](https://github.com/fivethree-team/lottie) ![](angular.png)

### Menu, Tabs

- [Fab Toolbar](https://github.com/ekhmoi/fab-toolbar) ![](ionic.png)

### Form / Input

#### Input - Date/Calendar

- [Capacitor Calendar Plugin](https://capawesome.io/docs/sdks/capacitor/calendar/)
- [How to Manage Recurring Calendar Events in Capacitor](https://capawesome.io/blog/recurring-calendar-events-in-capacitor/)
- [Capacitor Calendar Permissions on iOS 17+ and Android](https://capawesome.io/blog/capacitor-calendar-permissions/)
- **Calendar**
  - [Calendar](https://github.com/mattlewis92/angular-calendar) ![](angular.png) (very powerful)
- [Inputfield Mask](https://github.com/text-mask/text-mask)

### Lists/Table

- [Flexible and Light Table](https://github.com/swimlane/ngx-datatable) ![](angular.png)

### Images

- [How to Take and Edit Photos in a Capacitor App](https://capawesome.io/blog/how-to-take-and-edit-photos-in-a-capacitor-app/)
- [How to Scan a Document to PDF in a Capacitor App](https://capawesome.io/blog/how-to-scan-a-document-to-pdf-in-a-capacitor-app/)
- [Exploring the Capacitor File Compressor API](https://capawesome.io/blog/exploring-the-capacitor-file-compressor-api/)
- [Image Loader](https://github.com/zyramedia/ionic-image-loader) ![](ionic.png)
- [Image Viewer](https://github.com/Riron/ionic-img-viewer) ![](ionic.png)
- [Gallery Modal](https://github.com/nikini/ionic-gallery-modal) ![](ionic.png)

### Video/Audio

- [Capacitor Audio Player Plugin](https://capawesome.io/docs/sdks/capacitor/audio-player/) - background playback, playlists and lock screen controls
- [Capacitor Audio Recorder Plugin](https://capawesome.io/docs/sdks/capacitor/audio-recorder/)
- [How to Play Audio in the Background in a Capacitor App](https://capawesome.io/blog/how-to-play-audio-in-the-background-in-capacitor/)
- [Audio Player 8.4.0: Playlists and Media Session Support](https://capawesome.io/blog/capacitor-audio-player-8-4-0-release/)
- [Exploring the Capacitor Audio Recorder API](https://capawesome.io/blog/exploring-the-capacitor-audio-recorder-api/)
- [Capacitor Audio Player Demo](https://github.com/capawesome-team/capacitor-audio-player-demo)

### Frames

- [ng Lightning (for Salesforce Apps)](https://github.com/ng-lightning/ng-lightning) ![](angular.png)

# Are you Italian?

**Join** the italian [Ionic Framework community](https://www.facebook.com/groups/380772785422827/)! ![](ionicitalia.jpg)

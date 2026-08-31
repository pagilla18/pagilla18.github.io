# pagilla18.github.io

Robin Sound Labs
Premium Minimalist Audio/Video Environments

Welcome to Robin Sound Labs. We engineer premium, minimalist media players—including Pure Audio Music Player, Canary Player: Music Player, and Fire Video Player. For full details regarding our developer identity, comprehensive privacy policy (covering offline data handling, device permissions, Chromecast local network operations, monetization frameworks, and children's privacy), and corporate contact channels, please refer to the complete markdown layout provided in the repository source.

Developer Transparency & Identity

In compliance with Google Play Developer Policies and global merchant guidelines, our engineering operations are mapped directly to our legal corporate registration:

Legal Entity Name: PAGILLA LINGA RAJU
Registration Number: UDYAM-TS-09-0257094 (Micro Enterprise)
Registered Address: Plot No. 42, Pagilla Lingaraju Building, Sri Rama Hills Colony, Road No. 4C, Mansoorabad, Lb Nagar, Ranga Reddy, Hyderabad, Telangana, India, Pincode: 500068
Corporate Support Desk: pagilla18@gmail.com
Official Hotline: +91 6305992280
Privacy Policy

Last Updated: August 31, 2026

Welcome to Robin Sound Labs. We are committed to protecting your digital sovereignty. This Privacy Policy explains how our applications handle data on your Android device. This policy applies to both our premium paid applications and our free-to-download ad-supported versions.

1. Information Collection and Use

Our applications function fundamentally as local, offline media players.

Personal Data: Robin Sound Labs does not collect, store, transmit, or share any personal identification information (such as your name, email address, phone number, or telemetry location data).
Media Files: The applications require user permission to access local device storage solely to scan, index, and display your local media (audio, video) files for playback management. We do not catalog, upload, or modify your files.

2. Device Permissions Used :
To provide high-fidelity audio playback, our applications request the following system permissions:
READ_EXTERNAL_STORAGE / READ_MEDIA_AUDIO: Required to scan and play audio files stored locally on your physical device.
FOREGROUND_SERVICE: Required to ensure uninterrupted background audio processing when the application is minimized or your screen is deactivated.
READ_MEDIA_VIDEO: (For Android 13+) Required to scan and index local video container formats.
SYSTEM_ALERT_WINDOW: (Optional) Required exclusively if you utilize the background pop-up or custom Picture-in-Picture window overlay feature to display floating video canvases on top of other running applications.

3. Google Cast / Chromecast Integration & Local Network Operations:
Our applications (including Canary Player and Fire Video Player) provide features that allow you to cast your local audio and video files directly to Google Cast-enabled devices (such as a TV, Android TV, or smart speaker) on your local network.
How it Works: Chromecast hardware cannot directly stream or read files saved natively on your mobile phone's private storage (such as content:// or file: URIs). To bridge this gap, when you explicitly tap the Cast icon and connect to a device, the application temporarily launches a highly secure, lightweight, internal HTTP server locally on your phone. This server temporarily maps your selected music tracks to private, local network URLs.
Network & Background Permissions: To keep playback active when your screen turns off, the application uses local Wi-Fi connectivity and updates its background service to seamlessly hand off playback control to the Google Cast player. 
Data Sovereignty: This streaming pipeline occurs 100% on your device and inside your private home Wi-Fi network. No media files, tracking analytics, or telemetry data are ever uploaded, sent to, or processed on an external cloud server. 
Metadata Sync: Basic media metadata (such as Track Title and Artist Name) is transmitted locally to your TV screen strictly to render the standard "Now Playing" user interface.

4. Monetization & Advertising Framework :
Our ecosystem features two distinct app distributions. Data handling varies depending on the specific version you install:
Premium/Paid Applications (Pure Audio Music Player): Contain zero advertisements and utilize no third-party tracking layers. Your usage habits remain entirely private and offline.
Free Applications (Canary Player: Music Player and Fire Video Player) (Ad-Supported): To keep these tools free to download, this version may display third-party advertisements. These ad providers (such as Google AdMob) may access device identifiers (like the Android Advertising ID) to serve non-personalized or personalized ads and monitor ad performance. No financial transaction details or user tracking profiles are stored or accessed by Robin Sound Labs.
Local Typography: To display interface typography, font assets are bundled locally within the application package and are rendered completely offline. No network requests are made to external engines for asset delivery.

5. Children’s Privacy :
Our applications do not collect or harvest any data from anyone, including children under the age of 13. While our free version serves ads compliant with Google Play’s Families Policy, our tools remain entirely safe for family use.

6. Contact Us :
If you have any questions or feedback regarding this privacy infrastructure, please reach out to us via our corporate developer support channel at: pagilla18@gmail.com.


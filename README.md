# pwa-offline-cache 
- Web page should be load in case of offline
- PWA is a highly responsive website which open in browser as web page and in mobile view it feel like native mobile app. It can be adapt every device side like mobile, tablet, or laptop or desktop big screen size.
- Whatever feature website will have same can be access in PWA.
- We can achieve we site offline accessibility using Services workers & Caching.
- We can intall it on home screen and it will open in full screen width which feels like native mobile app but it still uses browser to open because altimately it is a responsive website.
- Resources
  - https://www.youtube.com/watch?v=bRoRikxgIew&list=PL8p2I9GklV46NFHdQMFBjXvxwVqtJpa2N  

- When to use PWA and when to use mobile native app
  - Native app use when we need more controll on hardware side like - Access Camera, Push notification, Contact list, etc.
  - Access to Native APIs: Native apps have access to device-specific APIs and hardware features, such as the camera, accelerometer, fingerprint scanner, and Bluetooth. While PWAs can leverage some of these features through browser APIs (e.g., Geolocation API, MediaDevices API), they may not have access to all native APIs, limiting the functionality of certain features.

  - Advanced Graphics and Animations: Native apps can provide smoother animations and more complex graphics compared to PWAs, especially for high-performance applications such as games or multimedia-rich experiences. While modern web technologies like WebGL and CSS animations can achieve impressive visuals in PWAs, they may not match the performance and fidelity of native apps.

  - Background Processes and Services: Native apps can run background processes and services continuously, allowing them to perform tasks such as syncing data, processing notifications, or tracking location updates even when the app is not actively in use. While PWAs can use service workers to perform background tasks and handle push notifications, they have limitations on background execution time and may not have the same level of control as native apps.

  - Access to Platform-Specific Features: Native apps can provide platform-specific features and integrations, such as widgets, app extensions, Siri shortcuts (on iOS), and home screen shortcuts (on Android). These features enhance the user experience and interoperability with other apps on the device, which may not be achievable with PWAs alone.

  - Offline Functionality: While PWAs can provide basic offline functionality using service workers and caching, they may not offer the same level of offline capabilities as native apps. Native apps can store larger amounts of data locally, support offline transactions, and offer more seamless offline experiences, making them better suited for use cases where offline functionality is critical.

  - Distribution and App Stores: Native apps are distributed through app stores (e.g., Apple App Store, Google Play Store), which provide visibility, credibility, and discoverability to users. PWAs, on the other hand, rely on web-based distribution channels, which may not offer the same level of exposure or promotional opportunities as app stores.

  - While PWAs offer many advantages, especially in terms of cross-platform compatibility, ease of deployment, and lower development costs, they may not be suitable for all use cases, particularly those requiring advanced native capabilities or platform-specific features. It's essential to evaluate your specific requirements and user needs when choosing between a PWA and a native app. In some cases, a hybrid approach combining both PWA and native app components may offer the best solution.
 
## Choose which one
- Depends on who are the potential customers?
- What features do they need?
- What devices do they use?
- Do they always have internet access?
- What budget and deadline company have?
  - PWA don't need seprate development and support team
  - Native app need development team and after deploy support team
  - PWA ASAP but native takes more time
  - PWA less cost effective and native app are more costly
- Depends on business
  - Food catering (PWA)
  - Beauty (PWA)
  - Hospitality (PWA)
  - Entertainment (PWA)
  - Fintech (Native app)
  - Healthcare (Native app)
  - Social media (Native app)
- Sometimes hybrid approch could be best, depends on requirements.
  - Flipkart

# NetworkExplorer
Repository for my app's privacy policy and components as I open-source them

Privacy Policy for Network Explorer
Last Updated: October 7, 2025

Thank you for using Network Explorer. This privacy policy explains what information the app uses and how it is handled. Our core principle is simple: your data is your own. This app is designed to function entirely on your device and local network without collecting or transmitting your personal information.

1. No Data Collection
Network Explorer does not collect, store, or transmit any personally identifiable information (PII). All operations and data analysis occur locally on your device. We do not have servers, and we do not want your data.

2. Information the App Uses
To perform its functions as a network utility, the app requires access to information about your device's network state. This includes:

Local Network Information: The app scans your local Wi-Fi network to discover and display information about other connected devices (like their local IP address, MAC address, and open ports). This information stays on your device and is never transmitted to us or any third party.
Bluetooth Device Information: The app scans for nearby Bluetooth and Bluetooth Low Energy (BLE) devices to display their names, signal strength, and other broadcasted characteristics. This scanning occurs only on your device.
3. Required Permissions
Network Explorer requests certain permissions to function correctly. Here is why each permission is needed:

INTERNET: Required to perform network scanning tasks, such as checking for open ports on local devices. No data is sent to the internet.
ACCESS_NETWORK_STATE: Allows the app to check if your device is connected to a network before attempting a scan.
ACCESS_WIFI_STATE: Allows the app to view information about the current Wi-Fi network, such as your local IP address and the names of nearby networks.
NEARBY_WIFI_DEVICES (Android 13+): Required to scan for nearby Wi-Fi devices without needing location permission.
BLUETOOTH, BLUETOOTH_ADMIN, BLUETOOTH_SCAN: Required to discover and display information about nearby Bluetooth devices.
ACCESS_COARSE_LOCATION / ACCESS_FINE_LOCATION: On older Android versions, location permission is required by the operating system to get results from Wi-Fi and Bluetooth scans. The app does not use, read, or store your physical location.
4. Third-Party Services
This app does not integrate with any third-party advertising or data collection services. This app does use Google Firebase to track crashes and for anonymous usage analytics.

5. Changes to This Privacy Policy
We may update this privacy policy from time to time. We will notify you of any changes by posting the new privacy policy within the app. You are advised to review this page periodically for any changes.

6. Contact Us
If you have any questions about this Privacy Policy, you can contact us through the app's listing page on the Google Play Store.

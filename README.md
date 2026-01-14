# Sending-app-too-expo-go-phone-


What makes your app appear on Expo Go?

Your phone does NOT open folders.
Expo Go only shows whatever project is currently running on your PC.

So:
👉 Whatever project you start with npx expo start is what appears on your phone.

🧩 Step 1: Go to your RootedInHer folder on your PC

Open PowerShell and type:

cd "C:\Users\27711\Desktop\Demo\RootedInHer"


Press Enter.

Now check:

dir


You should see:

App.js
package.json


✅ This confirms you are inside RootedInHer.

▶️ Step 2: Start Expo for THIS project

In the same PowerShell window, type:

npx expo start --clear


Wait a few seconds…

You will see a QR code appear in the terminal or browser.

👉 This QR code = your RootedInHer app

📱 Step 3: Open it on your phone (Expo Go)

Open Expo Go on your phone

Make sure:

Your phone and PC are on the same Wi-Fi

Tap Scan QR Code

Scan the QR code shown on your PC

⏳ After a few seconds, your app loads

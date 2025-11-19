# **SEAS \- Smart Emergency Alert System 🚨**

**Live Demo:** [Click here to view the App](https://www.google.com/search?q=https://sefat357.github.io/emergency-alert-system/)

## **📖 Project Overview**

The **Smart Emergency Alert System (SEAS)** is a cloud-enabled web application designed to provide immediate assistance in emergency situations. With a single click, users can broadcast their **live GPS location** and **medical profile** to their emergency contacts via automated emails.

This project demonstrates the integration of modern web technologies, real-time geolocation APIs, and third-party communication services to solve real-world safety problems.

## **✨ Key Features**

* **📍 Real-Time Geolocation:** Instantly captures high-accuracy GPS coordinates (Latitude/Longitude).  
* **📧 Automatic Email Alerts:** Uses EmailJS to send formatted emergency emails containing a Google Maps link and the user's medical data.  
* **💾 Local Data Persistence:** Uses the browser's Local Storage to save user profiles and contacts, ensuring data is available even after closing the browser.  
* **📱 Fully Responsive Design:** Optimized for mobile devices, ensuring usability during high-stress situations.  
* **🛡️ Error Handling:** Includes intelligent fallbacks (Simulated Location) if GPS is blocked or unavailable, ensuring the alert can still be triggered.

## **🛠️ Technologies Used**

* **Frontend:** HTML5, JavaScript (ES6+)  
* **Styling:** Tailwind CSS (via CDN)  
* **Icons:** Lucide Icons  
* **API Services:**  
  * **Geolocation API:** For capturing user position.  
  * **EmailJS:** For serverless email automation.  
* **Hosting:** GitHub Pages

## **🚀 How to Use**

1. **Open the App:** Visit the [Live Link](https://www.google.com/search?q=https://sefat357.github.io/emergency-alert-system/).  
2. **Create Profile:** Enter your name, age, blood group, and any medical conditions. Click **Save Profile**.  
3. **Add Contacts:** Enter the name and email address of your emergency contact. Click **Add Contact**.  
4. **Trigger Alert:** In an emergency, click the large red **"SEND EMERGENCY ALERT"** button.  
5. **Confirmation:** The app will locate you and send emails automatically. A confirmation modal will appear with your detected location.

## **📸 Screenshots**

| Dashboard | Alert Triggered | Email Received |
| :---- | :---- | :---- |
| *(You can upload your screenshots to an 'images' folder and link them here)* | ... | ... |

## **🔮 Future Improvements**

* **SMS Integration:** Adding Twilio support to send text messages.  
* **Backend Database:** Migrating from Local Storage to Firebase for cross-device data syncing.  
* **Push Notifications:** Enabling alerts for nearby users.

## **👨‍💻 Developer**

* **Name:** Raisul Islam Sefat  
* **University Project**
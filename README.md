# Fetching-JSON-data-from-URL
*******************************************************************
<p> Developed by- Anish Puranik for Fetch Rewards </p>
<p> Developed in Java using Android Studio Jelly Fish ver- 2023.3.1.20 (x64) </p>
<p> Tested on- Google Pixel 5, Google Pixel 7a (VM) </p>
<p> App Support- Android 8.0 (Oreo [API26]) and above with target version, Android 14 (Upside Down Cake [API34])</p>
<p> OS used- Windows 11 </p>
<p> Processor- AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx 2.10 GHz </p>
*******************************************************************

README

This repository includes an android application along with its apk file. 
FUNCTIONALITY - Fetches JSON data from a URL and displays the list which is sorted as-
- Items grouped by "listId"
- Sorted the results first by "listID" then by "name" where items containing "name" as null or blank have been filtered out

INSTALLATION- The repository comes with an apk file which can directly be installed on any Android phone. 
If the installation is to be done from Android Studio-

- Make sure that you run Android Studio Jelly Fish.
- Clone the repository
- Open the project in Android Studio
- Connect a physical device or install a virtual device on Android Studio itself
- Any version above Android 8.0 should be able to host this app
- Run the app on the device for testing

ASSUMPTIONS- I got the data from https://fetch-hiring.s3.amazonaws.com/hiring.json and included it inside a JSON array called "data" and generated a new link https://api.npoint.io/8467b69defd76d56c512
The application fetches data from the above link and displays the result on the phone

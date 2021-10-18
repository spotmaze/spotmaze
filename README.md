# Welcome to the Spotmaze Repository
Spotmaze is a virtual world creation platform that enables you to build and customize your own personalized virtual worlds.

## How it works?
You first create a grid of connected locations and pathways. These are meant to represent any topics that are closely related. Each location can be then be linked to a forum, where you can receive responses from your community. You can then share this world using a simple URL.

## Launch your world
- To launch your world, fork this repository and the "[spotmaze.json](https://github.com/spotmaze/spotmaze/blob/main/spotmaze.json)" file into your own repository. 
- You repo name must be "[spotmaze](https://github.com/spotmaze/spotmaze)". 
- To see the world, go to your custom URL [https://spotmaze.world/spotmaze](https://spotmaze.world/spotmaze)
- To refresh your world, you can rename your file to "[room1.json](https://github.com/spotmaze/spotmaze/blob/main/room-1.json)"  
- Use your URL with a queery parameter(?) 
- For eg [https://spotmaze.world/spotmaze?room1](https://spotmaze.world/spotmaze?room1). 

## Customize your world
- You can customize your world by editing the appropriate fields in your [spotmaze.json](https://github.com/spotmaze/spotmaze/blob/main/spotmaze.json) file. 
- To add images into your world, you can drag and drop your Image folder into the repository, 
- Then add "[Images/my-img.png](https://github.com/spotmaze/spotmaze/tree/main/Images)" into the locations the image field. 

## Customize your world (using an Excel Spreadsheet)
- You also customize your world using Excel spreadsheet. 
- After editing, upload your custom [Excel file](https://raw.githubusercontent.com/spotmaze/spotmaze/main/spotmaze.xlsx) to this [Excell converter](https://beautifytools.com/excel-to-json-converter.php) to convert your XLSX to JSON. 
- This website (https://beautifytools.com/excel-to-json-converter.php) will build you a valid JSON that you can use as your source file.
- Copy & paste this output into your existing JSON source file to compleate the process 
- Or else replace the current file with the newly created one from the website.
- Your XLSX format should match the standard format as shown here in this [repository file](https://raw.githubusercontent.com/spotmaze/spotmaze/main/spotmaze.xlsx).

## Validate your world
To Validate your JSON source file, you can use any JSON Validator. For eg
- https://jsoneditoronline.org/beta/#right=local.qujuzu&left=local.wuxedu (Highly Recommended)
- https://jsononline.net/json-checker
- https://jsonformatter.org/

## Debug your world
For an __in-game debugging__ experience
- Turn `grid on` in the developer section 
- Press `backspace` to toggle the debug console.

## Rooms with Bugs
Three error rooms are provided for you, where you can test some commom mistakes while writing the source file.
- [error1.json](https://github.com/spotmaze/spotmaze/blob/main/error1.json) Spot duplicate name    :   https://spotmaze.world/spotmaze?error1
- [error2.json](https://github.com/spotmaze/spotmaze/blob/main/error2.json) Spot name not found   :   https://spotmaze.world/spotmaze?error2
- [error3.json](https://github.com/spotmaze/spotmaze/blob/main/error3.json) Image not found       :   https://spotmaze.world/spotmaze?error3

## Links with Bugs
If an incorrect link is entered, the application will throw up a user not found error.
- User not found error        :   https://spotmaze.world/spotmaze_other
- Room not found error       :   https://spotmaze.world/spotmaze_other?lounge

<!--
**spotmaze/spotmaze** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Welcome to the Spotmaze Repository
Spotmaze is a virtual world creation platform that enables you to build and customize your own personalized virtual worlds.

## How it works?
You first create a grid of connected locations and pathways. These are meant to represent any topics that are closely related. Each location can be then be linked to a forum, where you can receive responses from your community. You can then share this world using a simple URL.

## Launch your world
- To launch your world, copy/fork this "[spotmaze.json](https://github.com/spotmaze/spotmaze/blob/main/spotmaze.json)" file into your own repository re-named "[spotmaze](https://github.com/spotmaze/spotmaze)". 
- To see the world, go to your URL [https://spotmaze.world/\_\_USERNAME\_\_](https://spotmaze.world/spotmaze)
- To refresh your world, you can rename your file to "[room1.json](https://github.com/spotmaze/spotmaze/blob/main/room-1.json)"  
- Use your URL with a queery parameter(?) 
- For eg [https://spotmaze.world/\_\_USERNAME\_\_?room1](https://spotmaze.world/spotmaze?room1). 
- To embed images into your world, you can drag and drop your Image folder into the repository, and add "[Images/my-img.png](https://github.com/spotmaze/spotmaze/tree/main/Images)" into the image field. 
- You can further customize your world by editing the appropriate fields in your [spotmaze.json](https://github.com/spotmaze/spotmaze/blob/main/spotmaze.json) file. 

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
Two error rooms are provided for you, where you can test some commom mistakes while writing the source file.
- Spot duplicate name error : https://spotmaze.world/spotmaze?error1
- Spot name not found error : https://spotmaze.world/spotmaze?error2

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

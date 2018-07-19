# Google AIY mirror project

## Introduction
Hello there, if you like what I did, go subscribe to my [Youtube channel](https://www.youtube.com/channel/UCSt9bIi3GKhuTw7n1WaYz8Q)
### Steps to setup software a summary
_**Note**: The full in depth explanation is in my Youtube channel_ 

1. Use Etcher.io to create an image of the software on a micro sd card, btw software linked above.
2. Once you have everything installed go to the google [Cloud services API dashboard](https://console.cloud.google.com/apis/dashboard) (make sure you sign into your google account and its for free).
3. Now create a new project name it click and go over to the credentials tab and click on the OAuth consent screen
fill out the email address and product name (btw name it what you named your project for simplicity).  
4. Now get your Raspberry PI and go to the Credentials tab and download the secret code by clicking the download button on the project you made .
5. Now rename the file you downloaded assistant.json drag it and put ith in the home/pi/ folder
6. Now your done just run src/examples/voice/assistant_library_demo.py

### Troubleshooting issues I faced
If you are using the 2017 model of the AIY Voice HAT, the software will not detect the microphone and speaker. There are many work around but an easy one is to use version(yyyy) of software which is linked in software setup (step 1.). You can find more details about this in issue # 225 


g installed go to the google (cloud services link:
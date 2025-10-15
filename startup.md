### [Go Back Home](/README.md)
### [Troubleshooting Help](/TS/README.md)
# Running OBS and Streaming a Game

1. Sign into the LEFT Esports Shoutcasting Computer. This will be the computer we run the stream off of. In the past, we used to use both computers, but this is harder in some cases dealing with audio and microphones for Commentators.
2. Launch OBS on the computer. You can find it on the desktop or in the search bar.
3. Once OBS is launched, verify you are on the right Scene Collection for the game being streamed. You can check that information on the title bar of OBS.\
![](/Assets/currentsc.png)
    - If you are not on the correct Scene Collection, click the [Scene Collection button](/Assets/scenecollection.png) and [select the game](/Assets/scwithscenes.png) that is going to be streamed.
4. Select the "Starting" Scene and verify you are on the "Esports" profile. (When changing profiles, you may have an error that you have been signed out of the Twitch. If this happens, sign back in.)
5. Launch the game that we will be playing on the same computer that OBS is running on.
6. Head to the **In Play NoCam** scene and verify that gameplay is showing.
7. Verify that the commentary microphone is being picked up by OBS, as well as game audio.
    - If Microphone audio is not picking up, make sure the microphone is unmuted. It will have a SOLID red light when unmuted and a blinking red light when muted. If it is still not being picked up, head to the Audio tab in OBS Settings and verify the "Yeti" Microphone is selected.
    - If game audio is not being picked up, in the audio tab in settings, verify the Desktop Audio is working correctly.
8. Finally before we start the stream, head to OBS Settings > Advanced and verify that **Stream Delay** is Enabled and set to 180s.
![](/Assets/delay.png)
> [!WARNING]
> The last step is VERY IMPORTANT and not setting this will cause us to get in trouble with ECAC. Take time to check before every stream that it is set to 180s on ALL games.
9. Change the Stream name to the team name and who we are facing. Then change the category to the game we are playing. 
> [!NOTE]
> If you change the title mid stream, we will need to rename the VOD before sending it to YouTube.\
10. Hit the **Start Streaming** button. Once that happens, the delay is activly building and the stream is live.
> [!NOTE]
> Even through it will take 180 seconds to stream information to Twitch, keep in mind that during those 180 seconds, YOU ARE LIVE. It wont appear on twitch at that second, but it WILL in 180 seconds.
11. If there is no commentator and you do not wish to speak to stream, verify the Microphone is muted. Keep the language in the Shoutcasting booth clean as a precaution while the stream is live to prevent issues if we have an accidental hot mic.
12. When in game, change the the In Play NoCam scene and utilize the other scenes such as Be Right Back, Starting, and Ending to help show that the Stream is still live. (This helps to show that the stream is live by using a moving background.)
13. When finished, switch to Ending and hit the "Stop Streaming" button. There will be two options. Always hit "Stop Streaming", **NEVER DISCARD DELAY**! (If the delay is discarded, it will stop the stream on Twitch immediately losing the last 180 seconds on the stream. Only do Discard Delay in cases where you have to be out of the booth immediately.)
14. Wait for the Stream Delay to finish sending to Twitch, you can keep track of that at the bottom right corner.
15. Once the stream is finished, head to Twitch and go to the "Creator Dashboard". Head to the "Video Producer" tab. If you change the stream title before starting the stream, you will see that title on the VOD. If you need to change it, do it now by clicking the Modify button in the 3 dots menu on the VOD.
16. Now that we have verified the title, click the 3 dots menu and click **Export**. A menu will pop up with a Title, Description and visibility. It will automatically grab everything from the VOD, but verify the visibility is Public (Unless something occured during stream we dont want people to see, then change to Unlisted). 
17. After that hit the "Start Export" button and it will send the VOD to YouTube.
We can then close the dashboard, OBS, and the game and shut down the computer.

### Thats it! :tada:
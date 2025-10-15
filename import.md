### [Go Back Home](/README.md)
# Importing Scene Collections
Now that OBS is set up, lets add our scene collections.

1. Head to the [CCSUEsports OBS Github Repo](https://github.com/CCSUEsports/OBS)\
![](/Assets/github_page.png)

2. Select the **Code** button.\
![](/Assets/codebutton.png)

3. Select the **Download ZIP** button.\
![](/Assets/download_zip.png)

4. Head to File Explorer and extract the ZIP file.\
![](/Assets/fileexplorer.png)

5. Head back to OBS Studio and select the **Scene Collection** dropdown.\
![](/Assets/scenecollection.png)

6. Select the **Import** button\
![](/Assets/importsc.png)

7. In the Import window, select either the "..." or the Browse button.\
![](/Assets/scbrowse.png)

8. Navigate to the OBS-main folder that was extracted earlier and enter the **Scene Collection** folder.\
![](/Assets/scbrowse2.png)

9. Select the games that you are going to stream.[^1]\
![](/Assets/scbrowse3.png)

10. Once all the required scene collections are selected, press the **Import** button.\
![](/Assets/importsc2.png)

11. Select the **Scene Collection** dropdown again.\
![](/Assets/scenecollection.png)

12. You should see a bunch of the scene collections that were imported. Select one of them to change to that Scene Collection.\
![](/Assets/scwithscenes.png)

13. If this window pops up, select the **Search Directory** button.\
![](/Assets/missingfiles.png)

14. Navigate to the OBS-main folder that was extracted and enter the Assets Folder.
    1. Verify you are in the OBS-main/Assets folder.
    2. Do **NOT** select any of the folders in that folder. 
    3. Press the "Select Folder" button\
![](/Assets/missingfiles2.png)

15. All of the missing files should change to "Found". If they don't, navigate the folder in File Explorer and attempt to find them manually.\
![](/Assets/missingfiles3.png)

16. Our Scene Collection has sucessfully imported! :tada:....... wait... we are missing a Microphone....\
![](/Assets/scimportcomp.png)\
There is a bug when importing that causes the microphone to not appear. Lets fix the microphone.

17. Head over to the settings button.\
![](/Assets/settings.png)

18. Select the Audio Tab.\
![](/Assets/audiotab.png)

19. In the photo below, disable the microphone and re-enable it. When reenabling, select the actual microphone we will be using INSTEAD of "Default".\
![](/Assets/audiofix.png)

20. Once fixed, the mic will appear in the Audio Mixer.

### And thats how we import Scene Collections!
Now that we are finished with that, lets [tailor the OBS Profile](profile.md).

---
[^1]: The folder shown in the example does not represent active teams. If a team is missing, import an existing scene collection and modify it at the end by following [this guide](/TS/newsc.md).
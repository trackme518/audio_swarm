# Audio Swarm
Swarm simulation for spatial audio diffusion

## For Windows
Download the zip folder, unzip, double click .exe file (no need to install).

## For MacOS
When you download usigned app from the internet (with a browser) it may apply [quarantine attribute](https://derflounder.wordpress.com/2012/11/20/clearing-the-quarantine-extended-attribute-from-downloaded-applications/) on it and give you an error. You can check the attributes assigned to the file with `xattr /path/to/MyApp.app`. You also need to allow running App from unverfied sources in Settings. Detailed instructions below: 
* Right-click on the downloaded .zip folder, `open with...archive utility` (it will unzip)
* Righ-click on the unzipped folder, select `New Terminal at Folder`
* paste this command: `sudo xattr -r -d com.apple.quarantine audioAnimator_v4.app`(replace audioAnimator_v4.app with the name of the downloaded app)
* input your password
* now you can double click the app and it should run - you might also need to allow it in `Security settings`
  * Go to settings - `Privacy & Security` scroll down
  * Click allow anyway
  * double click the app icon to run it

## License
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). When using or distributing the code, give a credit in the form of "OSCreplay software (https://github.com/trackme518/audio_swarm) by Vojtech Leischner (https://trackmeifyoucan.com)". Please refer to the [license](./LICENSE.markdown) or see online [reference](https://creativecommons.org/licenses/by-nc-sa/4.0/). Author is not liable for any damage caused by the software. Usage of the software is completely at your own risk. For commercial licensing please [contact](https://tricktheear.eu/contact/) us.

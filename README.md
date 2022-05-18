# Tracker_Insect_flight

### Contents
- Steps, links, and explanations on how to use *Tracker Video Analysis and Modeling Tool* for tracking Insect head en body angle during free fall. 
- Tracker file exemple and file depending of the exporting methods (Tab, comma ...) 

### Install tracker 
Link to install but also to have a lot of information on how to use Tracker: https://physlets.org/tracker/

### Tips:  
- You will need a .avi file of the movie you want to track. 
- You will also probably need to change the RAM: See on this [screenshot](https://user-images.githubusercontent.com/100707728/169100735-462cebfa-db02-47a4-9fae-41bbd9e515e9.png) were to change it. >Set memory size...> increase it according to your use and the performance of your computer. The default value is 1024 MB. 
- For basic info (open .avi, create Tracks ...) see Tracker website https://physlets.org/tracker/ and youtube video https://www.youtube.com/watch?v=La3H7JywgX0.

### Steps:  
- Open or import avi. file
- Set start (1.) and end (2.) frame ([screenshot](https://user-images.githubusercontent.com/100707728/169105496-8b1fe8ae-9dc8-4305-88c4-afd249fb9ec1.png))
- Show and verify the coordinate axes ([screenshot](https://user-images.githubusercontent.com/100707728/169105746-bfc0a62d-7a81-4d13-b124-a2c39b4c29ef.png))
- Create a calibration stick if needed ([screenshot](https://user-images.githubusercontent.com/100707728/169106728-866d10a9-65d1-476d-a06e-0f8b2cd2dadf.png)) 
- Create a track: Track>New>Point Mass ([screenshot](https://user-images.githubusercontent.com/100707728/169107029-41157a77-7c7e-410a-a5a6-9dcedf15b8c4.png)). It's helpful to rename and change the color of the track for multiple tracking ([screenshot](https://user-images.githubusercontent.com/100707728/169107333-5f93ed85-baab-463d-abc7-9d19bc583648.png))
- Tracking: To track image by image (Shift + click on the image) or use autotracker (Shift+ Ctrl + click on the image > select the area of interest > Search ([image](https://user-images.githubusercontent.com/100707728/169108143-17f37d08-02fc-45f6-84c4-015dae0ebebb.png))
))
- Check the tracking (especially if you are using Autotracker) and adapt manually the wrong tracking value
- Export values ([image](https://user-images.githubusercontent.com/100707728/169108871-05e05807-4621-4741-98b3-77cd684b132b.png)). Choose the tracks (you can choose to export multiple tracks in the last version of Tracker). Choose frame in column selection. Choose Tab as Delimiter. Save as .txt file. 
- Open the .txt file in Excel or Matlab 

### Notes
- Tracker version: 6.0.8 
- Scientific paper link to this memo: Anna Verbe, Léandre P. Varennes, Jean-Louis Vercher, Stéphane Viollet; How do hoverflies use their righting reflex?. *J Exp Biol* 1 July 2020; 223 (13): jeb215327. doi: https://doi.org/10.1242/jeb.215327

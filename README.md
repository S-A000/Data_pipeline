What does this project do?
Think of InstaPipeline as an automated data-entry and file-management assistant. Its main job is to look at your Instagram video files, figure out what they are named, tag them with an "AI Label" (a category), and save all that information into a neat list (a CSV file). Once a video is logged, it moves the video out of the way into an archive folder so your main workspace stays clean.

How it works (Step-by-Step Flow)
Finds the Videos: The system goes into your main folder (like Raw_reel) and looks for any .mp4 video files.

Extracts Information: It looks at the file and isolates just the actual video name (like promo_001.mp4). It also attaches an "AI Label" to it, which helps categorize what the video is about.

Logs the Data: It takes that Video Name and the AI Label and writes them side-by-side into a list, which is saved as a video_log.csv file (just like a simple Excel sheet).

Cleans Up (Archiving): As soon as the video's information is safely written in the list, the system moves the actual video file into an "Archive" folder. This prevents the folder from getting cluttered and ensures the same video isn't accidentally processed twice.

![Alt text](path/to/image.png)

## TwinGalaxies_Thread_Analysis
Jupyter notebook with analysis done on dataset based on the Billy Mitchell Donkey Kong dispute thread: https://www.twingalaxies.com/showthread.php/176004-Dispute-Jeremy-Young-Arcade-Donkey-Kong-Points-Hammer-Allowed-Player-Billy-L-Mitchell-Score-1-062-800/

### Background: 
- Well known documentary: https://en.wikipedia.org/wiki/The_King_of_Kong
- Thread arguments in video form: https://www.youtube.com/watch?v=SEKYlZbaQPE
- Popular, though a bit inaccurate description of the situation: https://www.youtube.com/watch?v=234Y76_3YPE

This was made just for fun as a side project.

### What it contains:
- Script to create XLS/CSV data file based on thread
- Script to analyse XLS data file created in previous step
  - Calculates summary stats
  - Adds importance ratings based on network centrality. This permits filtering for most important amid 3251 posts.
  - Calculate most important posters / influencers
  - Rate and order links / attachments according to community appreciation

### To Do: 
- Network statistics (poster score, post score, ...) are not well developped and should be re-evaluated with a theoretical analysis. 
- Comments and proper refactoring is missing

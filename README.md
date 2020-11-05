# best-metronome-app
The Best Metronome App

### Functionality Ideas
- Basic beat playing
- Allow selection from multiple beat sounds
- Allow creating your own beat sounds
- Complex beat pattern playing, setting up various beat subdivions. 
    This would require substantial UI/UX work.
- Fast switching to different tempo - there could be some way where you need a song to switch tempo in the middle, it could provide that capability.
- Widget with simplified metronome
- Metronome controls via notification
- Multiple ways to help determine the BPM 
  - Manual BPM input
  - BPM recognition by tapping
  - Automatic BPM recognition by an .mp3 
  - Song search functionality that suggests BPM
        Could for example use https://getsongbpm.com/search.
  - BPM recognition from sounds in the room, for exapling when playing by yourself.
  - BPM recognition from sounds coming from the itself.
      For example, if you have YouTube playing, the app could try to determine the BPM for that.
- Naming and storing of BPMs and their beat patterns.
- Display a list of all the BPMs that you stored.
- Creating sub-sets of BPMs that you created. 
    This would be useful for live performances, where you could take some songs and put them in a list, in the order that you will play them.  
- Favoriting BPMs. 
- Search functionality for your created BPMs (sorting by creation date, by usage).
- Recording and storing a short preview for a specific BPM.
    This is useful because when you are creating songs, you often forget the name that you gave to them. So a short preview is nice to have.
- Full user creation, authentication and login flow. The person could still use the app without logging in, but if he logged in then there would be additional features that he could use:
  - Sharing their BPMs, with recording previews.
  - Searhing importing BPM list of someone else. 
  - Playing the same BPM in synchronization with connected, so that multiple people could hear the same BPM at the same time.
      Would be interesting how to implement this exact synchronization, and how to connect the apps. Bluetooth? Nfc? Wifi?
      Note: Perhaps this does not require authentication? 
  - TODO add more authenticated functionalities. 

### Analysis of Competing Apps
#### The Metronome by Soundbrenner
 - Small tempo adjustment could be better. Those arrows are really small, not convenient for small adjustments. Reconsider UX.
 - Notification could provide more.
 - Ads in home page
 
### Notes
- Consider doing it with Flutter? Pros/cons?
- Libraries that help detect BPM from audio:
  - https://github.com/chrvadala/music-beat-detector
  - https://github.com/cjcliffe/beatdetektor
  - https://jmperezperez.com/bpm-detection-javascript/
  - https://mziccard.me/2015/05/28/beats-detection-algorithms-1/
  - https://stackoverflow.com/questions/657073/how-to-detect-the-bpm-of-a-song-in-php
  - https://stackoverflow.com/questions/2781897/programmatically-get-bpm-of-a-wave-or-mp3-from-net
- Look at forums, ask friends, what more features would they need.
- App should have clean UI/UX
- Do more analysis of competing apps
- Could do a cool demonstration for the app

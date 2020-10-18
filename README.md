# iptv-free-tv
FREE TV CHANNELS  
playlist.m3u will be updated ~~weekly~~ daily through automated api     
## About
**AUTOMATE API USING SELENIUM WEBDRIVER IN JAVA (iptv.jar).** *RUN.BAT creates a file playlist.m3u which contains video players for LIVE TV Channels.   
**Playlist.m3u** can be opened on desktops, mobile, or smart TV (using any iptv player for TV ).*  
Playlist.m3u:  
![Alt text](https://i.imgur.com/dJGyPEV.jpg)
### How it works:
Running RUN.bat opens a cmd (for user input ). It asks if you want to upload playlist to TV ( type NO if you dont want to use TV, YES it will save playlist on local too),
then a connection code, in case you want to upload playlist to TV (NO means tv is already connected).  
![Alt text](https://i.imgur.com/huMuSU7.jpg "Optional")  
*The automate program then will open Google Chrome and scrape google for websites which have video players for every TV channel.  
*It will choose a videoplayer for every channel based on HD quality and save it in a in-memory database.  
*Based on the created database it will create the playlist.m3u which will contain every single TV channel.  
*The process is fully automated and it only requires user input.  
*You'll need a player to open Playlist.m3u ( for example: BSPlayer, VLC, PotPlayer )  
*If catches an exception it will output in cmd and exit webdriver.  
*Successful automated process: 

![Alt text](https://i.imgur.com/3RBVhsN.jpg) 

## DEMO:   
### ~~V.1.2~~  - deprecated
![Alt text](https://media.giphy.com/media/S4Hl2Ljqig17XqbM5y/giphy.gif)   

### V.1.3 - latest
![Alt text](https://media.giphy.com/media/H7f4HiTzSUMrpQ78CU/giphy.gif)  
Currently supporting 50+ channels. Will add more:  

#EXTINF:-1,RO: PRO CINEMA  
#EXTINF:-1,RO: HBO  
#EXTINF:-1,RO: HBO 2  
#EXTINF:-1,RO: HBO 3  
#EXTINF:-1,RO: CINEMAX  
#EXTINF:-1,RO: CINEMAX 2  
#EXTINF:-1,RO: FILMNOW  
#EXTINF:-1,RO: AMC  
#EXTINF:-1,RO: AXN  
#EXTINF:-1,RO: AXN BLACK  
#EXTINF:-1,RO: AXN WHITE  
#EXTINF:-1,RO: AXN SPIN  
#EXTINF:-1,RO: FILMBOX  
#EXTINF:-1,RO: FILMBOX PREMIUM  
#EXTINF:-1,RO: U TV  
#EXTINF:-1,RO: ZU TV  
#EXTINF:-1,RO: KISS TV  
#EXTINF:-1,RO: MOOZ HITS  
#EXTINF:-1,RO: 1 MUSIC CHANNEL  
#EXTINF:-1,RO: MTV EUROPE  
#EXTINF:-1,RO: MTV HITS  
#EXTINF:-1,RO: CLUB MTV  
#EXTINF:-1,RO: MTV LIVE HD  
#EXTINF:-1,RO: MTV MUSIC 24  
#EXTINF:-1,RO: BRIDGE TV DELUXE  
#EXTINF:-1,RO: BRIDGE TV HITS  
#EXTINF:-1,RO: MANELE TV    
#EXTINF:-1,RO: MINIMAX  
#EXTINF:-1,RO: BOOMERANG  
#EXTINF:-1,RO: Nickelodeon  
#EXTINF:-1,RO: DISNEY JUNIOR  
#EXTINF:-1,RO: DISNEY CHANNEL  
#EXTINF:-1,RO: CARTOON NETWORK  
#EXTINF:-1,RO: MR.BEAN 24/7 **new**  
#EXTINF:-1,RO: ~~NIMO TV~~ **removed**  
#EXTINF:-1,RO: JOHNNY BRAVO 24/7  
#EXTINF:-1,RO: TOM & JERRY  
#EXTINF:-1,RO: DIGI LIFE  
#EXTINF:-1,RO: DIGI WORLD  
#EXTINF:-1,RO: DIGI ANIMAL WORLD  
#EXTINF:-1,RO: Crime + Investigation  **new**  
#EXTINF:-1,RO: HISTORY CHANNEL  
#EXTINF:-1,RO: HISTORY 2 **new**      
#EXTINF:-1,RO: DISCOVERY CHANNEL  
#EXTINF:-1,RO: DISCOVERY SCIENCE  
#EXTINF:-1,RO: DISCOVERY ID  
#EXTINF:-1,RO: NATIONAL GEOGRAPHIC  
#EXTINF:-1,RO: CBS REALITY  
#EXTINF:-1,RO: BBC EARTH  
#EXTINF:-1,RO: DIGI SPORT 1   
#EXTINF:-1,RO: DIGI SPORT 2   
#EXTINF:-1,RO: DIGI SPORT 3    
#EXTINF:-1,RO: DIGI SPORT 4   
#EXTINF:-1,RO: TELEKOM SPORT 1   
#EXTINF:-1,RO: TELEKOM SPORT 2   
#EXTINF:-1,RO: TELEKOM SPORT 3   
#EXTINF:-1,RO: TELEKOM SPORT 4 
#EXTINF:-1,RO: FIGHTBOX **new**  

-- Added on requests from users --  
#EXTINF:-1,RO: ANTENA 1  **new**   
#EXTINF:-1,RO: ANTENA STARS  **new**    
#EXTINF:-1,RO: PROTV     **new**   
#EXTINF:-1,RO: DIGI 4K   **new**   
#EXTINF:-1,RO: PRO 2     **new**   
#EXTINF:-1,RO: PRO X     **new** 
#EXTINF:-1,RO: PRO GOLD  **new**  
#EXTINF:-1,RO: KANAL D   **new**  
#EXTINF:-1,RO: PRIMA TV  **new**  
#EXTINF:-1,RO: RO TV     **new**
#EXTINF:-1,RO: TVR 1     **new**   
#EXTINF:-1,RO: TVR 2     **new**  
#EXTINF:-1,RO: TVR 3     **new**  
 
    

## Instructions for using PC ONLY ( not TV ) 
click RUN.bat  
"Do you want to upload playlist to tv? : YES / NO" Type NO and press enter. Wait.  
Playlist.m3u will be created in same directory.  
![Alt text](https://i.imgur.com/z29iG1T.jpg)  
If channels are not working and this appears, it means playlist.m3u is not updated. **Then run RUN.bat to update it**   
![Alt text](https://i.imgur.com/Kg9cGcP.jpg)
## Changelogs  
FreeTv V.1.1 - add sport channels  
FreeTv V.1.2 - fix java.ArrayIndexOutOfBounds Exception ( occurs sometimes on getting category )  
FreeTv V.1.2.1 - increase performance by adding headless mode, runtime down to 15 seconds from ~50  
FreeTv V.1.3  - change chromedriver path from relative to "user.dir". Added chromedriver to src  
FreeTv V.1.4 - fix selenium.common.exceptions.WebDriverException: Message: Element is not clickable at point (61, 24.300003051757812). Other element would receive the click: null ",  
             - Added acceptance for cookie policy  
FreeTv V.1.5 - **BIG UPDATE** Application used to work for certain Chrome Browser version (ex v85). Now it's compatible with **ALL** Chrome Browser Versions.  
FreeTv V.1.6 - Add Romanian Tv channels on demand from user side. See change list channels.  
FreeTv V.1.7 - New Channells, rewrite whole code - a lot of code refactoring to improve performance. This may be the final version bc don't have time anymore.  
	     - ** I DISABLED OLDER VERSIONS SO THEY NO LONGER WORK, DOWNLOAD LATEST 1.7**  
FreeTv V.1.8 - TO DO add feature -> update github repository automatically when RUN.bat is executed successfully. **DONE not made public**  

# Bringing My OCD Online: Userscripts for Enhanced Forum Browsing

 Hi, I'm Will. I'm 24 and I'm autistic. I'm learning to code and this is my first public project. For OCD people like me, the constant visibility of how much of a thread is left hinders our ability to immerse myself in the story and can stress us out. Therefore, I developed userscripts for the online forums I use that hide those indicators. 

When I know how close I am to the end of the story, I have difficulty getting immersed in the story because I keep thinking about how much content is left. Sometimes it's just a constant distraction. Other times I get stressed figuring out whether or not it's worth continuing the story if it's slow and near the end. Unfortunately, I find information about my closeness to the end all over the place. The story blurb and the word count are both right next to the total chapter count. The next page button is right next to the number of the last page. Below the last post of each page is a count of the remaining posts until the end. 

Before I learned to code, I'd use my hand to block the total chapter count so I could read the blurb and see the wordcount. I would do my best to ignore the page navigation bar except for the next page button, but I usually ended up failing. One of the reasons I always read in full-screen Safari is that I didn't have to see the tab name that always had the page number. I learned not to hover my cursor over the window because it would tell me the page number. 
Despite the fact I didn't know what a userscript was until I started coding them, AI assistance allowed me to code them with minimal help from my brother. Khanmigo helped me plan, write, and debug code. ChatGPT taught me the theory. Part of the reason I coded a lot faster with the later userscripts is I knew enough to realize when AI was talking about something irrelevant and redirect it. One cool moment was when I correctly predicted I didn't need to code different user scripts for SpaceBattles and Sufficent Velocity because Sufficent Velocity used to be part of SpaceBattles. 

I find it relaxing not to have to worry about accidentally seeing the chapter count or the final page number. 
		

# Removing Threadmark Count
 The userscript removes the last column of the first image. <br>
 <img src="https://github.com/wkrouse/Bringing-My-OCD-Online/blob/main/images/1st%20threadmark%20count%20removal.png?raw=true)" alt="Comparison of web forum interface with and without the first instances of threadmark count" width="700"><br>

The userscript changes the template Statistics (threadmark number threadmark, wordcount words) to Statistics (wordcount words).
 <img src="https://github.com/wkrouse/Bringing-My-OCD-Online/blob/main/images/2nd%20Threadmark%20count%20removal.png?raw=true" alt="Comparison of thread statistics display, with and without second instance of threadmark counts" width="500">

# Renames Final Page Button to 'Last' in Navigation Bars

 The userscript renames the button right before the next button to the word Last. It's  only effective when multiple navigation buttons are present. Note: This feature will take a moment to load. This feature works on Questionable Questing.<br>
 <img src="https://github.com/wkrouse/Bringing-My-OCD-Online/blob/main/images/Rename%20last%20page%20button.png?raw=true" alt="Screenshot showing the renaming of the forum navigation button to 'Last' by the userscript" width="300">

# Removes Remaining Reply Count at Bottom of Page
 The userscript removes the number of replies then the words more messages. This feature works on Questionable Questing.<br>
 <img src="https://github.com/wkrouse/Bringing-My-OCD-Online/blob/main/images/remaining%20reply%20count%20remover%20horizontal.png?raw=true" alt="Comparison of web forum interface with and without the number of replies then the words more messages" width="500">

# When looking at the threads created by an user, it removes the total reply count		
 The userscript removes the number of replies in the thread. <br>
 <img src="https://github.com/wkrouse/Bringing-My-OCD-Online/blob/main/images/total%20reply%20count%20remover.png?raw=true" alt="Comparison of web forum interface with and without the number of replies in the thread" width="500">

# How to install
Available on GreasyFork at https://greasyfork.org/en/scripts/484473-sufficient-velocity-userscipts, and https://greasyfork.org/en/scripts/484469-spacebattles-userscripts, and https://greasyfork.org/en/scripts/484474-questionable-questing-userscript.

They Works with UserScripts and probably more userscipt managers, but not tried.

UserScripts
1. Install and Usage Sections of https://github.com/quoid/userscripts
2. Select by the gear button +
3. Press New JS
4. Paste the raw contents of one of the .js file into the editor
5. Save.
6. Repeat 1-5 twice.

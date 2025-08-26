steps to clone this repo with obsidian:
I'm assuming you just have obsidian if you're doing this.

### Step 1: install git
If you think you already have git but are unsure, head to the step labeled  (here) below.

-go here: https://git-scm.com/downloads/win

-hit the "Click Here to Download" link up top

-follow instructions in installer

### Step 2: Clone the repo into a folder of your choice
work with me here.
-locate a place you want to store this repo. for example. the Documents folder. Create a new folder in there if you like.

-once you have your location, right click on the folder and click the "Open in Terminal" option.

-(here) if you only just installed git, run the following command to confirm it's installed:
	git --version
if this gives any errors, the installation hasn't gone right. otherwise it should output a version like this:
	git version 2.43.0.windows.1

-once good to go, enter this command:
	git clone https://github.com/joeysacct/Vecner-Notes.git
This should pull all the notes down. You can close the command line at this point; you're safe now.

### Step 3: Using it in Obsidian
-in Obsidian open the Vecner-Notes folder that you just grabbed as a vault.
-Click the cogwheel icon in the bottom left next to the vault name. 
-go to community plugins and turn them on.
-click "Browse" and search for (shocker) "Git"
-click "Install" and "Enable"
you should have things set up now.

### Basics of Usage
Using it at all:
	hit the "Git Source Control" icon on the left bar:
	![[Pasted image 20250826013630.png]]
Grabbing new changes from github:
	-click the "Pull" icon: ![[Pasted image 20250826013418.png]]
Adding your changes to the github:
	-In the text field below the set of buttons on the right git stuff, add a message describing what you've added or changed. ![[Pasted image 20250826014325.png]]
	-then, click the 'Commit-and-sync' button: ![[Pasted image 20250826013429.png]]
if Git starts whining and complaining when you try to pull:
	-hit the open command palette button on the left bar. should look like a >_
	-search for "Git: Raw Command"
	-select that, type in 'stash' and run that
	-click the "Pull" icon: ![[Pasted image 20250826013418.png]]
	-goto "Git: Raw Command" again
	- run 'stash pop'
	you should now have any WIP changes you have as well as the most recent notes.
	
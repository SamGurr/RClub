# Time to 'git' started!

----

## before we 'git' going..

* start a git account 
	
* download a user interface to interact with github from your command line 

	- git 
	
	- github user interface 
	
* email your github account ID to samuel_gurr@noaa.gov to be added as a collaborator to the repository 'RClub' and accept the invitation to be a collaborator (you will get an email notification)
	
*NOTE: git appears same as raw shell lfor using linux commands whereas the github UI is an application-like interface
the following workship uses commands for a git workflow that can be translated to the UI if prefered  

## objective:

* initiate team-based version control using our collaborative 'RClub' resository!

	- use basic linux commands to navigate your computer 

	- use a handful of main git commands to clone, edit, and add to the collaborative 'RClub' repository 
	
# Let's do this! 
*out of 'git' puns *...for now!*
----

Below are steps supplemented with color-coded <span style="color:red">linux</span> and <span style="color:green">git</span> commands 

### Clone the RClub repo

(1) Open git on your computer 

(2) Use linux commands to navigate to a directory where you want the 'RClub' respository to live. **You are now ready to <span style="color:clone">git</span> teh repository**

(3) Open the internet page for the repository https://github.com/SamGurr/RClub - rememeber you are now a collaborator on this repo! 

(4) click on the green box called Code (sceenshot below) . This will default to the HTTPS option for cloning the repository as https://github.com/SamGurr/RClub.git. Copy it!

(5) in your git window, clone the repository using <span style="color:green">git clone</span> as the following command

```
git clone https://github.com/SamGurr/RClub.git
```

* you will see a it load into your directory, should reach 100% fairly quick (~10-20 seconds)

(6) Great work! You now have all of the **main** branch!
 In other words, you **'git' the power** *...I told you I'd be back*

(7) Lets look at it using the linux commands cd and ls


*NOTE: As Uncle Ben said, "with great power comes great responsibility".* 
We all have master rights to this repository meaning that it can easily spiral to data conflicts when one version is behind/past another. 
These issues worsen as teams grow and become more productive. Seems counter-intuitive right? Working in this informal setting with a non-critical data
(this RClub repository) allows us to troubleshoot, learn, and decide upon what fits best for our current and future teams.

In the following steps, we will learn about forks and branches. These are essential aspects of collaborative workflows using git
to better manage large and productive teams!

# The mysterious of Branches and Forks
----

Again you might say, "'git' outta 'ere with this jargon!", but I'll breifly touch on these useful tools.
As mentioned above, you were made a collaborator on 'RClub' repository with full contribution and collaboration rights - 
you can smell the potential for trouble here (whaa HA HA!) 


#### Definitions: 

**fork** - a duplicated and **independent** version of from the original repository **up to the time it was forked**. A forked repository contains all the contents including the branches, 
however all edits to a forked respository have no effect on the original. 
	
	- useful when you want another researchers code for your own use without collaborating. The intent here is to split for an independent project/edits that may never reunite with the parent/origin (main) repository
	
		- example: website templates, code and mock data, etc. open data is cool right!

	- alternative definition as a 3-4 pronged utencil for formally transporting nutrients as opposed to the fingers that have well adapted for this task

**branch** - think **under construction** or **work in progress**, the branch is akin to a manuscript with track changes on where the parent/origin is a separate document that is managing changes. 
In other words, the branch mimics the parent/origin but its purpose is to prevent direct integration of change to the master repository without a stamp of approval from the manager(s)

- useful for collaborative workflow in large teams when edits are created on a particular feature with the intent to manage what is integrated to the parent/origin - occasionally a brnach can be named for that task such as 'timeline data' or 'stats'

- alternative definition as a tree's fingers of which a tree's *forks* would be much more appropriate in our modern age (review alt def of fork)

We have a <span style="color:green">branch</span> for teamwork 

This was created using the following git commands from the main branch:

* a 'teamwork' branch (<span style="color:green">-b</span>) was created in for the Rclub repository by using the command <span style="color:green">git checkout -b</span> 

- a shortened <span style="color:green">git co -b</span> ..if the 6 extra characters is just too much for ya

```
git checkout -b teamwork
```

```
git co -b teamwork
```

* use <span style="color:green">git branch</span> to see what branch you are in

*NOTE: the output will list all existing branches with your highlighted/bold. 
**The branch you are in  is also indicated at the end of our git command directory as (<current branch>)**

```
git branch
```


```
<span style="color:red">cd</span>
```


```
<span style="color:red">cd</span>
```

```
<span style="color:red">cd</span>
```

```
<span style="color:red">cd</span>
```

*Note: repository is just a jargony word for a folder, treat this as you would any project folder* 

*Important!: the following steps will add all contents of 'RClub' **including** the head folder 'RClub', therefore you do not have to name a master folder for it.* 
For example, you can initiate this process in a directory as simple as Documents or Documents/Github_repositories  or Documents/My_Projects. 
The choice is yours and will have zero impact on the collaborative repo - this is where it will live *for you only*

(3) *optional* make a directory for 
 clone the RClub repository to your personnal and/or work computer(s) 
# Persistme-Persistmy-Theme-Builder

In this repo, I intend to house the fruits of an open-source, community-led, project to design a program that will be 

  * 1.) operable via command line and / or GUI \n
  * 2.) cross-platform \n
  * 3.) simple to use, hopefully encapsulating a lot of the gorier, more tech-oriented bits. \n
  * 4.) enough of the idealistics; how about some details already? \n
  
### Something Concrete...

A lot of today's software is configurable. Although this is a very good thing in my opinion, I believe that it can be made much better. When I start using a program, it is usually not long until I start getting _the itch._ At that point, I can not stop myself wondering things like "where is the config file" or "I wonder if there is a Preferences setting(s)." Although I generally enjoy the process of answering these questions, it takes time to do so. Lets consider a sample program. We will take a look at settings for customizing the UI for Alacritty. Alacritty is a cross-platform terminal interface. One of it's top selling points, aside from being completely FREE, is that it is both completely stripped out-of-the-box and configurable to world's end. Once the user has rounded that learning curve, it is fairly simple to get Alacritty to a point where it looks/ acts nothing alacritty. 

SPOILER ALERT !!! That learning curve is the problem I am trying to solve. I want a program that gets me around that curve as quickly as possible. Better yet, 
lets take a completely different route and avoid that curve altogether. What if we didn't need to learn how alacritty configuration works just to configure it. 
What if we didnt even have to configure Alacritty at all! At least in the conventional way. We could just open our **persistmy** folder (or navigate to same directory inside a terminal) and create a file called 'alacritty.conf' or something similar. The program that I eventually intend to have living in this repo will take any valid files in the 'persistmy/' folder as input, change the configuration of the program with the same name as the file requesting the changes, and finally, persist those changes outside of our program, if possible. For programs like Alacritty, this will be easy. we just write changes to the proper 'alacritty.yaml' file. For other programs, it may not be so simple. 

In fact, our final product may not be a program may not be a program at all, in the traditional sense. Maybe it will work better as a framework or a protocol, such as http, ip, etc. (Surely you've all used the etc. protocol, right?) In this model, we would build / maintain a parser of some sort and lay out a specification (in other words, a rule book) for writing program implementations. This way, persistme doesn't need to contain the logic for reconfiguring millions of programs. We just need to provide the tools / resources and an instruction manual for building implementations. Once the program (or framework, or whatever else) is deployed, let's say Jon J. wants to use it. He uses VS Code every day, so his first objective, he decides, will be to build and store a custom Persistme configuration (Btw, _persistmy_ will be the name of the folder and 'Persistme' is reserved for the GUI and CLI front-end components. I was thinking that the overall architecture could be 'Persistmy-Persistme'. Regardless, it is just a working title) for Code. Hopefully, our initial release will come with a few prepackaged implementations for the most used **confables** (shorthand for programs that provide some means of configuration) according to our predictions. Maybe we can put a one or two question survey on Reddit just to feel out our predicted userbase, or something similar. I will leave that to be sorted out later, by the group.

Anyway, back to the use case. Jon opens his text editor and creates a 'persistmy/VS-Code.conf'. According to the layout that I am imagining, simply having a VS-Code file in the folder will trigger the software to check the target configuration (in this case, that of VS Code) against whatever is defined in the persistme directory. A blank file will be parsed and 'pass' automatically. By pass, I mean that the parser looked it over to make sure everything in the file was readable and achievable, then it diffed the file's contents against the current settings inside VS code, and finally, it will make any needed configuration changes and print / confirm via console message that there were changes made. It should also provide an entry to an application-scoped log file stored at .persistme or some other predetermined location. 

So far, I want (although in the  end, I am hoping that it is not only up to me...) this program to work as follows:

  ## This is for the community to decide! XD
  
To become a part of this community, send an email to:

<BUILDING EMAIL SERVER NOW. COME BACK IN A COUPLE OF HOURS AND IT SHOULD BE ROLLING>

Include the following:

  * name (1st name & last initial is fine for now if it is all you are comfortable with),
  * email (or preferred contact method & endpoint, although I am not going to learn any new platforms etc. just to get ahold of someone.)
  * a bit of relative info about you. e.g. Why are you volunteering; What do you most enjoy about programming, open-source, etc.
  * relative experience (mostly interested in open-source exp. Remember, this isn't a job interview. This just lets us know where your skillset will most benifit the project, and where you will likely be most comfortable. If you think that you might already know this, then by all means, let us know.)
  * What platform(s) should we use for communication among the community, and why.
  * Any info that I haven't included, but you think is relevant.
  * If you have any experience with administration, let me know here. Our community will need people to watch over our various networks (email, reddit, any other communication channels that we decide to use) and take on supervisory roles inside the project itself. While I DO NOT want to create a strict workplace type of environment, I also know that an environment with zero structure will breed zero productivity. IMO, the ideal environment will reside somewhere in the middle of these 2 extremes. Supervisory titles will be given, but they will not have 'power' over anyone. Their primary role in this capacity will be to facilitation. In fact, we will reserve the word / title 'coordinator' for these roles. This person will be responsible for keeping their sub-group working in the same direction and not against each other. Additionally, we will likely have regular coordinatoin meetings in which all coordinators will discuss the news / issues of the day/week/whatever group decides, and afterward, the coordinators will be responsible for letting their team know. Additionally, we will need to set up a message board somewhere. Again, your input is wanted. In the end, I suspect that we will use community votin for most topics. This all, of course, depends on the size of the community, so I will leave it at, "we'll see."
  
Also, if you see any fundamental flaws in the concept that I have laid out, or if you have any ideas for improvement. I will make a list of these, along with the contributor for each (if you wish for your idea(s) to be attributed to 'anonymous' say so here and I / we will honour your wishes.) Once we all get together, one of our first tasks, after setting up an acceptably robust communication system, there will likely be multiple methods of getting ahold of someone at every leg of the project. But for now...
 
 ## PHASE ALPHA : # EXPIRIMENTAL FREE FOR ALL!!
 
 A couple of points to make..
 
  - The project now has a Reddit base at `r/persistmepersistmy`
  - Excepting ideas "willy nilly"
  - Send a pull request with thoughts: 
 where should we go from here.
 App(s) structure
 recommendations -- Techstacks etc.
 license type
 anything, I want to start by LISTENING
  - Accepting anything with actual ideas (no lude content, etc., etc., you know the drill)
  - Well call it a community brainstorm event.
  - Sign up on Reddit and include reddit username.
  - These can be our identifiers until we get a proper system in place
 

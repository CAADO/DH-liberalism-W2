First step for this week is reading the assigned texts, after reinstalling all the softwear from last week onto a new computer. 

I have made a basic distiction for myself: Notes is for whatever I feel like recording during the proccess of doing this week's work, whereas reflections will always be the last thing I do in the week. 

GitHub not having the ability to just hit a 'save' button but rather having to enter-leave-enter every time you want to save a line of text is super painful and encorages me to just not save my work, even on a computer prone to crashes. 

reading the croudsourcing article: resistance to crowdsorucing particularly for things like transcribing and digitisation stinks of elitism something feirce. Nothing within either of these tasks requries education, honed skills, professional judgement or even a whole lot of brainpower. Having someone who can do that in a supervisory position is good, but the tasks themselves are very simple. 
  I should correct myself here. It's not so much that experence doesn't make one a much better and faster transcriber, but rather you     really don't need much to START transcribing and much of the learning for the task is self-contained. 

The paper was an interesting look at the economics of crowdsorucing, but it does requrie the attention of volunteers. It seems quite clear that large, long term projects have significantly more potential for crowdsourcing due to startup costs. 

writing Github notes with unstable internet is a dangerous game. 

I read the two Bethman articles in order that they are on the instructions: 2018 followed by 2012. This seemed something of a waste, since the 2018 paper already spends time summarising the 2012. 

download time for ana is almost an hour on the present internet, which is pretty painful. 

I attempted to just move onto the next task but that needs ana as well. 

Next section: APIs. I... think I know how to do this? 

Yep, it's all working well until... I need ana again. 

Next step involves downloading more things, things being the two R packages. Well, see you in a a couple hours Git, I'm getting a beer or something. 

After a short interlude to have a midnight hamburger,do battle with google books and to yell at a book from the 80s that messed up its citations, we have returned. conda 4.8.2 and python 3.7.6 both running fine

right onto wget. Wget is installed, but for some reason conda isn't finding it in C. I think I know why?

current error: 'wget.exe' is not recognized as an internal or external command,
operable program or batch file.

So far, I've attempted to troubleshoot through the discord messages other people have left, and I'm at the point where I'm pretty sure that the wget install was messed up

new error: Access is denied. Going to try and run the shell as admin.

after trying some more moving around, I managed to get a 'you can't do that dave' popup I didn't even know windows had.

After attempting a restart, I went with my gut and reinstalled the program, this time with the 64 bit version. After a small amount of brutal failure, I got it working. 

the program is running, but it sure is finding a lot of bad file location, descriptors and the rest.

so this is slow, even for slow. break time I guess, I hope I don't brick my pc by the time I get back or something. 

finished the DL, total wall clock time 33m 16s

next exerise was smooth

final exersie of Wget had problems finding the file again, so I just moved a copy of wget into the folder.

I had another access denied error with the popup banner, it's something to do with copying the file and the filesize of wget going to zero. trying the copy again worked (?)

SELF TIP: if you get 'can't run' error, check the filesize of the Wget that's trying to run. If it's 0, that's your problem. 

Other then an error becuase I forgot a) save to the right place, b) format my name right, c) save it after fixing it the API stuff went quite well. I'm already somewhat familiar with APIs, so I will go back and do more if I have extra time, but for now I'm moving on. 

oh god more installs end my life, I'm doing this one later I guess.

after a break for sleep and to let R install, I'm back and everything seems to be going smoothly

First problem showed up when my R is not the same as the one in the pictures, but I continued doing exersises anyway, just finding the commands I'm looking for. after giving the three library commands, instruction 9, I got an error that they were built in 3.6.3, but the program seemed fine. After running it (step 10) I got a fatal error. 

retry in a new session also crashed in the same place, so it wasn't just a missimput

pretty sure I set the path wrong

I did, but the actual crash error casue has been found after some tinkering: the picture was in the wrong location. I put the picture in the same r-stuff folder that I was working in, and the function worked. 

Once I got past this error, the rest of the R section went smoothly. 

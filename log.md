# 100 Days Of Code - Log

<!-- Examples
### Day 0: February 30, 2017 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2017 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence) -->

### Day 0: January 2nd, 2017

**Today's Progress**: Worked on CTCI problems, and put some thought into what I'll be starting on tomorrow.

**Thoughts:** Trying to figure out where to start with my project and what all I will need to know in order to build it. I think I've settled on working on this
barcode review app that will allow me to scan any item in a store and aggregate reviews. Things I need to think about regarding it: UI, database/hosting a server,
api's for reviews.

### Day 1: January 3nd, 2017

**Today's Progress**: Researched how to open up the camera to scan a barcode. Managed to get a few lines written but was unable to get the app to scan any barcodes.

**Thoughts:** So I was kind of expecting this hour to go something like this: I would start writing some lines of code, realize I don't know how to do something, quickly look it up then jump right back into the code, rinse and repeat. It was something like that, where I opened up Android Studio to the project I started, figured out my next step, then spent 2 hours researching with maybe a line of code to show for it. So I'm realizing that this will be a slower process than I originally thought. Which I also need to realize, is just part of the learning process. I don't know how to do all of this yet, so I will be spending more time researching than coding to begin with.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 2: January 4th, 2017

**Today's Progress**: Found a better guide and got a better understanding of the barcode library.

**Thoughts:** I felt like I made a lot more progress compared to yesterday. I managed to get a lot more code down thanks to a guide that helped explain things a bit better. However, I was unable to get the camera to start or detect anything. I believe it may have something to do either the permissions, or the intent. I'll try to focus on more debugging tomorrow.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 3: January 5th, 2017

**Today's Progress**: Fixed the app permission to get the camera working. Added the Retrofit library, and started on the code to pass the UPC number to an API and return the information.

**Thoughts:** Picking up speed now. I was able to quickly find out why my camera wasn't working in the app early today (Had to go into the app's settings and turn on the permission), but wasn't able to work on any code until later tonight. I decided my next step should be to setup RetroFit to call an API and get information about the barcode number. I found a UPC database that I hope will large enough to get any barcode I send it. I'm hoping to be done with the Retrofit part tomorrow, so I can start testing some this weekend.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 4: January 6th, 2017

**Today's Progress**: Not as productive as I was hoping. Tried getting Retrofit to work, but was unable to. Need to look do more research into it.

**Thoughts:** I waited too late at night to start working on this, and so I'm struggling with staying awake and trying to remember how I managed to get Retrofit to work when I used it several months ago. I was able to get a little bit of code down, but I'm going to have to do a lot more tomorrow to get things working.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 5: January 7th, 2017

**Today's Progress**: Messed around with some of the layout settings and worked on getting Retrofit working.

**Thoughts:** So I'm getting to the point where I realize I need to spend more time in Udacity or looking at some other Android tutorials. I've forgotten a lot of what I learned through the Udacity course and now I'm now spending a lot of time going back through stuff I should know how to do. I'll plan to spend more time in tutorials next week while I work on this.
As far as progress of my app, Retrofit isn't properly getting the UPC API, so the app is currently crashing whenever I scan a barcode. More to work on tomorrow.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 6: January 8th, 2017

**Today's Progress**: Solved problem 4.9 in "Cracking the Coding Interview."

**Thoughts:** I decided to change up my night a bit and work on the problems in the CTCI book since I'm meeting to go over the problems tomorrow. I managed to solve 4.9, but still need to review the actual solution in the book. I also need to make sure I'm spending enough time going back through the chapters again, especially after not looking at it for a few days.

**Link to Work** [CTCIProblems](https://github.com/SudoForkBomb/CTCIProblems)

### Day 7: January 10th, 2017

**Today's Progress**: Still unsuccessful troubleshooting app. Tried debugging the retrofit portion of the app, but it's still crashing when I scan a barcode. Managed to correct a few lines that would have caused problems later though.

**Thoughts:** Still having trouble with this app. I tried debugging for a bit, and double checked the barcodes I was scanning, but it still doesn't seem to be making the actual call to the API properly. I must still have something wrong with retrofit. I'll try to spend more time learning it tomorrow, and hopefully come back with a better understanding of it. Also contemplating starting a different project...

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 8: January 11th, 2017

**Today's Progress**: Fixed retrofit and got the app working!

**Thoughts:** Tired and irritated. Had to add a line this line in order to get it working ".addConverterFactory(GsonConverterFactory.create())". Still a little unsure why I needed it, but I guess now I need to spend more time looking up about JSON and GSON.

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 9: January 12th, 2017

**Today's Progress**: Did a little bit more troubleshooting and discovered the problem with the api call. It seems like it's making the returning with the call just fine, but it's printing an answer before the api call is complete. I think once I do a bit more with the design and function, outside of the api call, things will fall into place fine.

**Thoughts:** Still a little frustrated with retrofit, but I'm understanding it a little more. I think I'm doing better with troubleshooting and now I'm excited to move forward with working on more design and functionality of the app. I want to try to work on setting the button to trigger the camera to open, and close once it's scanned the barcode.

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 10: January 13th, 2017

**Today's Progress**: Started splitting up my MainActivity file into two Fragments, one for the camera, and the other for the Barcode details. Still pretty broken up at this point, but I'll work on finishing up putting them together tomorrow. I'm sure more troubleshooting will ensue.

**Thoughts:** Started to work on more of the design and functionality of the app. I've had to do a lot of review with my Popular Movies app, since I don't quite remember how to implement Fragments anymore. I need to go back and read more about them and when is the proper time to actually use Fragments over Activities.

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 11: January 14th, 2017

**Today's Progress**: Nothing exciting, just cleaned up the Fragments some more.

**Thoughts:** Need to look into intents and passing the information between Fragments.

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 12: January 16th, 2017

**Today's Progress**: Worked on getting my BarcodeDetailsFragment to try and start the CameraFragment and pass the information of the barcode, through the Activity. I managed to do this using the OnFragmentInteractionListener, and the onAttach method. (https://developer.android.com/training/basics/fragments/communicating.html)

**Thoughts:** Confusing, yes, but I  believe this is the appropriate next step to getting things to work. I start with the BarcodeDetailsFragment in the MainActivity. Then when I click the button, I want it to inflate the CameraFragment, then once it's gotten the barcode, close out this fragment, and return the information to the BarcodeDetailsFragment. I think I'm almost there, but it's more tutorials and testing.
My only concern with my progress so far, is that I'm starting to feel like I'm looking for what I need to do and hacking it together, instead of following some sort of flow or process. Maybe that's just how things are supposed to be when starting out? Need to find a proper Android book..

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 13: January 17th, 2017

**Today's Progress**: More progress with communication between BarcodeDetailsFragment to MainActivity to CameraFragment. Crashes when trying to load CameraFragment because there is no container for it, but the fact that the button is actually triggering the CameraFragment to open is a good start.

**Thoughts:** Feel like I'm on the border of understanding what's going on. I'm not helping myself with trying to figure it out as I'm working on it, because it's becoming difficult to figure out how these should work at the same time I'm trying to figure out how to implement things. Trying to jot down a quick flow chart is helping, but I need to spend time to work on the flow chart.

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 14: January 18th, 2017

**Today's Progress**: Managed to get the CameraFragment to open up when I trigger it with the button from BarcodeDetailsFragment. There still seems to be some cross overlay between the two fragments. I need to double check the CameraFragment class and make sure that there are no errors.

**Thoughts:** Not the most productive night, but I made a small little victory with stopping the app from crashing. I need to go back through and double check the classes and make sure the simple parts are clean and correct.

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 15: January 19th, 2017

**Today's Progress**: Made some changes to the CameraFragment in an attempt to get the camera to display. It's actually showing the correct fragment now, but the button is still in the CameraFragment for some reason.

**Thoughts:** Nothing new to report. More troubleshooting, need to spend more time on this and need to start earlier in the day. Probably going to switch gears tomorrow though and work on CTCI problems.

**Link to Work** **Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 16: January 20th, 2017

**Today's Progress**: Got things set up and started working on Chapter 5 of Cracking the Coding Interview. Not a whole lot of code written, but got a little bit down.

**Thoughts:** Realized how much I forgot or didn't know about Bit Manipulation. So I'm spending a bit more time leaning than coding for today.

**Link to Work** [CTCIProblems](https://github.com/SudoForkBomb/CTCIProblems)

### Day 17: January 21th, 2017

**Today's Progress**: Feel like I've pretty much finished solving 5.2. Just need to complete the rest of the code for that problem (Figure out a way to bail out if the number is repeating.)

**Thoughts:** Feel like I've made some progress on trying to learn more/refresh myself on bit manipulation, and mainly, bit conversion. Going to try and meet up with friends tomorrow to try and maybe get some help on the other problems in the chapter.

**Link to Work** [CTCIProblems](https://github.com/SudoForkBomb/CTCIProblems)

### Day 18: January 22th, 2017

**Today's Progress**: Not a whole lot. Spent more time trying to solve the problem than actually coding. The nap didn't exactly help either.

**Thoughts:** Got really lazy this weekend and did not accomplish near as much as I had hoped. Still need to finish the rest of these problems by tomorrow, but I'm still struggling with them and I just keep distracting myself with other things. At least I know some more areas I need to focus on.

**Link to Work** [CTCIProblems](https://github.com/SudoForkBomb/CTCIProblems)

### Day 19: January 23th, 2017

**Today's Progress**: Have the fragments working properly and talking to each other through the activity using the FragmentManger and FragmentTransaction. Now I need to work on getting the camera to work again.
 master

**Thoughts:** Feel good again about working on this. Found a nice, in-depth guide at https://guides.codepath.com/android that gives really good cliffnotes for different Android topics. Went through the section for Fragments and it seemed to really help me understand and get things working tonight.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 20: January 24th, 2017

**Today's Progress**: Tried troubleshooting the CameraFragment to get the camera image to show up, and can't figure out why. So I'm still having issues with it. Need to go back and look into the BarcodeScanner stuff.

**Thoughts:** Not really sure why the camera image is not showing up. Thinking it may be related to the class ending, or maybe there is something wrong with how I have the BarcodeScanner or CameraSource set up.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 21: January 25th, 2017

**Today's Progress**: Cleaned up the code a bit. No progress made with getting the camera working.

**Thoughts:** Just confused to why it's not working. Can't seem to find a decent tutorial again. More searching and progress tomorrow hopefully.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 22: January 26th, 2017

**Today's Progress**: Got the CameraView working. I believe something was happening between the RetroFit task, and OnCreateView returning before it was done. This is further confirmed since my txtView is never updated  after scanning a barcode.

**Thoughts:** Need to learn more about Android's Activity and Fragment lifecycles, so that I'm doing these things in the proper order and that I'm able to do them. For some reason I guess that I thought that while the camera was being displayed, it was looping and would update things whenever it scanned something. That wouldn't make sense though since it has to return the view at the end of OnCreateView to even display things. More studying to be done.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 23: January 27th, 2017

**Today's Progress**: I looked up more about the Fragment lifecycle and decided to add onViewCreated method within CameraFragment. This takes place after onCreateView, so I added my code that takes in the barcode and sets the txtView within here. It successfully worked and I even added it so that it would set the text in txtView to the most recent barcode.

**Thoughts:** Still need to make sure I really understand the lifecycles, especially making sure things are closed or destroyed. My next task I'd like to do is create another Activity/Fragment combo and then pass on the barcode number to them, which will then get the Retrofit treatment and I can display the details of the item.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 24: January 28th, 2017

**Today's Progress**: Added the new Fragment and Activity and started implementing the new order of process for the app.

**Thoughts:** Nothing too exciting or much. Just worked on getting things implemented. More testing and things tomorrow.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 25: January 29th, 2017

**Today's Progress**: Made a few more changes to the new fragment and making sure it fit and worked in the new order.

**Thoughts:** Same as last night. Nothing too exciting or much. Just worked on getting things implemented. More testing and things tomorrow.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 26: January 30th, 2017

**Today's Progress**: Changed the Details layout to output the information from the UPC. Worked on the details fragment starting once the camera has detected a barcode number.

**Thoughts:** Had to speed some time looking at my older app on how to go from one activity to another and then initiate the fragment for the details. Progress has been a little slow, but I'm hoping to pick up  more this week.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 27: January 31th, 2017

**Today's Progress**: Worked on getting things right with passing the Barcode Number. Testing some tomorrow.

**Thoughts:** Tired. Need to start earlier and be more productive tomorrow.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 28: February 1st, 2017

**Today's Progress**: Worked on passing the barcode number from the cameraFragment to the mainActivity to the DetailsFragment using an Intent. Messed around with the Retrofit code as well. App was crashing last test, and it seemed to be related to the Activity I was trying to call.

**Thoughts:** May need to do some digging about going from one Activity to another Activity.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 29: February 3rd, 2017

**Today's Progress**:Made some changes to try and get the cameraFragment to pass the string to the detailsActivity. No luck.

**Thoughts:** Not sure where I'm messing up. Error message is telling me I need to implement a method, which isn't right. Even tried it to just show it wasn't right. Need to test some more. Getting a little  burnt out on the app as well. Want to try and do more research and look into trying to do something else.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 30: February 4th, 2017

**Today's Progress**:Trying changes to get the detailsActivity working.

**Thoughts:** Tired of this app, stuck because I don't know how to do whatever is required next, and don't have a lot of time to go through a tutorial..

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 31: February 5th, 2017

**Today's Progress**:No new progress. More troubleshooting.

**Thoughts:** Think I may try a new project tomorrow.

**Link to Work** [Barcode Scanner](https://github.com/SudoForkBomb/BarcodeScanner)

### Day 32: February 6th, 2017

**Today's Progress**: Took a break from my Barcode app to try and focus on learning web development from FreeCodeCamp. Spent a few hours working through the Front-End Certification.

**Thoughts:** Kind of rethinking of my coding direction currently, so going to go through the FreeCodeCamp courses to learn and also just take a break from the Barcode up until I can find more time to spend going through those tutorials.

### Day 33: February 7th, 2017

**Today's Progress**: Finished up with the "HTML and CSS" section for the Front-End Certification.

**Thoughts:** So far, it's been pretty simple to get into. Trying to not get distracted has been hard though, since it's kind of slow. I'm looking forward to getting started on the projects though.

**Link to Work** [FreeCodeCamp](https://www.freecodecamp.com/)

### Day 34: February 8th, 2017

**Today's Progress**: Finished up with the "Responsive Design with Bootstrap" section for the Front-End Certification.

**Thoughts:** Excited I got to learn about Bootstrap today. Messed with it about a year ago, so I was glad to be able to use it again. A few more hours and I should be on the projcets.

**Link to Work** [FreeCodeCamp](https://www.freecodecamp.com/)

### Day 35: February 9th, 2017

**Today's Progress**: Finished up with the "jQuery" section for the Front-End Certification.

**Thoughts:** Finally done with the tutorials and now onto the first project, Building a Tribute Page. No idea who I'm going to do it on, but I'll try to figure it out. I'm also going to try and attempt doing the projects outside of codepen.io. Even though it would make it a bit easier to use, I'd rather keep pushing to Github. Need to maintain those green squares. I'll also be spending some time this weekend working on "Cracking the Coding Interview."

**Link to Work** [FreeCodeCamp](https://www.freecodecamp.com/)

### Day 36: February 10th, 2017

**Today's Progress**: Got things set up for my Tribute Page project. Managed to get Bootstrap downloaded and loaded into the folder and ran a few tests to make sure it's set up properly.

**Thoughts:** Going to have to do a lot of looking up as I work on this. Downside of blowing through the tutorials so quickly is the info didn't stick very well. I should be fine though, may just go a bit slower. Need to spend some time and figure out who I want to do my tribute for.

**Link to Work** [TributePageFCC](https://github.com/SudoForkBomb/TributePageFCC)

### Day 37: February 11th, 2017

**Today's Progress**: Not a whole lot. Trying to work on the design a bit.

**Thoughts:** Things aren't showing up like I think they should, so Bootstrap may not be set up properly. Need to go back through the tutorials and check things.

**Link to Work** [TributePageFCC](https://github.com/SudoForkBomb/TributePageFCC)

### Day 38: February 12th, 2017

**Today's Progress**: Fixed Boostrap setup. Tested out some styles.

**Thoughts:** Been really slack lately. Need to spend more time reading and studying.

**Link to Work** [TributePageFCC](https://github.com/SudoForkBomb/TributePageFCC)

### Day 39: February 13th, 2017

**Today's Progress**: Worked on page organization and getting the main sections down. Tried to get things in their proper place on the page with the bootstrap classes. May try to see if I can organize them within the style section.

**Thoughts:** Front-End right now seems to be a lot of repeating the same code, which makes it weird because I remember learning that if you are repeating code, you should make a method or class that you can call instead. So my first instinct is to find a way to put most of the stuff in the styles section and then use a class. However, it seems like there are just slight differences in each section, so it make it hard to create just a couple of style classes. Oh well. For now I'll focus on just getting things working, then dig into the code a bit to clean it up as I learn more.

**Link to Work** [TributePageFCC](https://github.com/SudoForkBomb/TributePageFCC)

### Day 40: February 14th, 2017

**Today's Progress**: Decided to dedicate my tribute page to Rick, from Rick and Morty. Added information about him to the page and worked on getting the image margins correct. Still need to work on getting the fonts and things set to the example page.

**Thoughts:** Glad I got some rest today and was able to take my time working on this. Honestly felt a little weird it came together once I started putting the information in. Think I should be done with it tomorrow.

**Link to Work** [TributePageFCC](https://github.com/SudoForkBomb/TributePageFCC)

### Day 41: February 15th, 2017

**Today's Progress**: Worked on fine tuning the design to match that of the example. Still need to add a couple of links and some addtional text.

**Thoughts:** Will plan to start the additional projects tomorrow or this weekend while I finish up with the tribute page.

**Link to Work** [TributePageFCC](https://github.com/SudoForkBomb/TributePageFCC)

### Day 42: February 16th, 2017

**Today's Progress**: I think I'm done with my Tribute Page! And I think it looks pretty good. Once I was done, I looked at the source code for the example page and learned some commands that worked better than my hacked up attempts. (i.e Jumptron and Thumbnail classes vs using Wells.)

**Thoughts:** Excited to move onto the next project. One weird thing is that I'm trying to paste my code into Codepen so I can submit it, but it's not displaying properly. It's like my picture isn't resizing to fit into the bootstrap columns. I also am a little confused why the example didn't need to use that many row classes, when mine seemed to need them in order for the text to appear on the proper lines. May troubleshoot it a bit later while I start on the next thing.

**Link to Work** [TributePageFCC](https://github.com/SudoForkBomb/TributePageFCC)

### Day 43: February 17th, 2017

**Today's Progress**: Started working through the JavaScript section on FreeCodeCamp.

**Thoughts:** This tutorial is very similar to other coding tutorials and seems to be going through basic coding concepts that I have already learned. Will try to start my portfolio project this weekend.

**Link to Work** [FreeCodeCamp](https://www.freecodecamp.com/)

### Day 44: February 18th, 2017

**Today's Progress**: More of the JavaScript section on FreeCodeCamp.

**Thoughts:** Not much. Wish I had been more productive today, but I'll try to work on the portfolio site tomorrow.

**Link to Work** [FreeCodeCamp](https://www.freecodecamp.com/)

### Day 45: February 19th, 2017

**Today's Progress**: Made some more progress through the JavaScript section. Also got started updating my portfolio site.

**Thoughts:** The portfolio site seems it may be a pretty a long progress. Right now I don't have much of an idea on what I want to put on there. I guess that's the point though, and I'll show off the things I learn them? Do have a few cool ideas I'd like to try out on there. May need to see about getting a droplet to host my site on too, since I'm a little limited with hosting it through Github. I'll try to be more focused and productive this week.

**Link to Work** [FreeCodeCamp](https://www.freecodecamp.com/) [Portfolio Project](https://github.com/SudoForkBomb/crtaylor123.github.io/) (http://www.chrisrtaylor.me/)

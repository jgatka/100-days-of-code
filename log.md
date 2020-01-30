# 100 Days Of Code - Log

### Day 16: January 29th, 2020
#### Size, Height, and Weight

**Today's Progress:** I completed three exercises in the freecodecamp.org chapter on applied visual design. I learned how to style elements using the font-size, font-weight, and line-height properties. These properties can be assigned to headings and paragraphs tags.

**Thoughts:** I had a busy day but managed to get through three exercises. I'm now 33% through the chapter on AVD. I'm sure that these properties can be applied to more tags than just the headings and paragraph tags. I'll have to test this in later chapters. While I've used font-size before, the font-weight and line-height properties are brand new to me. I've said it before and I'll say it again, I'm glad I followed my instincts and decided to start from the beginning. Many gaps that I didn't know existed are being filled in. Also...this week I put together a new PC, so I'm actually updating the log in Notepad++ on my PC instead of in vim on my Raspberry Pi. I use vim enough at my job that I'm not worried about losing that skill set. It's also worth noting that I generated rsa keys and uploaded them to github so that I could update the log from this PC as well. Does using ssh-keygen in powershell count as a #100daysofcode exercise? I think maybe it should (:

<hr />

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

### Day 15: January 28th, 2020
#### _Box-shadows, Opacity, and Text-Transform_

**Today's Progress:** I completed three exercises in the freecodecamp chapter on applied visual design. I learned how to code box shadows, set opacity, and use the text-transform property to hardcode the case of an element.**

**Thoughts:** Adding a box shadow to a card element made it look much more appealing. I can _see_ the quallity of my code improving. The context for box shadows is actually kind of difficult to digest. I'll need to practice with this one a lot more. The elements (offset-x, offset-y, blur-radius, spread-radius, and color) must appear in a specific order, and 2 of them (blur-radius, spread-radius) are optional. I assumed opacity would go from 0 to 255, but actually the range is 1 (solid) to 0 (transparent). As an InfoSec guy, I can see nefarious uses for setting the opacity of elements that I seek to hide from the user to 0. The text transform property will allow me to set the case of all words in an element rather than editing the words individually. Handy for headlines, titles, headings, etc.**

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 14: January 27th, 2020
#### _More AVD_

**Today's Progress:** I continued working through _vimtutor_, and learned how to specify a line I'm on (CTRL+G), go to that line (<number> CTRL+G), go to the end of the file (G), and go back to the beginning of a file (gg). I also learned how to search for text using (/). In bash, I learned how to work with aliases, how to format my ~/.bashrc file. For freecodecamp, I learned how to style text using the background-color: rgba(x,y,z,0) format, which includes control for opacity. I also learned how to resize headers using the font-size property, so that the headers are larger than the paragraph text.

**Thoughts:** I jumped around quite a bit today but I'm really happy that I'm continuing to diversity my skill set. The vim and bash knowledge come in handy and I'm glad that I'm leveling those skills up to scale along with my coding ability.

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 11-13: January 24th-26th, 2020
#### _Applied Visual Design_

**Today's Progress:** I completed the chapter on CSS and moved into the next chapter; Applied Visual Design. I completed the final 4 exercises from the CSS chapter, which were:

* Improve Compatibility with Browser Fallbacks
* Inherit CSS Variables
* Change a variable for a specific area
* Use a media query to change a variable

_...and from the Applied Visual Design chapter:_
* Introduction to the Applied Visual Design Challenges
* Create Visual Balance Using the text-align Property
* Adjust the Width of an Element Using the width Property
* Adjust the Height of an Element Using the height Property
* Use the strong Tag to Make Text Bold
* Use the u Tag to Underline Text
* Use the em Tag to Italicize Text
* Use the s Tag to Strikethrough Text
* Create a Horizontal Line Using the hr Element

**Thoughts:** I'm 15% through the chapter on Applied Visual Design already. I covered a lot of ground over the last 3 days and I'm still enjoying the consistency. I'm worried I'm going to forget some of the class/variable/inline selection from the CSS chapter, so I'm contemplating starting some of the projects early. I peeked ahead and there's a portfolio and memorial page that I could probably put together now and iterate/improve upon as the coursework continues. However, I want to make sure I stick with this, so I don't want to get _too_ far ahead of myself. A lot of the AVD exercises were review for me. I always used the "b" tag instead of "strong", and the "i" tag instead of "em", but I'm glad I got some practice learning the other way. The text align lessons were new information for me though.

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 10: January 23rd, 2020
#### _CSS Variables_

**Today's Progress:** I completed 3 freecodecamp lessons on creating and using CSS variables to change several elements at once. I also learned how to create a fallback variable in case a browser limitation or other error causes the CSS variable to not display properly.

**Thoughts**: I've now completed 91% of the CSS chapter and only have 4 lessons left. The next chapter deals with applied visual design. Stoked. I'm also getting pretty damn good with vim.

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 9: January 22nd, 2020
#### _Httpserver & RGB Syntax_

**Today's Progress:** As part of my responsibilities at work, I learned how to use the more advanced features of [advanced http server](https://github.com/zeroSteiner/AdvancedHTTPServer). I used it to serve up a sample page that I wrote as well as to serve up files for future endeavors. I completed 2 freecodecamp exercises and learned how to use rgb syntax to color an element as opposed to hex codes or plain English.

**Thoughts:** Busy day at work, band practice, and I still managed to get in two exercises and update my log. Rad. Onward and upward.

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 8: January 21st, 2020
#### _ROYGBIV_

**Today's Progress:** I finished the command line editing chapter in my Bash book. I also learned how to use the replace, change, and put commands in vim. I learned how to use hex codes to style web pages with specific colors. I learned how to use hex codes to style page with mixed colors (R,G,B), and I learned how to style pages with colors using abbreviated hex codes. I only have 10 exercises left in the Basic CSS chapter of the Responsive Web Design Certification course.

**Thoughts:** When I first started using HTML/CSS back in the MySpace days I used hex codes. I would just look them up (probably yahoo search back in those days) and add them to my page. Now I know that the codes use two hexadecimal characters each for Red, Green, and Blue. This revelation made me harken back to elementary school and learning that TVs (and later CRT monitors) used RGB to display colors. I also had no idea that you could abbreviate the hex codes from 6 characters down to three. Still, I plan on actually writing the color out wherever possible, do keep my code readable. I'm continuing to come up with cool ideas for the projects later in the course where I'll build my own pages. Stoked.

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 2-7: January 15th-20th, 2020
#### _Grab Bag_

**Today's Progress:** I made it through 10 lessons in freecodecamp today. I'm now 70% done with the CSS curriculum. I've started thinking about my portfolio site and I'm stoked to learn more and eventually create a sort of "capstone" project to put all that I've learned to use.

**Thoughts:** I was originally going to admit defeat already, since I didn't do enough logging over the past couple of days. But I have to learn to give myself more credit. What _is_ important is that I _did_ write code each day, even if it was outside of the freecodecamp curriculum I've been emphasizing. Here are some of the things I studied over the past few days:

* Emacs commands in bash
* Using intruder/payloads in Burp Suite to automate attempted attacks
* More vim practice
* Which styles will take precedence when simultaneously using CSS, id attributes, inline formatting and the !important tag 

The lesson about precedence is another example of something that I never learned when teaching myself to code outside of a structured curriculum. I just styled text and hoped for the best. Trial and error were my ways of knowing which takes precedence. I'm happy that I finally know so many ways to style attributes using HTML/CSS, and I'm really thankful for freecodecamp.org!

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 1: January 14th, 2020
#### _Steady_

**Today's Progress:** Today I spoke on the phone with a developer that I used to work with for about an hour. I told him my goals, what I want to learn,what kind of projects I want to build once I'm proficient enough. Over the past 9 days I've written bash scripts at work to help me query information I needed. Tonight after my phone call I completed 2 more CSS exercises. I'm now 50% complete with the CSS portion of the freecodecamp curriculum. I learned how to use clockwise notation to adjust all four sides of an object (top, right, bottom, left). I also learned how to copy and paste in vim using V,y,p. :)

**Thoughts:** I did not know that you could use clockwise notation to adjust all four sides of an object in a single line. As painful as it is to start this journey at the beginning (I studied HTML/CSS in the myspace.com era...yeah...I'm that old), I'm glad that I'm doing it this way. I'm picking up bits and pieces of stuff that I missed along the way. It's the slow and steady way but I'm hoping it's the way that wins the race.

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 0: January 5th, 2020
#### _Starting Over_

**Today's Progress:** Over the past 5 days, I completed the following challenges on freecodecamp.org, as part of the Basic CSS unit of the Responsive Web Design certification.

* Adjust the Padding of an Element
* Use an id Attribute to Style an Element
* Set the id of an Element	
* Give a Background Color to a div Element

**Thoughts:** Starting a new job, a death in the family, my PC completely dying on me, continual struggles in my personal life, learning vim (which I'm using to write this update, btw)...I could make all sorts of excuses on why I abandoned 100 days of code in 2019, but they'd be just that, excuses. Instead I'm just going to get right back on the horse and jump back into this. My new priority will be completing as much of freecodecamp.org as I can. I'll also continue working on python apps to serve my personal and work needs whenever such needs arise. I'd like to continue working on challenges on code wars when opportunities present themselves.

**Link(s) to work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 0: December 31, 2018
#### _Getting Ready_

**Today's Progress:** Forked the original github repo for 100 days of code. I decided that for this, my first "round" of #100daysofcode I'm going to focus on C#/.NET development. I plan on completing some C# coursework and also doing codewars.com exercises in order to actually build things using what I've learned.

**Thoughts:** I'm nervous, but I know I'm going to have a blast once I get started. I've always enjoyed coding, and my career aspirations of becoming a security engineer require me to get more proficient at it.

**Link(s) to work:**
* [My 100 Days of Code Repo on Github](https://github.com/jgatka/100-days-of-code)
* [My profile on codewars](https://www.codewars.com/users/jgatka)

<hr />

### Day 1: January 1, 2019
#### _Arabic to Roman and Github Woes_

**Today's Progress:** As a way to get back into serious coding after some months off, I revisited codewars and decided to take on the "Roman Numerals Encoder" Challenge, requires an app to take an integer greater than zero and convert it to a roman numeral. I knocked it out, and posting the code into codewars and watching all of the unit tests pass was SO SATISFYING. I even leveled up! I'm stoked to be back to writing code.

Having successfully created a new app, I decided to upload the project to github. The fact that I'm a serious InfoSec professional who uses multi-factor authentication caused me some problems tonight. I had to do a deep dive and learn how to use MFA in github with SSH keys and user tokens. It took me longer to troubleshoot this than it did to write my app! But alas, at about 12:30am I finally got things figured out and now my code is available in github. Perhaps I'll revisit it later and refactor it with some switch cases and some try/catch blocks.

**Thoughts:** It's interesting that the github troubleshooting took longer to deal with than writing the app itself. I suppose that's the nature of the beast though. Years of InfoSec experience has taught me to remain calm when fires need to be put out. Special thanks to my buddy Samuel Kelemen for helping me troubleshoot the github issues. I linked to his github below and you should check it out.

**Link(s) to work:**
* [Roman Numerals Encoder](https://github.com/jgatka/RomanNumeralsEncoder)
* [Samuel Kelemen @ github](https://github.com/SCKelemen)

<hr />

### Day 2: January 2, 2019
#### _Started Gray Hat C#_

**Today's Progress:** Having spent a good amount of my day at work writing and running powershell scripts, I decided to crack into the _Gray Hat C#_ book that I recently purchased as part of Humble Bundle's holiday hacking bundle. I read the table of contents and the first chapter, which is primarily a crash course intro to C# and mostly covered concepts I already know. 

**Thoughts:** Since I didn't write a whole lot of code today, there's temptation to feel like the day was wasted. I'm fighting that feeling. I learned some new concepts, I learned about the existence of some IDEs, and I learned about a linux answer to C# called "Mono". The importan thing is that _I LEARNED_ today. This book covers some really cool projects and teaches ways to automate some security testing, which I know I will need to do in my career. I'm stoked to read more of it.

**Link(s):**
* [Gray Hat C# (No Starch Press)](https://nostarch.com/grayhatcsharp)

<hr />

### Day 3: January 3, 2019
#### _Improving The Basics_

**Today's Progress:** I completed module 5: _Accessing and using classes_ in the Pluralsight course _C# Best Practices: Improving on the Basics_, taught by Deborah Kurata.

**Thoughts:** This was challenging. I need to get back to **writing** code tomorrow and hopefully find some way to practice the many concepts that were covered in this module. Topics like initialization, instantiating, null checking, and the various ways to assign fields in classes, and the use cases for each.

**Link(s):**
* [Deborah Kurata on Twitter](https://twitter.com/DeborahKurata)
* [C# Best Practices: Improving on the Basics (Pluralsight)](https://app.pluralsight.com/library/courses/csharp-best-practices-improving-basics)

<hr />

### Days 4, 5, and 6: January 4-6, 2019

**Progress:** After giving it some thought, I finally came up with a good app to put the OOP skills I'm learning on pluralsight into practice. I created a github repo for an app to generate a character for 5th edition D&D and started coding it. 

**Thoughts:** Rough couple of days emotionally, normally I'd have made more progress than this but at least I took some time each day to actually code.**

**Link(s):**
* [FyVee](https://github.com/jgatka/FyVee)
* [Dungeons & Dragons](http://dnd.wizards.com/)

<hr />

### Days 7, 8, and 9: January 7-9, 2019

**Progress:** I added the properties for ability scores to the Hero class of FyVee. I also set up my work PC so that I'm able to make changes from there. Sometimes I prefer the well lit standing desk I have at work. Sometimes (it's rare) I prefer to code _without_ a cat on my lap.

**Thoughts:** The propfull snippit in visual studio is awesome. I've gotten the hang of adding properties to a class using this shortcut. The hero class now has ability scores (strength, constitution, wisdom, intelligence, dexterity, charisma) as well as languages, which will be selected from a list. I got a decent amount of practice with OOP and the basics over the last few days, which is rad.

**Link(s):**
* [FyVee](https://github.com/jgatka/FyVee)
* [Dungeons & Dragons](http://dnd.wizards.com/)

<hr />

### Days 10-20, January 10-20, 2019

**Progress:** Added a list for languages in the FyVee App.

**Thoughts:** Got some news from my family about my grandfather's health that hit me hard. I'm also down to just 2 people on my team at work. This time last year we had 7. I thought about just abandoning this project and returning to 100 days of code later in the year, but that's not what my grandfather would want me to do, and it's not healthy or productive to completely start over when you get derailed or knocked off of your horse. Life isn't Tetris on NES. I'm just going to keep at it even though I've already failed the goal of 1hr of code per day. Life happens.

**Link(s):**
* [FyVee](https://github.com/jgatka/FyVee)
* [_The Not To Do List: 9 Habits to Stop Now_](https://tim.blog/2007/08/16/the-not-to-do-list-9-habits-to-stop-now/)

<hr />

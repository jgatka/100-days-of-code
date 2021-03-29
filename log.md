# 100 Days Of Code - Log
### Day 1: March 28th, 2021
#### Make the Deadfish swim

**Today's Progress:** Decided to complete a Codewars kata to get back to it.

**Thoughts:** Took me a minute to remember some simple python syntax I haven't used in awhile. Hopefully I won't ever take so long of a break from writing code as I did between fall and spring.

**Link(s) to Work:**
<em>My solution to "Make the Deadfish swim", a Codwars.com kata:</em>
```python3

# Instructions:
# 
# Write a simple parser that will parse and run Deadfish.
# 
# Deadfish has 4 commands, each 1 character long:
# 
# 	i increments the value (initially 0)
# 	d decrements the value
# 	s squares the value
# 	o outputs the value into the return array
# 
# Invalid characters should be ignored.

def parse(data):
    print('data: ' + data)
    count = 0
    array = []
    
    # Python3 program to Split string into characters
    def split(word):
        return [char for char in word]
    
    # calculate length of string
    length = len(data)
    print("data is " + str(length) + " character(s) long.")
    
    # split into chars
    chars = split(data)
    print("Chars in word: " + str(chars))
    
    # loop over the characters 
    for char in chars:
        if char == 'i':
            count += 1
        elif char == 'd':
            count -= 1
        elif char == 's':
            count = count ** 2
        elif char == 'o':
            array.append(count)
        else:
            continue
    
    return array
```
* [My profile on codewars.com](https://www.codewars.com/users/jgatka)

</ hr>

### Day 0: February 11th, 2021
#### <em>Navbar Tweaks</em>

**Today's Progress:** I added code to make the navbar menu items change colors when you hover over them. I also added a google font so that I can change the color of the title.

**Thoughts:** I thought about making the content of the page revolve around guitar tutorials, but the unit tests lend themselves towards a project similar to the one I forked off of. With that in mind, I've decided to make the page a Python tutorial. Not a bad way to ease back into my routine.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

## Start of a new 100 Days of Code

<hr />

###  Day 100 & Beyond: May 10th, 2020 - February 1st, 2021
#### <em>Passing The CISSP Exam</em>

**Today's Progress:** Since my last update last spring, I focused my attention on studying for the CISSP exam. I took the exam on January 5th, and passed. It was the hardest exam I've ever taken, and all of the time spent studying was necessary in order to pass it. All of the paperwork is done, my endorsement has been received, and now all that's left to do is wait for ISC2 and the post office to do their thing. Did I code? Of course, but mostly one-off projects for work.

**Thoughts:** Last week, 140 employees were let go at my former employer, in one massive unexpected layoff. The company had just celebrated a successful, profitable year, despite the pandemic. After I passed the CISSP exam, I told myself I'd focus on self-care and re-learning how to relax. The events of the last week served as a wake up call. My short-lived break is over. Most of the employees targeted in the layoffs were QA testers, and those that developed and maintained legacy products. Their jobs were either eliminated or outsourced to India and Poland. The cloud/automation reaper continues to accumulate casualties. My days as a security engineer will not last long enough for me to retire. One day, maybe 2 years from now, maybe 5 years from now, someone will invent some sort of blinky-box software that does my job about 33% as good as I do it, but will cost 66% less than my salary. And then I'll need to find a new job. That's why I need to start a new 100 days of code. That, and the same reasons I've always wanted to learn this. To build websites about things I'm passionate about, and possibly write my own app someday. I still have some projects to finish in the HTML & CSS course, and a some lessons to finish for the javascript data structures and algorithms course before I can start the projects and earn the certificate.

I don't mean to dwell on negativity. I have a lot to hang my hat on. I completed some C#/.NET coursework on pluralsight last year, and according to microsoft's skill's assessment I'm rated as "proficient". If there's one thing that I learned in 2020, it's that I've yet to defeat my imposter syndrome. I've been told that one way to combat it is with positive affirmations. Well, I'm a proficient C# developer, I'm a competent security engineer, and pending some work from ISC2 and USPS, I'm a CISSP.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* [My Profile on Pluralsight](https://app.pluralsight.com/profile/josh-gatka-f9)
* [Completed Codewars Solutions: jgatka](https://www.codewars.com/users/jgatka/completed)
* [How to Get Rich Sabotaging Nuclear Weapons Facilities by Matt Stoller](https://mattstoller.substack.com/p/how-to-get-rich-sabotaging-nuclear)

<hr />

### Days 94-99: May 4th-9th, 2020
#### <em>✅ Survey Form</em>


**Today's Progress:** I finished the survey form. 2 out of 5 final projects for the Responsive Web Design course are now finished.
**Thoughts:** They say perfect is the enemy of done, but I could only tolerate so much asymmetry before submitting this final project. Two problems that I needed to work through were:
* The order of the labels vs the inputs on both my radio buttons AND my checkboxes. Default is label then input, I wanted these switched.
* The alignment of the labels and inputs

I had to do a lot of googling and reading in order to figure out how to properly align the radio buttons, checkboxes, and their respective labels, and I'm still not 100% satisfied with the finished result. That said, I had to take a step back and re-examine my definition of done, something that I have to do all the time in the professional world. The page looks pretty cool objectively speaking, and it meets <u>all</u> of the requirements. All of the unit tests passed. So I'm moving on. Tomorrow is day 100, and I really want my responsive web design certification, even though I know it's going to take me beyond the 100 days in order to get it.

I put a lot of my childhood into this survey form. I made it about classic 80's/90's WWF/WCW professional wrestling. I'm proud of the way the form looks on top of the background that I found, and of the fact that I picked font styles that will look familiar to fans of what is now called...sigh..."Sports Entertainment". Have a look, page is linked below.

**Link(s) to Work:**
* [FCC: Survey Form](https://codepen.io/jgatka/pen/yLYJmjE)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 91-93: May 1st-3rd, 2020
#### <em>Dropdowns and Radio Buttons</em>

**Today's Progress**: I worked more on the survey form. The dropdown menu is complete, but I'm having trouble getting my labels to align with their respective radio buttons. Hoping to figure this out and fix it tomorrow.

**Thoughts:** I like that the final projects force you to fix the problems that arise due to your own design decisions and code. W3schools and stackoverflow have been my friends these last few days.

**Link(s) to Work:**
* [FCC: Survey Form](https://codepen.io/jgatka/pen/yLYJmjE)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 87-90: April 27th-30th
#### <em>Fun with Forms</em>

**Today's Progress:** I worked on the survey form site, and finally got the form stylized the way that I want it.

**Thoughts:** Part of me is mad at myself for being a perfectionist about these websites, but the other part of me is treating them like artifacts for a future portfolio - they <em>must</em> be quality works.

**Link(s) to Work:**
* [FCC: Survey Form](https://codepen.io/jgatka/pen/yLYJmjE)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 86: April 26th, 2020
#### <em>✅Simple Pig Latin</em>

**Today's Progress:** I finished the Simple Pig Latin kata today. This is the first 5kyu kata that I've completed. I also put some work into my survey form project on freecodecamp.

**Thoughts:** I was able to figure out the missing piece of the pig latin kata by adding a single line of python. That was pretty cool. The form project is proving a bit more challenging. I want my page to look good, I'm treating my codepen page like a portfolio. I'm having trouble formatting my survey form to look good atop the background and beneath the title/description I've created. It's going to require me going back and digging into the tutorials to chronologically build the form in a way that is organized and appealing.

* [FCC: Survey Form](https://codepen.io/jgatka/pen/yLYJmjE)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* [Simple Pig Latin: A Codewars Kata](https://www.codewars.com/kata/520b9d2ad5c005041100000f)
* [Completed Codewars Solutions: jgatka](https://www.codewars.com/users/jgatka/completed)

<em>My solution for "Simple Pig Latin" - a codewars.com kata:</em>
```python3
def pig_it(text):
    solution_list = []
    solution = ""
    a = "a"
    y = "y"
    new_word = ""
    len_chars = 0
    punctuation_chars = ['.','?','!','¿','¡']
    words = list(text.split(' '))
    print("Words: " + str(words))
    for word in words:
        print("Word: " + word)
        chars = list(word)
        print("Chars: " + str(chars))
        first_char = chars[0]
        # Don't pig-latinize punctuation
        if first_char in punctuation_chars:
            new_word = ''.join(first_char)
            solution += (new_word + ' ')
        # Not a punctuation mark? Cool - pig-latinize it
        else:
            print("First char: " + str(chars[0]))
            chars.append(first_char)
            print("After append: " + str(chars))
            chars.pop(0)
            print("After pop: " + str(chars))
            chars.append(a)
            chars.append(y)
            print("After pig latinized: " + str(chars))
            new_word = ''.join(chars)
            solution += (new_word + ' ')
        
        
    # trim leading and trailing spaces
    solution = solution.strip()
    return solution
```

<hr />

### Day 83-85, April 23-25, 2020
#### <em>Simple Pig Latin</em>

**Today's Progress:** I worked on the codewars.com kata "simple pig latin". I also completed the C# module on "testing your code" and I put some work into my survey form page on freecodecamp. A busy, if not exclusively focused, couple of days.

**Thoughts:** I'm almost done with this kata, I just need to figure out a way to get the code to put the punctuation in the proper spot.

**Link(s) to Work:**
* [Simple Pig Latin: A Codewars Kata](https://www.codewars.com/kata/520b9d2ad5c005041100000f)
* [Unfinished Codewars Solutions: jgatka](https://www.codewars.com/users/jgatka/unfinished)
* [My Profile on Pluralsight](https://app.pluralsight.com/profile/josh-gatka-f9)
* [C# Fundamentals Course](https://app.pluralsight.com/library/courses/csharp-fundamentals-dev)
* [FCC: Survey Form](https://codepen.io/jgatka/pen/yLYJmjE)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 80-82, April 20th - 22nd, 2020
#### <em>C# Classes, Objects, Testing</em>

**Today's Progress:** I complted two modules in the C# Fundamentals course on Pluralsight. One on Classes & Objects, and a second module on testing your code. I also signed up for Portswigger.net's web security academy. Now that I have a Burp Suite Pro license I can return to serious study of web app pentesting. Conntinuing to learn how to break as I learn how to build.

**Thoughts:** I am tired today. Keep on keeping on. Some of the C# OOP stuff doesn't make sense yet. I've been here before. For me at least, some of this will have to "click" while I'm actually writing code instead of studying how to write it. I can't wait to jump back into the FCC.org stuff and finish my projects.

**Link(s) to Work:**
* [My Profile on Pluralsight](https://app.pluralsight.com/profile/josh-gatka-f9)
* [C# Fundamentals Course](https://app.pluralsight.com/library/courses/csharp-fundamentals-dev)

<hr />

### Day 79, April 19th, 2020
#### <em>Survey Form</em>

**Today's Progress:** Today I started working on the survey form project. I forked the code which will allow for me to run unit tests, began creating the CSS properties, and stylized some fonts.

**Thoughts:** I have a few ideas for what I want to do with the survey...possibly a guitar survey or survey about my band's first song, but  haven't decided for sure yet. It has to be fun to keep me engaged.

**Link(s) to Work:**
* [FCC: Survey Form](https://codepen.io/jgatka/pen/yLYJmjE)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 77-78, April 17th-18th, 2020
#### <em>✅C# Syntax</em>

**Today's Progress:** Today I completed the Syntax module on the Pluralsight course on C# Fundamentals, taught by Scott Allen.

**Thoughts:** I'm starting to feel like I'm working on too many learning domains at once, so I may need to spend a day or week focused on plowing through the remainder of the freecodecamp projects, and putting aside the codewars and pluralsight. Or not 🤷‍♂️.

**Link(s) to Work:**
* [My Profile on Pluralsight](https://app.pluralsight.com/profile/josh-gatka-f9)
* [C# Fundamentals Course](https://app.pluralsight.com/library/courses/csharp-fundamentals-dev)

<hr />

### Day 76, April 16th, 2020
#### <em>✅ Tribute Page</em>

**Today's Progress:** Today I completed my tribute web page to Kurt Cobain. The project passed all tests and looks pretty good if I do say so myself.

**Thoughts:** One project down, 4 to go!

**Link(s) to Work:**
* [FCC: Tribute Page - Kurt Cobain](https://codepen.io/jgatka/pen/dyYPVaP)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 75, April 15th, 2020
#### <em>9/10 Ain't Bad</em>

**Today's Progress:** I worked on the tribute page today. I've passed 9 out of the 10 unit tests for the page. Tomorrow I'll focus on fixing the formatting of the div element that's causing the final test to fail.

**Thoughts:** It's still strange to look at this page that I've created. I'm really proud of it. My days of taking shots in the dark and trying to format my MySpace page using copied and pasted HTML are long behind me.

**Link(s) to Work:**
* [FCC: Tribute Page - Kurt Cobain](https://codepen.io/jgatka/pen/dyYPVaP)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 74, April 14th, 2020
#### <em>Tribute Page</em>

**Today's Progress:** I worked on my tribute page project today. All of the elements have been added and all that's left to do is to ensure that the adaptive design is in place.

**Thoughts:** I find myself working on the look and feel of the page instead of just blindly chasing the requirements. I'm having fun.

**Link(s) to Work:**
* [FCC: Tribute Page - Kurt Cobain](https://codepen.io/jgatka/pen/dyYPVaP)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 73, April 13th, 2020
#### <em>Gradebook</em>

**Today's Progress:** I put in some work on the tribute page today, and I uploaded the gradebook program that is part of the C# course to github, so that I can work on it at home and push changes to the main repo using my personal github account. This required me to create a repo, push my local directory to the repo, use my work account to send my personal account an invite to collaborate, accept the invite using my personal account and then clone the repo to my home PC.

**Thoughts:** I guess I learned more about github today then I did about HTML/CSS/Python/C# - I suppose it's important to be well rounded though 🤔

**Link(s) to Work:**
* [FCC: Tribute Page - Kurt Cobain](https://codepen.io/jgatka/pen/dyYPVaP)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 70-72, April 10th-12th, 2020
#### <em>Tribute Page Project</em>

**Today's Progress:** For the past three days, all of my coding work has been focused on the first of the final projects, designing a tribute page.

**Thoughts:** I've been fascinated with the life and art of Kurt Cobain for awhile, so I decided to make my tribute page about him. I'm having an absolute blast doing this. I picked fonts that look like the Nirvana logo and Kurt's handwriting (I've read his journals, that have been published), and I picked a color schema that reminiscent of Nirvana t-shirts that I've seen. The site looks great so far, I'm just working through all of the requirements now.

**Link(s) to Work:**
* [FCC: Tribute Page - Kurt Cobain](https://codepen.io/jgatka/pen/dyYPVaP)
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 68 & 69, April 86th  9th, 2020
#### <em>Return to Pluralsight & C#</em>

**Today's Progress:** I'm back to working for an employer that provides pluralsight access as a perk of working there. I'm so grateful. Today I installed .NET Core and Visual Studio Code on my work laptop and my home PC. From there I started the C# Fundamentals course and completed 13% of it.

**Thoughts:** Scott Allen is a great professor. Years ago I completed a C# course he taught on <em>Microsoft Virtual Academy</em>, which was free. I also completed his C# Fundamentals with Visual Studio course on Pluralsight years ago when I had pluralsight at my previous employer. I'm sure that this course will be largely a review, but I don't care. I could use the review, and I want to climb the C# learning path. I want to be at the level of a junior developer, so that I can write and recommend secure code in addition to just being able to read and review it. I really like C#, and I'm so happy to be back to writing it.

**Link(s) to Work:**
* [My Profile on Pluralsight](https://app.pluralsight.com/profile/josh-gatka-f9)
* [C# Fundamentals Course](https://app.pluralsight.com/library/courses/csharp-fundamentals-dev)

<hr />

### Day 66 & 67, April 6th & 7th, 2020
#### <em>CSS Grid</em>

**Today's Progress:** I finished the remainder of the tutorials in the CSS Grid portion of the freecodecamp.org course on responsive web design. All that's left to do for the certification is the final projects!

* Create Grids within Grids
* Use Media Queries to Create Responsive Layouts
* Create Flexible Layouts Using auto-fit

**Thoughts:** YAY FINAL PROJECTS TIME!

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 65, April 5th, 2020
#### <em> Repeat, Minmax, Auto-fill</em>

**Today's Progress:** Today I completed 3 tutorials in the CSS Grid portion of the freecodecamp.org course on responsive web design. There are only 3 exercises remaining, followed by 5 final projects.

* Create Flexible Layouts Using auto-fill
* Limit Item Size Using the minmax Function
* Reduce Repetition Using the repeat Function

**Thoughts:** The ability to use repeat, minmax, and auto-fill to keep a page looking consistent at any size/screen is pretty neat.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 64, April 4th, 2020
#### <em>✅ 6kyu</em>

**Today's Progress:** I completed my final unfinished 7kyu kata on codewars.com and advanced to 6kyu. 

**Thoughts:** I'm happy to have finally advanced to 6kyu. I even introduced two friends to the site and now they are my "allies". I look forward to the increased difficulty of the 6kyu challenges.

**Link(s) to Work:**
* [Completed Solutions: Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)
* [Isograms: A codewars.com Kata](https://www.codewars.com/kata/54ba84be607a92aa900000f1)

<em>My solution for "Isograms", a codewars.com kata:</em>
```python3

def is_isogram(string):
    solution = True
    list_chars = list(string.lower())
    print("List f chars: ")
    print(list_chars)
    for char in list_chars:
        solution = True
        if list_chars.count(char) >= 2:
            solution = False
            return solution
        else:
            solution = True
            
    return solution
```

<hr />

### Day 63, April 2nd, 2020
#### <em> ✅ 7kyu coding session</em>

**Today's Progress:** I wanted a break from freecodecamp, so I knocked out three 7kyu katas on codewars.com

* List FIltering
* Ones and Zeros
* Number of People in the Bus

**Thoughts:** I now have a pretty good body of proof that I've upgraded my python development skills. I went back to my list of incomplete katas, hoping to knock out every 7kyu one that was left. I now have only one left (_Isograms_). I like that <em>Ones and Zeroes</em> made me combine my networking knowledge with my programming knowledge. It was the first time I had to calculate base 2 numbers in a long time. Excited to finish the last 7kyu kata, as well as the last few remaining tutorials in the freecodecamp course, so that I can begin work on the final projects.

**Link(s) to Work:**
* [Completed Solutions: Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)
* [List Filtering: Codewars.com](https://www.codewars.com/kata/53dbd5315a3c69eed20002dd)
* [Ones and Zeroes: codewars.com](https://www.codewars.com/kata/578553c3a1b8d5c40300037c)
* [Number of People in the Bus](https://www.codewars.com/kata/5648b12ce68d9daa6b000099)

<em>My solution for "List Filtering", a codewars.com kata:</em>
```python3
import sys, math, os
def filter_list(list):
    hits = []
    for item in list:
      if type(item) == str:
          print('[-] ' + item + ' not added to hit list!')    
      elif type(item) == int:
          print('[+] ' + str(item) + ' added to hit list!')
          hits.append(item)
      else:
          pass
    return hits  
```
<em>My solution for "Ones and Zeroes", a codewars.com kata:</em>
```python3
def binary_array_to_number(arr):
  # your code
  solution = 0
  power = 0
  for value in reversed(arr):
      solution += value*(2**power)
      power += 1
  
  return solution
```
<em>My solution for "Number of People in the Bus", a codewars.com kata:</em>
```python3
def number(bus_stops):
    # Good Luck!
    num_passengers = 0
    for stop in bus_stops:
        num_passengers += stop[0]
        num_passengers -= stop[1]
    return num_passengers
```

<hr />

### Day 62, April 1st, 2020
#### <em>More fun with grids</em>

**Today's Progress:** It's been an eventful week. I started at a new employer and my basement flooded. Onboarding and paperwork have kept me busy when cleaning up the flood damage hasn't. I returned to my regularly scheduled programming today (see what I did there?), and completed a few tutorials on freecodecamp. I also set up my new, work-provided pluralsight account so that I can return to the C# coursework that I had to step away from 13 months ago because I left the employer that was providing it for me.

* Use grid-area Without Creating an Areas Template
* Place Items in Grid Areas Using the grid-area Property
* Divide the Grid Into an Area Template
* Align All Items Vertically using align-items
* Align All Items Horizontally using justify-items
* Align an Item Vertically using align-self

**Thoughts:** It's been a really challenging week to keep at it, but on the bright side, I should be done with tutorials, and starting the projects this weekend. And I have a pluralsight license again, so I can finally return to learning C#/.NET!

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 59-61, March 25th-27th, 2020
#### ✅ Counting Duplicates

**Today's Progress:** After 3+ days of refactoring and trying different ways of going about solving the problem, I finally completed the <em>Counting Duplicates</em> kata on freecodewars.com. I also completed 3 tutorials in the <em>CSS Grid</em> chapter from freecodecamp.org

* Use grid-column to Control Spacing
* Use grid-row to Control Spacing
* Align an Item Horizontally using justify-self

**Thoughts:** This codewars kata was the most challenging one yet. I spent a lot of time trying to write code that would perform what I later found out is exactly what the 'set' method does. Figuring out that I could trim duplicates from a list simply by calling 'set' on it was a game changer. This was also the first time in a while that I built a dictionary, so it was nice to practice that skill again. My current rank on codewars is 7 kyu (white belt) but this was a 6 kyu kata and I'm 67% towards my 6 kyu (yellow belt). Each codewars user starts at 8 kyu and progresses to 1 kyu and then on to 1 dan (master) level. In case you haven't inferred this yet, the system is influenced by martial arts. From Codewars wiki on github:

<em>"Why the names Kyu and Dan? The terms are borrowed from a system in Japanese martial arts, which is in turn borrowed from the game of Go. Kyu (or Kyū) indicates the number of degrees away from master level (Dan). This is why they count downward. Once you reach master level, we count upward. Black belts in martial arts are Dan level."</em>

I continued to learn about how customizable columns, rows, cells, and their contents are in CSS as well. Freecodecamp.org is so rad.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* [Counting Duplicates - A codewars.com Kata](https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1)
* [Completed Solutions: Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)

<strong>Kata instructions for <em>Counting Duplicates:</em></strong>

Write a function that will return the count of distinct case-insensitive alphabetic characters and numeric digits that occur more than once in the input string. The input string can be assumed to contain only alphabets (both uppercase and lowercase) and numeric digits.
Example

"abcde" -> 0 # no characters repeats more than once
"aabbcde" -> 2 # 'a' and 'b'
"aabBcde" -> 2 # 'a' occurs twice and 'b' twice (`b` and `B`)
"indivisibility" -> 1 # 'i' occurs six times
"Indivisibilities" -> 2 # 'i' occurs seven times and 's' occurs twice
"aA11" -> 2 # 'a' and '1'
"ABBA" -> 2 # 'A' and 'B' each occur twice

<strong>My solution for the <em>Counting Duplicates</em> kata:</strong>

```python3
def duplicate_count(text):
    char_x_occurrences = {}
    char_is_dupe = False
    
    # number of characters that are duplicates
    num_dupes = 0
    
    # list of characters from the input string
    # Note that the text is first converted to lower case to avoid case errors
    list_of_chars = list(text.lower())
    
    # count the amount of characters in the list
    list_of_chars_count = len(list_of_chars)
    
    print('[-] There are ' + str(list_of_chars_count) + ' characters in ' + text + '.')
    print('[-] The characters in ' + text + ' are: ' + str(list_of_chars) + '.')
    
    ''' We need a working list. This list will be used 
    to count the amount of characters in the main list.
    since a set has no duplicate values, we will use it
    against text to get a working list with no duplicates
    '''
    working_list = []
    working_list = set(text)
    
    # I need to count the amount of times that each char appears in the list...
    for char in working_list:
        
        print('[-] Now checking, ' + '\'' + char + '\'...')
        
        # Add the char and the number of times it appears
        char_x_occurrences[char] = list_of_chars.count(char)
        print('[-]Number of occurrences of ' + str(char) + ': ' + str(char_x_occurrences[char]))
        if char_x_occurrences[char] > 1:
            char_is_dupe = True
        else:
            char_is_dupe = False
        
        
        # Report back to user
        print("[-] Chars & Occurrences: ")
        print(char_x_occurrences)
    
        if char_is_dupe == True:
            num_dupes +=1
    
    if num_dupes > 0:
        print('[+] there are ' + str(num_dupes) + ' characters that repeat')
    else:
        print('[-] there are ' + str(num_dupes) + ' characters that repeat')
    
    
    return(num_dupes)
```

<hr />

### Day 58, March 24th, 2020
#### <em>Grid Gap</em>

**Today's Progress:** I took a break from the Counting Duplicates kata and instead completed 4 tutorials in the <em>CSS Grid</em> chapter of freecodecamp.org

* Add Gaps Faster with grid-gap
* Create a Row Gap using grid-row-gap
* Create a Column Gap Using grid-column-gap
* Use CSS Grid units to Change the Size of Columns and Rows

**Thoughts:** Tonight I learned multiple was to space content out inside of a container, and I also learned how to create gaps of space in between rows and columns. 

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 56-57, March 22nd - 23rd, 2020
#### <em>CSS Grid</em>

**Today's Progress:** I've spent the past two days trying to solve the <em>Counting Duplicates</em> kata on <em>codewars.com</em> I have yet to solve it. I also started the <em>CSS Grid</em> chapter on <em>freecodecamp.org</em>, and completed 3 tutorials:

* Add Rows with grid-template-rows
* Add Columns with grid-template-columns
* Create Your First CSS Grid

**Thoughts:** I can tell I'm getting closer to the solution for the counting duplicates kata, but I think tomorrow I'm going to try going about it in a different way. I've been using lists in a way where it might make more sense to use a dictionary. I'll try that approach tomorrow. The CSS grid tutorials make sense so far. Just as with some of the earlier chapters, I'm surprised at how many ways there are to accomplish the same task in HTML/CSS.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* [Counting Duplicates - A codewars.com Kata](https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1)

<hr />

### Day 55, March 21st, 2020
#### <em>✅ CSS Flexbox</em>

**Today's Progress:** Tonight I completed the final two tutorials in the <em>CSS Flexbox</em> chapter of codewars.com. I also attempted to create a solution for the codewars.com kata <em>Counting Duplicates</em>, however, I haven't been successful at solving the kata (yet).

* Use the align-self Property
* Use the order Property to Rearrange Items

**Thoughts:** I'm finished with the CSS Flexbox chapter, the 22 tutorials of the CSS Grid chapter and the 5 Responsive Web Design projects are all that separate me from the <em>Responsive Web Design</em> certification!

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* [Counting Duplicates - A codewars.com Kata](https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1)

<hr />

### Day 54, March 19th, 2020
#### <em>✅ You're a Square!</em>

**Today's Progress:** I completed three tutorials on freecodecamp.org. tonight. I also completed the codewars.com kata <em>You're a Square</em>.

* Use the flex Shorthand Property
* Use the flex-basis Property to Set the Initial Size of an Item
* Use the flex-grow Property to Expand Items

**Thoughts:** COVID-19 is causing me to stay indoors indefinitely. After some research, it turns out I was overthinking the perfect squares kata. I overthink sometimes. the python "math" library is powerful, and using the math.sqrt method saved me a lot of steps. The challenge after that became using int and adding 0.5 to integers to round to the appropriate value. I'm glad I finally have this kata removed from my "unfinshed" list on codewars.com.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* [Completed Solutions: Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)

<em>My Solution to [You're a Square](https://www.codewars.com/kata/54c27a33fb7da0db0100040e):</em>
```python3
def is_square(n):    
    
    # negative numbers cannot be square numbers
    if (int(n) < 0):
        return False
    
    if (int(n) == 0):
        return True
    
    import math
    # calculate the square root of the number
    sq_root = int(math.sqrt(n))
    
    # if the square root squared equals the number, than the number is a perfect square.
    # using int and adding .5 will round so that large integers will still make this calculation correctly.
    if (int(sq_root + 0.5) ** 2) == n:
        return True
    else:
        return False
```

<hr />

### Day 53, March 18th, 2020
#### <em>Flex-shrink, Flex-wrap, and more Align-items</em>

**Today's Progress:** I completed three tutorials in freecodecamp.org tonight:

* Use the flex-shrink Property to Shrink Items
* Use the flex-wrap Property to Wrap a Row or Column
* Use the align-items Property in the Tweet Embed

**Thoughts:** As the demo pages on freecodecamp get more complex, I'm enjoying seeing the granularity of control that a developer can have over the presentation of graphics and elements. It's been tough to focus amidst all of the COVID-19 chaos, but I'm doing what I can.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 52, March 16th, 2020
#### <em>Justify-content & Align-items</em>

**Today's Progress:** I completed three tutorials on the freecodecamp.org chapter on CSS Flexbox today:

* Align Elements Using the justify-content Property
* Use the justify-content Property in the Tweet Embed
* Align Elements Using the align-items Property

**Thoughts:** I had no idea there are so many options for aligning content in rows/columns in CSS. It's interesting that there is are sort of absolute x and y axises and relative ones available for the developer to position content along.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 51, March 15th, 2020
#### <em>flex-direction</em>

**Today's Progress:** I completed three tutorials in the CSS Flexbox chapter on _freecodecamp.org_:

* Apply the flex-direction Property to Create Rows in the Tweet Embed
* Use the flex-direction Property to Make a Column
* Apply the flex-direction Property to Create a Column in the Tweet Embed

**Thoughts:** It's difficult to stay focused with all of the corona virus hype, but it was nice to see how easy it is to get a site to adapt based on whether the developer wants it to be aligned by column or by row.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 50, March 11th, 2020
#### <em>Introduction to the CSS Flexbox Challenges</em>

**Today's Progress:** I started the CSS Flexbox Challenges Chapter of freecodecamp.org and completed three tutorials:

* Use display: flex to Position Two Boxes
* Add Flex Superpowers to the Tweet Embed
* Use the flex-direction Property to Make a Row

**Thoughts:** I'm not quite sure I understand how this works, but tonight's challenge were focused around adding the "display: flex;" property to elements. Hopefully as I configure more values in the future this will "click" in my head.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 49, March 10th, 2020
#### ✅<em>Responsive Web Design Principles</em>

**Today's Progress:** Since the <em>Responsive Web Design Principles</em> chapter was only four tutorials long, I just went ahead and knocked it out over the course of an hour or so. I learned:

* Introduction to the Responsive Web Design Challenges
* Create a Media Query
* Make an Image Responsive
* Use a Retina Image for Higher Resolution Displays
* Make Typography Responsive

**Thoughts:** Changing the dimensions of elements to conform to the screen that they are on was a lot less complex than I thought it would be. CSS has a few features to simplify this process, and I'm glad that I was able to play around with these features tonight.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 48, March 8th, 2020
#### ✅<em>WeIrD StRiNg CaSe</em>

**Today's Progress:** I completed the codewars.com kata "<em>"WeIrD StRiNg CaSe"</em>" today. Completing the kata ranked me up to 7kyu in Python on codewars.com. The instructions for the challenge were as follows:

<em>
Write a function toWeirdCase (weirdcase in Ruby) that accepts a string, and returns the same string with all even indexed characters in each word upper cased, and all odd indexed characters in each word lower cased. The indexing just explained is zero based, so the zero-ith index is even, therefore that character should be upper cased.

The passed in string will only consist of alphabetical characters and spaces(' '). Spaces will only be present if there are multiple words. Words will be separated by a single space(' ').
Examples:
</em>
```
to_weird_case('String'); # => returns 'StRiNg'
to_weird_case('Weird string case') # => returns 'WeIrD StRiNg CaSe'
```

**Thoughts:** I told myself that I would come back and complete at least one of the incomplete codewars.com katas that I had left unfinished. This one took some time to work out, but I finally figured out a solution (below).It was awesome to watch the solution pass all of its unit tests. I spent more time debugging than I did writing out the initial draft. Coming back to this kata after stepping away from it for so many days was difficult. Feeling pretty good today.

**Link(s) to Work:**
* [My Solutions - codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)
* ["WeIrD StRiNg CaSe" - Codewars.com](https://www.codewars.com/kata/52b757663a95b11b3d00062d)

<em>My solution to the codewars.com kata "WeIrD StRiNg CaSe":</em>
```python3
def to_weird_case(string):
    
    word_count=0
    word_chars=[]
    word_length=0
    count=0
    recased_word = ''
    recased_words=[]
    recased_words_length=0
    solution = ''
    
    
    # Split the string into individual words
    words = string.split(' ')
    word_count = len(words)
    
    
    # For each word, split the word into individual characters
    for word in words:
        count = 0
        word_chars = list(word)
        word_length = len(word)
        
        if word_count > 0:
            word_length = len(word)
        
        # iterate through each character
            while count < word_length:
            
                # if index is even
                if count % 2 == 0:
                    recased_word += str(word_chars[count].upper())

                # if index is odd
                elif count % 2 != 0:
                    recased_word += str(word_chars[count].lower())
                # if it's the last char, add the completed word to the list of recased words, then clear the recased word value for the next word.
                if count == (word_length -1):
                    recased_words.append(recased_word)
                    recased_word = ''
                
                # Regardless of even or odd...iterate
                count += 1
    
    # reset the count variable to 0
    count = 0
    
    # count the number of recased words
    recased_words_length = len(recased_words)
    
    # Add the recased words to the solution.
    for recased_word in recased_words:
        solution += recased_word
        count += 1
        # unless it's the last word, add a space
        if count != (recased_words_length):
            solution += ' '
    
    #return the solution
    return(solution)
```

<hr />

### Day 47, March 7th, 2020
#### ✅ _Applied_ _Accessibility_

**Today's Progress:** I completed the final three exercises in the <em>Applied Accessibility</em> chapter on freecodecamp.org:

* Give Links Meaning by Using Descriptive Link Text
* Make Links Navigable with HTML Access Keys
* Use tabindex to Add Keyboard Focus to an Element
* Use tabindex to Specify the Order of Keyboard Focus for Several Elements

**Thoughts:**  I learned a lot from this chapter, almost all of the tags, elements, and features I learned about were new for me. I now have an idea about the HTML5 and CSS features that are available to web developers to make their content accessible to users with disabilities and impairments. One thing that I wish that they had done was to have the user create a page and then be forced to navigate it using a screenreader or in a simulated colorblindness. I plan on remembering to do this test on my own at the end of the responsive web design class even if it's not one that is mandatory and alredy incorporated into the curriculum. 

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 46, March 5th, 2020
#### <em>Colorblind Awareness</em>

**Today's Progress:** I completed 3 exercises in the freecodecamp.org chapter on Applied Accessibility Awareness.

* Improve Readability with High Contrast Text
* Avoid Colorblindness Issues by Using Sufficient Contrast
* Avoid Colorblindness Issues by Carefully Choosing Colors that Convey Information

**Thoughts:** As someone whose colorblindness disqualified him from the Air Force gig he wanted (Fire Control Officer on an AC-130), I really enjoyed learning how easy it is to accomodate colorblind users when you test to ensure that the 4.5:1 contrast ratio is being applied on the elements of the page. Very, very cool. I also really like how freecodecamp.org keeps these lessons witty with their lessons on Camper the ninja cat. Getting close to the end of the applied accessibility chapter.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 45, March 4th, 2020
#### _Date & Datetime_

**Today's Progress:** Today I completed two tutorials in freecodecamp.org, covering the date and datetime input types:

* Add an Accessible Date Picker
* Standardize Times with the HTML5 datetime Attribute

**Thoughts:** I took two days off because I've been feeling under the weather. I'm disappointed but I know that I needed to do it. Tonight's tutorials covered more HTML5 topics that I was previously unaware of. Seeing the expected date format automatically populate an input text box as soon as the input type tag was added, was really cool.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 43 & 44, February 29th - March 1st, 2020
#### _Figure, Label, and Fieldset_

**Today's Progress:** Yesterday and today I attempted to spend some time creating a solution for the "WeIrD StRiNg CaSe" kata, but haven't successfully developed a solution yet. I hope to come back to it this week. I also still have the unsolved "Perfect Squares" kata to finish as well. I'm hoping to finish both of those next weekend before I attempt a separate one. I don't want to have a big backlog of unsolved katas. I also finished 3 tutorials in the freecodecamp.org chapter on <em>Applied Accessibility</em>:

* Improve Chart Accessibility with the figure Element
* Improve Form Field Accessibility with the label Element
* Wrap Radio Buttons in a fieldset Element for Better Accessibility

**Thoughts:** It is interesting to note how many elements of websites are typically encapsulated in a "div" tag, making it hard for users with disabilities to discern specifics and context from elements like radio buttons and charts. Today begins a new month in my #100daysofcode journey. I'm happy with the progress I've been making despite the other obligations I have in my life. I think that I'll be able to reach my goal of being the equivalent of a junior developer by 2021.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* ["WeIrD StRiNg CaSe" - Codewars.com](https://www.codewars.com/kata/52b757663a95b11b3d00062d)

<hr />

### Days 41 & 42, February 27th-28th, 2020
#### _Nav, Footer, and Audio_

**Today's Progress:** Yesterday I did some coding for work, but as before I'm choosing not to elaborate further. Today, I completed 3 exercises in the <em>Applied Accessibility</em> chapter of freecodecamp.org:

* Make Screen Reader Navigation Easier with the nav Landmark
* Make Screen Reader Navigation Easier with the footer Landmark
* Improve Accessibility of Audio Content with the audio Element

**Thoughts:** These tags/features of HTML5 are all brand new to me. My first thought is that it is so cool that adding audio controls is as easy as ensuring that the "controls" element is added to the "audio" tag. In this way, a sound clip can include a play and pause button. I think it's really, really cool that freecodecamp put the spotlight on Florian Beijers (@zersiax). Florian is a web developer that is passionate about accessibility and screen readers. RAD! Maybe one day I'll be featured as a web developer that is passionate about application security in a lesson.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 40, February 26th, 2020
#### _Main, Article, Header_

**Today's Progress:** I completed 3 exercises in the <em>Applied Accessibility</em> chapter of freecodecamp.org:

* Jump Straight to the Content Using the main Element
* Wrap Content in the article Element
* Make Screen Reader Navigation Easier with the header Landmark

**Thoughts:** I did not realize the importance of using main, article, and header to keep the page logically organized for individuals with disabilities. I think that learning the contextual differences between section and article will take practice, but otherwise I think that I have a pretty good handle on the correct uses of the three tags I studied tonight.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Days 38 & 39, February 24th - 25th, 2020
#### _Accessibility_

**Today's Progress:** I did some coding yesterday for work, but I'm not at liberty to elaborate. Today I completed the first three exercises in the <em>Applied Accessibility</em> chapter of freecodecamp.org:

* Add a Text Alternative to Images for Visually Impaired Accessibility
* Know When Alt Text Should be Left Blank
* Use Headings to Show Hierarchical Relationships of Content

**Thoughts:** I have used alt="" codes on images on websites before, but the second two exercises included lessons that are new to me. I did not realize that there is an accessibility use case for using an empty attribute. I also did not realize that using headings in a way that does not follow a logical order can be frustrating to users with disabilities. I feel privileged to learn about this perspective as I'm working through the tutorials/exercises.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 37: February 23rd, 2020
#### ✅ _Split Strings_

**Today's Progress:** My band had a show yesterday, and I wasn't able to make time to code. I resumed coding today. Rather than try to complete the previously attempted (and still not solved) _Perfect_ _Squares_ kata on codewars.com, I decided to try a new one: _Split_ _Strings_:

```python
'''
Complete the solution so that it splits the string into pairs of two characters. If the string contains an odd number of characters then it should replace the missing second character of the final pair with an underscore ('_').

Examples:

solution('abc') # should return ['ab', 'c_']
solution('abcdef') # should return ['ab', 'cd', 'ef']
'''
```

My solution (_worked, I passed the kata_):
```python
def solution(s):
    s_chars = list(s)
    s_length = len(s)
    string_pairs = []
    count = 0
    
    # if even
    if s_length % 2 == 0:
        # code
        while count < s_length:
            string_pairs.append(s_chars[count] + s_chars[count+1])
            count += 2
        
    # if odd
    elif s_length % 2 != 0:
        while count <= (s_length):
            if count < s_length and count != (s_length-1):
                string_pairs.append(s_chars[count] + s_chars[count+1])
                count += 2
            elif count == (s_length - 1):
                string_pairs.append(s_chars[count] + '_')
                count += 2
                
            else:
                count+=2
        
    # if neither even nor odd (shouldn't happen)
    else:
        print("Error!")
      
    return string_pairs
```

**Thoughts:** This one took me an hour to complete. Tweaking the algorithm to make the correct addition to the list when you are on the last character was the most most challenging part. That part took 45 minutes to work out, while the rest of the code I whipped up in about 15 minutes.

**Link(s) to Work:**
* ["Split Strings" - Codewars.com](https://www.codewars.com/kata/515de9ae9dcfc28eb6000001)
* [My Completed Solutions - Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)

<hr />

### Day 36: February 21st, 2020
#### ✅ _Applied Visual Design_

**Today's Progress:** I completed the final two exercises on the freecodecamp.org chapter _Applied_ _Visual_ _Design_:

* Use a Bezier Curve to Move a Graphic
* Make Motion More Natural Using a Bezier Curve

I learned how to move multiple graphics at varying rates. I used this to animate three colored balls in such a way that made them look like they were being juggled.

**Thoughts:** I'm happy to have completed another chapter. As of tonight I've completed three chapters of freecodecamp:

* Basic HTML and HTML5
* Basic CSS
* Applied Visual Design 

I'm excited to start the Applied Accessibility chapter. At one point in my career, I was working on a Security and Compliance team, and one of our team members was doing a great job of increasing accessibility awareness inside of the company. I learned a lot about how persons with disabilities and impairments navigate websites and apps. I'm stoked to learn how to include accessibility into my own code for a change.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 35: February 20th, 2020
#### _Variable Rates, Timing, and Bezier Curves_

**Today's Progress:** I completed three exercises on freecodecamp tonight:

* Animate Multiple Elements at Variable Rates
* Change Animation Timing with Keywords
* Learn How Bezier Curves Work

I learned how to change the rate of movement of animated elements, using the _ease_, _ease-in_, _ease-out_, and _linear_ values. I also learned how to customize the rate of movement across/down an axis using the _bezier- curve(x1, x2, y1, y2)_ syntax.

**Thoughts:** Customizing the animations is having me wonder what kind of animations I'll put on my own page. Only 2 more exercises left in the Applied Visual Design chapter of the course!

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 34: February 19th, 2020
#### _Inifinte Animations_

**Today's Progress:** I completed two exercises on freecodecamp tonight. I modified the _keyframes_ to make a heartbeat animation continuous, I then animated elements at variable rates so that two similar elements (in this case, stars) can appear to move at different rates/times.

**Thoughts:** It's especially tough to get my coding in on nights after band practice. I can't wait to play with some of these animation values though. Tonight's exercises reminded me a lot of the types of animations on one of my favorite websites, duolingo.com.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 33: February 18th, 2020
#### _Even more animation_

**Today's Progress:** I completed three exercises on freecodecamp tonight. I used _keyframes_ to move an element from left to right, then I changed the opacity of a ball as it moved from left to right, making it fade out, and then finally I set a ball to bounce infinitely.

**Thoughts:** I missed a day yesterday. Nobody is perfect I suppose. Creating and configuring animations has been great. I've never done anything like it previously. I've been brainstorming what kinds of animations to put into my projects. I may make try to create a metronome on my webpage that takes a BPM value and pulsates/beeps accordingly, coded using animations.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 32: February 16th, 2020
#### _More animation_

**Today's Progress:** I completed two exercises on freecodecamp. Today's lessons dealt with using keyframes to configure animations. I configured a button so that it would change background color when a user hovers over it. I then used the <em>animation-fill-mode: forwards;</em> parameter to configure the animation so that the color would remain changed for as long as the user is hovering over it.

**Thoughts:** I stopped working on the perfect squares codewars exercise for a day. I hope to return to it tomorrow. Thus far my python code has been written in vim or notepad++. I'm contemplating installing an IDE so that more serious debugging can take place, either pycharm or, more likely, visual studio code. Either way, it felt good to get the dopamine hit from completing some exercises again, and I'm glad I was able to make some forward progress today.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 30-31: February 14th & 15th, 2020
#### _Still Stumped_

**Today's Progress:** I spent a few more hours refactoring my code for the _You're_ _a_ _Square_ exercise on Codewars. My code is still not passing all unit tests. Some of the higher integer numbers are still returning incorrectly. I'll have to continue on this one.

**Thoughts:** I started my code from scratch after reading [this](https://www.quora.com/What-is-the-quickest-way-to-determine-if-a-number-is-a-perfect-square?share=1) quora thread. But it doesn't appear that the theory covers all perfect squares. At the very least, I count this as forward progress because it isn't timing out anymore like it did at last attempt.

**Link(s) to Work:**
* ["You're a Square!" - Codewars.com](https://www.codewars.com/kata/54c27a33fb7da0db0100040e/train/python)
* [My Completed Solutions - Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)

<em>My (still incomplete) solution to the codewars.com kata "You're a Square!":</em>

```python
def is_square(n):    
    
    '''
    # An efficient way to determine whether or not a number is a perfect square
    # is to evaluate whether or not it satisfies both of the following 
    # conditions: 
    # 1) A perfect square will always end in one of the following integers: 
    # ( 0, 1, 4, 5, 6, 9). A number that does not end in one of these numbers 
    # is not a perfect square. Numbers that satisfy this requirement can be 
    # tested for the second requirement:
    # 2) A Perfect Square always have digital summation of one of these 
    # numbers: ( 1, 4, 7, 9), if it doesn’t it’s not a Perfect Square. Note
    # that "digital summation" means adding the digits up and repeating the
    # operation until there is only one digit. That digit must be either 1, 4,
    # 7 or 9. Otherwise, the number is not a perfect suqare.
    # 
    '''
    
    # Zero is a perfect square
    if n == 0:
        return True
    
    # Negative numbers cannot be perfect squares
    if n < 0:
        return False 
    
    # Exception handling/input validation test to verify that n is an integer
    try:
        val = int(n)
    except ValueError:
        print("The number provided must be an integer")
    
    # Create a list to store each of the digits in
    digits_of_n = []
    
    # first test numbers
    first_test_numbers = [0,1,4,5,6,9]
    
    # second test numbers
    second_test_numbers = [1,4,7,9]
    
    # second test single digit fail numbers
    second_test_fails = [0,2,3,5,6,8]
    
    # split n into digits and add them to the list
    digits_of_n = [int(i) for i in str(n)]
    
    # digital summation needs to start at a number > 1 in order for the loop to
    # start. The number will be reset inside of the loop.
    digital_summation = 2
    
    # Generic error message
    error_message = "Error! Could not determine if the number is a perfect square."
    
    # First test...does n end in 0, 1, 4, 5, 6, or 9?
    if digits_of_n[-1] in first_test_numbers:
        # Perform second test
        
        # Add all of the digits up
        digital_summation = sum(digits_of_n)
        
        # If the sum is in the list of second test numbers, return true
        if (digital_summation in second_test_numbers):
            return True
        
        # Otherwise, one of two things has happened, 1) The number is either in 
		#(2,3,5,6,8), or 2) The number is > 9, and digital summation will need 
		# to take place again.
        else:
            # if the digital summation is either 0, 2, 3, 5, 6, or 8 - return 
			# False
            if (digital_summation in second_test_fails):
                return False
            
            # integer is double digits...we'll need to repeat digital 
			# summation until it isn't.
            elif digital_summation > 9:
                while digital_summation > 9:
                    # split up the digits again
                    digits_of_n = [int(j) for j in str(digital_summation)]
                    # add digits again
                    digital_summation = sum(digits_of_n)
                    
                    # If the new sum is in the fail case numbers, return false
                    if digital_summation in second_test_fails:
                        return False
                    
                    # If the new sum is in the success cases list, return true
                    elif digital_summation in second_test_numbers:
                        return True
                    
                    # if the new sum is still more than 1 digit, continue the 
					# loop
                    elif digital_summation > 9:
                        continue
                    
                    # This should never happen, but it's here for proper 
					# exception handling.
                    else:
                        # Raise an exception and break out
                        print(error_message)
                        break
            
            # else...thie shouldn't happen...raise an exception and break out
            else:
                print(error_message)
                return False
                
            
        
    else:
        # n did not pass the first test.
        return False
```

### Day 29-30: February 12th & 13th, 2020
#### _Stumped_

**Today's Progress:** Yesterday I was feeling pretty exhausted after a long road trip. So I opted to break out some old reading for a bit in bed, and revisited 24 deadly sins of software security. I'm counting it, because it's better than doing nothing. Today I completed one freecodecamp exercise, _Learn How the CSS @keyframes and animation Properties Work_. I animated a rectangular graphic in such a way that it morphed between colors 3 times over the course of 4 seconds. I also made an attempt at completed the codewars.com kata "You're a Square" - but was unable to create a solution that passed (yet).

**Thoughts:** I actually think it's rad that my codewars.com solution to the kata is incomplete. My solution passed the few unit tests that are provided, but somewhere in the larger battery of use cases, one such use case causes the code to time out. This goes to show how incomplete some simple unit tests can be, something I have concerns about due to my AppSec background. I have a feeling I know why the solution isn't complete though. Somewhere in the numbers that are tested is no doubt a huge number (bigint?)...and the amount of time that it takes for my code to decrement across all numbers between that number and zero is probably too long, causing the timeout. I'm going to have to revisit my logic and try to find a more efficient way to narrow down potential solutions. I'm happy that I was able to complete an exercise in the freecodecamp curriculum though, and get my code dopamine hit for the night.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* ["You're a Square!" - Codewars.com](https://www.codewars.com/kata/54c27a33fb7da0db0100040e/train/python)
* [My Completed Solutions - Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)

<em>My (incomplete) solution to the codewars.com kata "You're a Square!":</em>

```python
def is_square(n):    
    
    if n < 0:
        return False 
    
    # Count backwards from n towards 0
    num_before_n = n
    while ((num_before_n <= n) and (num_before_n >= 0)):
        if ((num_before_n * num_before_n) == n):
            return True
        else:
            num_before_n -= 1
            continue
    
    # If none of the integers before n, that are greater than zero, times themselves == n, n is not a square
    return False
```

<hr />

### Day 28: February 11th, 2020
#### _Lucky Charms_

**Today's Progress:** Today I attempted a codewars kata and couldn't quite figure it out. It's late and my looping logic has a bug in it somewhere. I'll return to it tomorrow. I also completed two exercises in the freecodecamp chapter on applied visual design. The chapter is now 75% complete. These exercises had me create a crescent moon and a heart using CSS 

**Thoughts:** I thought it was kind of cool to learn how to create a heart just in time for valentines day. the ::before and ::after pseudo-elements are new to me. I'll need some practice manipulating these in such a way that it creates familiar shapes. Looking forward to practicing with these during the final projects.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 27: February 10th, 2020
#### _Sneaky sneaky_

**Today's Progress:** Today I created a phishing email to be sent out to a nonzero number of employees using HTML and CSS as part of my responsibilities at work. In the immortal words of Forrest Gump: "...And that's all I have to say about that."

**Thoughts:** I love InfoSec, but there are times, like right now, where I wish I could be more verbose about the work that I do.

**Link(s) to Work:**
* <strike>Redacted</strike>

<hr />

### Day 26: Febrary 9th, 2020
#### _Lists of Lists, SkewX, SkewY_

**Today's Progress**: I completed another Python Codewars exercise. This one called for me to return a result based on an evaluation of 2 integers that resided inside of a list of lists. I'm happy that I was able to code a solution as quickly as I did. I also completed two more exercises in the freecodecamp applied visual design unit. I learned how to skew an element along its X or Y axis using the <em>Transform: skewX(xdeg);</em> and <em>Transform: skewY(ydeg);</em> properties.

**Thoughts**: I've completed 37 of the 52 exercises of the applied visual design unit. The next unit will cover applied accessibilty. Looking forward to it. I'm also looking forward to the increase in difficulty in codewars exercises.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* ["Categorize New Member" - Codewars.com](https://www.codewars.com/kata/5502c9e7b3216ec63c0001aa)
* [My Completed Solutions - Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)

<em>My solution to the "Categorize New Member" codewars.com kata:</em>

```python
def openOrSenior(data):
    # New list which will populate with member ranks
    member_Rank = []
    for list in data:
	# Age must be 55 or older, rank must be higher than 7
        if ((list[0] >= 55) and (list[1] > 7)):
            member_Rank.append("Senior")
        else:
            member_Rank.append("Open")
    return member_Rank
```

<hr />

### Day 25: Feburary 8th, 2020
#### _Return To Codewars_

**Today's Progress:** I put my money where my mouth is and returned to coding in Python. I completed a codewars kata called "Who Likes it?". The challenge was to create a function that takes a list of names, and return a string message similar to what you would see on Facebook after sharing something. For example "No one likes this" or "Alice, Bob, and 24 others like this". I also created 2 exercises in freecodecamp, and learned about using the transform: scale(x); property to resize elements on a page. 

**Thoughts:** I didn't have a chance to code outside of work yesterday, so I tried to make up for it today by doing a codewars kata AND some freecodecamp work. It felt good to write some Python and solve a codewars kata for the first time in a long time. When I saw how others solved the kata, I realized that I could definitely refactor my code and make it shorter. I'm tempted to be overly critical of myself, but I'm going to resist that urge, because this is all about getting better. I can refactor it in the future, after I've learned more, but the important thing is that it worked, it passed ALL unit tests, and it solved the problem. Again, part of the struggle of completing #100daysofCode, for me anyways, is understandig that <em>perfect is the enemy of done</em>. Rather than quitting because I didn't maintain a perfect 100 day streak, I'm going to just keep going, because the goal is to become a better developer, not a perfect one. 🙌

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)
* ["Who Likes It?" - Codewars.com](https://www.codewars.com/kata/5266876b8f4bf2da9b000362/train/python)
* [My Completed Solutions - Codewars.com](https://www.codewars.com/users/jgatka/completed_solutions)

<em>My solution to the "Who Likes It?" codewars.com kata:</em>
```python
def likes(names):
    #your code here
    num_Likes = len(names)
    if num_Likes < 1:
        return('no one likes this')
    elif num_Likes == 1:
        return(names[0] + ' likes this')
    elif num_Likes == 2:
        return(names[0] + ' and ' + names[1] + ' like this')
    elif num_Likes == 3:
        return(names[0] + ', ' + names[1] + ' and ' + names[2] + ' like this')
    else:
        remaining_Likes = (num_Likes - 2)
        return(names[0] + ', ' + names[1] + ' and ' + str(remaining_Likes) + ' others like this')
```

<hr />

### Day 24: February 6th, 2020
#### _Linear Gradients and Background URLs_

**Today's Progress:** Today I completed three more exercises in the applied visual design section of freecodecamp.org. I learned how to code colors as a linear gradient using the syntax <em>background: linear-gradient(gradient_direction, color 1, color 2, color 3, ...);</em>. I also learned that by setting the transition from one color to the next to happen instantly, a developer can give the appearance of stripes. I also "learned" something that I already knew - that you can set the background property of an element to a url using the syntax <em>background: url("linkgoeshere");</em>

**Thoughts:** Seeing the way that the colors transitioned in the gradients, and creating a div element that had the appearance of a yellow and black construction sign was really, really cool. For a dude that has primarily written code that displays and styles text, or console applications that also take and return text...it was a new experience watching my code create shapes and colors. I'm really looking forward to the projects at the end of this section of the course.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 22-23: February 4th & 5th, 2020
#### _Bash Scripting and More Fun With the Color Wheel_

**Today's Progress:** I'm still suffereing from the effects of this cold. I spent the 4th revisiting the fundamentals of bash scripting. I learned how to designate (what I've always referred to because of my Python background as) argument variables (argv's) using the dollar sign in bash scripts - i.e. $1 $2, etc. Today (02/05) I completed three more exercises on freecodecamp. I learned a more subtle way to use complementary colors so that they don't overwhelm the user. I also learned how to color elements using <strong>hsl(x,y,z)</strong> (hue, saturation, lightness).

**Thoughts:** It was interesting learning how to designate argument variables in Bash in a fashion I'm used to doing in Python. As for the lessons on applied visual design, I now know several different ways to set the color property on an element in a page. It is nice that there are so many ways to accomplish this task in HTML/CSS. My gut feeling is still that simpler is better though. I will most likely continue doing what I've always done, going to a site with a color wheel, pick a color that appeals to me, copy its hex code, and add it to my page. However, using opposite/complementary colors is easier if you know the value of one of the colors in hsl(x,y,z) style notation.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 21: February 3rd, 2020
#### _Tertiary Colors_

**Today's Progress:** Only one exercise tonight. Tertiary colors, which are created by combining a primary color with one of its complementary color. I was able to color elements Orange, Cyan, and Raspberry in this way.

**Thoughts:** Days like today are the ones where it's hard to push through. I've been taking DayQuil to deal with this headache, stuffy nose, and sore throat. I'm about to take NyQuil before bed. No pain no gain. Soon (this weekend I hope) I'm going to reintroduce Python into my coding curriculum, by picking up where I left off in _Automate_ _The_ _Boring_ _Stuff_ _with_ _Python_ and then by completing a codewars exercise as well.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 20: February 2nd, 2020
#### _Float & Complementary Colors_


**Today's Progress:** I completed two more exercises in the freecodecamp chapter on applied visual design. Today's lessons covered the "float" property as well as using a color wheel (and hex codes) to apply complementary colors. Float allows a developer to (at least visually) assign elements to a part of the page that makes them look like they are arranged columns. For instance, assigning one element with the "float: left;" property and the next element with the "float: right" property would make the page look like it had two columns. The exercise had me set one element's background-color property to blue (#0000FF) and a second element's background-color property to yellow (#FFFF00) to show how the two are opposites and thus complement one another.

**Thoughts:** As someone that is colorblind (albeit mildly), I appreciated that the freecodecamp exercises introduced early the idea that a developer should not rely solely on the emphasis provided by complementary colors to style a page.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 19: February 1st, 2020
#### _Z-Index and Margin: Auto_

**Today's Progress:** I completed two exercises in the freecodecamp chapter on applied visual design. Today's lessons covered the z-index and margin: auto properties. z-index allows a developer to choose which element is on top when two elements on a page overlap. margin: auto allows a developer to center elements automatically.

**Thoughts:** Yesterday it was tough to power through because I was tired. Today it was tough to power through because it feels like I'm coming down with a cold. Patting myself on the back again today. On to month two! 👍 

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 18: January 31st, 2020
#### _Absolute and Fixed Positioning_

**Today's Progress:** Today I completed two exercises in the freecodecamp chapter on applied visual design. Today's lessons covered Absolute and fixed positioning.

**Thoughts:** It's been tough trying to get ready for my band's first show on the 8th, whilst simultaneously remaining committed to 100daysofCode. Patting myself on the back for continuing even when there's days where I need to push myself a little bit harder than usual.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 17: January 30th, 2020
#### _Relative Positioning & Hover States_

**Today's Progress:** I completed three exercises in the freecodecamp.org chapter on applied visual design. Today's lessons covered relative positioning and adjusting the hover state of an anchor tag. Relative positioning allows for changing the location of an element relative to the top, bottom, left or right sides of the page. Changing the hover state allows for the color of the link to change when a user hovers over it.

**Thoughts:** I've changed hover states before, but relative positioning is a new concept for me. 

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 16: January 29th, 2020
#### _Size, Height, and Weight_

**Today's Progress:** I completed three exercises in the freecodecamp.org chapter on applied visual design. I learned how to style elements using the font-size, font-weight, and line-height properties. These properties can be assigned to headings and paragraphs tags.

**Thoughts:** I had a busy day but managed to get through three exercises. I'm now 33% through the chapter on AVD. I'm sure that these properties can be applied to more tags than just the headings and paragraph tags. I'll have to test this in later chapters. While I've used font-size before, the font-weight and line-height properties are brand new to me. I've said it before and I'll say it again, I'm glad I followed my instincts and decided to start from the beginning. Many gaps that I didn't know existed are being filled in. Also...this week I put together a new PC, so I'm actually updating the log in Notepad++ on my PC instead of in vim on my Raspberry Pi. I use vim enough at my job that I'm not worried about losing that skill set. It's also worth noting that I generated rsa keys and uploaded them to github so that I could update the log from this PC as well. Does using ssh-keygen in powershell count as a #100daysofcode exercise? I think maybe it should (:

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 15: January 28th, 2020
#### _Box-shadows, Opacity, and Text-Transform_

**Today's Progress:** I completed three exercises in the freecodecamp chapter on applied visual design. I learned how to code box shadows, set opacity, and use the text-transform property to hardcode the case of an element.**

**Thoughts:** Adding a box shadow to a card element made it look much more appealing. I can _see_ the quallity of my code improving. The context for box shadows is actually kind of difficult to digest. I'll need to practice with this one a lot more. The elements (offset-x, offset-y, blur-radius, spread-radius, and color) must appear in a specific order, and 2 of them (blur-radius, spread-radius) are optional. I assumed opacity would go from 0 to 255, but actually the range is 1 (solid) to 0 (transparent). As an InfoSec guy, I can see nefarious uses for setting the opacity of elements that I seek to hide from the user to 0. The text transform property will allow me to set the case of all words in an element rather than editing the words individually. Handy for headlines, titles, headings, etc.**

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 14: January 27th, 2020
#### _More AVD_

**Today's Progress:** I continued working through _vimtutor_, and learned how to specify a line I'm on (CTRL+G), go to that line (<number> CTRL+G), go to the end of the file (G), and go back to the beginning of a file (gg). I also learned how to search for text using (/). In bash, I learned how to work with aliases, how to format my ~/.bashrc file. For freecodecamp, I learned how to style text using the background-color: rgba(x,y,z,0) format, which includes control for opacity. I also learned how to resize headers using the font-size property, so that the headers are larger than the paragraph text.

**Thoughts:** I jumped around quite a bit today but I'm really happy that I'm continuing to diversity my skill set. The vim and bash knowledge come in handy and I'm glad that I'm leveling those skills up to scale along with my coding ability.

**Link(s) to Work:**
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

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 10: January 23rd, 2020
#### _CSS Variables_

**Today's Progress:** I completed 3 freecodecamp lessons on creating and using CSS variables to change several elements at once. I also learned how to create a fallback variable in case a browser limitation or other error causes the CSS variable to not display properly.

**Thoughts**: I've now completed 91% of the CSS chapter and only have 4 lessons left. The next chapter deals with applied visual design. Stoked. I'm also getting pretty damn good with vim.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 9: January 22nd, 2020
#### _Httpserver & RGB Syntax_

**Today's Progress:** As part of my responsibilities at work, I learned how to use the more advanced features of [advanced http server](https://github.com/zeroSteiner/AdvancedHTTPServer). I used it to serve up a sample page that I wrote as well as to serve up files for future endeavors. I completed 2 freecodecamp exercises and learned how to use rgb syntax to color an element as opposed to hex codes or plain English.

**Thoughts:** Busy day at work, band practice, and I still managed to get in two exercises and update my log. Rad. Onward and upward.

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 8: January 21st, 2020
#### _ROYGBIV_

**Today's Progress:** I finished the command line editing chapter in my Bash book. I also learned how to use the replace, change, and put commands in vim. I learned how to use hex codes to style web pages with specific colors. I learned how to use hex codes to style page with mixed colors (R,G,B), and I learned how to style pages with colors using abbreviated hex codes. I only have 10 exercises left in the Basic CSS chapter of the Responsive Web Design Certification course.

**Thoughts:** When I first started using HTML/CSS back in the MySpace days I used hex codes. I would just look them up (probably yahoo search back in those days) and add them to my page. Now I know that the codes use two hexadecimal characters each for Red, Green, and Blue. This revelation made me harken back to elementary school and learning that TVs (and later CRT monitors) used RGB to display colors. I also had no idea that you could abbreviate the hex codes from 6 characters down to three. Still, I plan on actually writing the color out wherever possible, do keep my code readable. I'm continuing to come up with cool ideas for the projects later in the course where I'll build my own pages. Stoked.

**Link(s) to Work:**
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

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 1: January 14th, 2020
#### _Steady_

**Today's Progress:** Today I spoke on the phone with a developer that I used to work with for about an hour. I told him my goals, what I want to learn,what kind of projects I want to build once I'm proficient enough. Over the past 9 days I've written bash scripts at work to help me query information I needed. Tonight after my phone call I completed 2 more CSS exercises. I'm now 50% complete with the CSS portion of the freecodecamp curriculum. I learned how to use clockwise notation to adjust all four sides of an object (top, right, bottom, left). I also learned how to copy and paste in vim using V,y,p. :)

**Thoughts:** I did not know that you could use clockwise notation to adjust all four sides of an object in a single line. As painful as it is to start this journey at the beginning (I studied HTML/CSS in the myspace.com era...yeah...I'm that old), I'm glad that I'm doing it this way. I'm picking up bits and pieces of stuff that I missed along the way. It's the slow and steady way but I'm hoping it's the way that wins the race.

**Link(s) to Work:**
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

**Link(s) to Work:**
* [My profile on freecodecamp.org](https://freecodecamp.org/jgatka)

<hr />

### Day 0: December 31, 2018
#### _Getting Ready_

**Today's Progress:** Forked the original github repo for 100 days of code. I decided that for this, my first "round" of #100daysofcode I'm going to focus on C#/.NET development. I plan on completing some C# coursework and also doing codewars.com exercises in order to actually build things using what I've learned.

**Thoughts:** I'm nervous, but I know I'm going to have a blast once I get started. I've always enjoyed coding, and my career aspirations of becoming a security engineer require me to get more proficient at it.

**Link(s) to Work:**
* [My 100 Days of Code Repo on Github](https://github.com/jgatka/100-days-of-code)
* [My profile on codewars](https://www.codewars.com/users/jgatka)

<hr />

### Day 1: January 1, 2019
#### _Arabic to Roman and Github Woes_

**Today's Progress:** As a way to get back into serious coding after some months off, I revisited codewars and decided to take on the "Roman Numerals Encoder" Challenge, requires an app to take an integer greater than zero and convert it to a roman numeral. I knocked it out, and posting the code into codewars and watching all of the unit tests pass was SO SATISFYING. I even leveled up! I'm stoked to be back to writing code.

Having successfully created a new app, I decided to upload the project to github. The fact that I'm a serious InfoSec professional who uses multi-factor authentication caused me some problems tonight. I had to do a deep dive and learn how to use MFA in github with SSH keys and user tokens. It took me longer to troubleshoot this than it did to write my app! But alas, at about 12:30am I finally got things figured out and now my code is available in github. Perhaps I'll revisit it later and refactor it with some switch cases and some try/catch blocks.

**Thoughts:** It's interesting that the github troubleshooting took longer to deal with than writing the app itself. I suppose that's the nature of the beast though. Years of InfoSec experience has taught me to remain calm when fires need to be put out. Special thanks to my buddy Samuel Kelemen for helping me troubleshoot the github issues. I linked to his github below and you should check it out.

**Link(s) to Work:**
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

## Self-Assessment
1. _Is there anything about the general job search and internship interview process you feel unprepared for? What would make you feel more comfortable and confident in your job search and internship interviews?_
  I would be more confident in a job search if I felt more prepared for the technical interview and non-technical. There is a tendency for me to get nervous when I stand in the front of the room. My memory isn't the best when asked to perform in this capacity. I would like to have more Javascript methods in my toolkit. 

2. _Is there anything about searching for and transitioning into your future career a technical field that you feel unprepared for? What would make you feel more comfortable and confident in this process?_
  I'm a little unclear what a typical work day looks like and what the expectations are. Knowing what the expectations are would help me feel more confident. I would also like to learn D3.js since I feel like this would be a useful skill.
  
## Plan
### Technical Interview
* Read ["Ace the coding interview, every time"](https://medium.com/@nickciubotariu/ace-the-coding-interview-every-time-d169ce1fd3fc)

* Read ["Internship and Job Search Preparing for job interviews Technical interviews"](https://www.learnhowtoprogram.com/internship-and-job-search/preparing-for-job-interviews/technical-interviews) and take notes for the questions linked.

* Read ["Conducting a Great Technical Interview"](http://www.hiringthing.com/2012/05/12/conducting-a-great-technical-interview.html) and note answers to the questions asked.

* Read ["Everything You Need to Know to Rock Your Next Whiteboard Test"](https://skillcrush.com/2016/03/29/rock-your-next-whiteboard-test/).

* Read ["The only 6 types of questions you need to know to ace any coding interview"]([https://www.byte-by-byte.com/six-software-engineering-interview-questions/) and note any logic problems presented and formulate responses.

* Watch ["5 Interview Questions that every Frontend Web Developer Should Know"](https://www.youtube.com/watch?v=0fFYacBQPbA) and note the questions and formulate responses.

* Watch ["What You Need to Know to be a Front End Developer in 2018"](https://www.youtube.com/watch?v=Xd7huBu39qk).

* Read, note, and practice the ["55 Must Know Built-In Javascript Methods and Operators"](https://gist.github.com/raineorshine/9513117.).

* Sign up for ["Programming Tests"](https://tests4geeks.com/programming-tests) and work through problems.


* Solve problems at ["byte by byte: Coding Interview Questions"](https://www.byte-by-byte.com/coding-interview-questions/) on jsfiddle.

### Non-Technical Interview
* Read ["Internship and Job Search / Preparing for job interviews / Non-Technical Interview"](https://www.learnhowtoprogram.com/internship-and-job-search/preparing-for-job-interviews/non-technical-interview). Answer any questions the seem challenging.

* Read ["Fifty Standard Non-technical Interview Questions"](https://github.com/HackYourFuture/alumni/wiki/Fifty-Standard-Non-technical-Interview-Questions). Answer any questions the seem challenging.

### Skill Building
* Read ["Intro to D3.js"](https://square.github.io/intro-to-d3/) to begin learning D3.js.

### First day jitters
* Read ["A Software Developer’s First Day — Part 1"](https://codeburst.io/a-software-developers-first-day-part-1-e1b42193633f).

* Read ["9 Ways to Make the Most of Your First Few Months as a Junior Developer"](https://medium.com/learn-love-code/9-ways-to-make-the-most-of-your-first-few-months-as-a-junior-developer-5c8234fb6403).

## Plan Executed
* ~~Read ["Ace the coding interview, every time"](https://medium.com/@nickciubotariu/ace-the-coding-interview-every-time-d169ce1fd3fc)~~
  - Note to study ["Binary Search trees"](https://www.geeksforgeeks.org/binary-search-tree-set-1-search-and-insertion/) 
  - Note to watch ["mycodeschool"](https://www.youtube.com/user/mycodeschool).  
* ~~Read ["Get that job at Facebook"](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html).~~
  - Note to practice sorts.
* ~~Read ["Internship and Job Search Preparing for job interviews Technical interviews"](https://www.learnhowtoprogram.com/internship-and-job-search/preparing-for-job-interviews/technical-interviews) and take notes for the questions linked.~~
  - Practice code challenges at ["coderbyte"](https://coderbyte.com/challenges)
    + ~~Complete First Factorial challenge~~
    + ~~Complete First Reverse challenge~~
    + ~~Complete Letter Changes challenge~~ ["fiddle"](https://jsfiddle.net/brenderbee/2cxrgaun/7/)
    + ~~Complete Simple Adding Challenge~~
    + ~~Complete Letter Capitalize challenge. Not complete.~~
      - Now refamiliar with: string.toLocaleUpperCase(), string.slice(), string.charAt(), string.split(" ")
* ~~Read ["Conducting a Great Technical Interview"](http://www.hiringthing.com/2012/05/12/conducting-a-great-technical-interview.html) and note answers to the questions asked.~~
* ~~Read ["Everything You Need to Know to Rock Your Next Whiteboard Test"](https://skillcrush.com/2016/03/29/rock-your-next-whiteboard-test/).~~
* ~~Read ["The only 6 types of questions you need to know to ace any coding interview"]([https://www.byte-by-byte.com/six-software-engineering-interview-questions/) and note any logic problems presented and formulate responses.~~
* ~~Watch ["5 Interview Questions that every Frontend Web Developer Should Know"](https://www.youtube.com/watch?v=0fFYacBQPbA) and note the questions and formulate responses.~~
  - _What are your favorite features of HTML5 and CSS3?_
    + HTML5 new structural elements: <aside>, <footer>, <figure>, <dialog>, <nav>, <progress>
    + HTML5 new input types: color, date, datetime, datetime-local, email, month, etc
    + HTML5 new graphics: <svg>, <canvas>
    + HTML5 new media elements: <audio>, <embed>, <source>, <video
    + CSS3: rounded corners (border-radius), border-image, box-shadow,text-shadow, gradient, rgba with opacity, transform with rotation, web fonts, animations, media queries
  - _Can you describe your workflow when creating a webpage?_
    + I typically start with some sort of sketch mock-up. If I am using a framework like Angular, then I determine what parts of the site warrent their own component (does it do a discrete task) and which components need to be children and parents. I typically build/style each component and make sure that it works independentally of the other components. Testing is important at this stage so I will test my logic to ensure that it wotrks. I include media queries and image opitmization so that mobile devices are not loading unnecessarily large files. If I'm using a module bundler like webpack, than I will use that to minify and bundle my code. Check that the site works as expected across various clients.
  - _Can you tell me the difference between CSS reseting and CSS normalizing?_
    + Never used this, but it sounds awesome:
      - Normalize.css makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing.
      - The CSS Reset stylesheet is a basic template to wipe out all built-in styling for HTML elements. You can customize your CSS Reset stylesheet, and add your own preferred styling choices for your webpage.
  - _Can you tell me the difference between inline, inline-block, and block elements?_
    + Inline elements don’t start on a new line, they appear on the same line as the content and tags beside them. Some examples of inline elements are <span> , <strong>, and <img> tags. When it comes to margins and padding, browsers treat inline elements differently. You can add space to the left and right on an inline element, but you cannot add height to the top or bottom padding or margin of an inline element.
    + Inline-block elements are similar to inline elements, except they can have padding and margins added on all four sides. You’ll have to declare display: inline-block in your CSS code. One common use for using inline-block is for creating navigation links horizontally.
    + A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).
  - _Can you please describe to me the CSS Box Model?﻿_
    + The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. Content - The content of the box, where text and images appear
      - Content - The content of the box, where text and images appear
      - Padding - Clears an area around the content. The padding is transparent
      - Border - A border that goes around the padding and content
      - Margin - Clears an area outside the border. The margin is transparent


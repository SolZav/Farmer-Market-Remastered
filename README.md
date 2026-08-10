# Farmer-Market-Remastered
New and improved version of Your-Local-Farmer-Market

I did not use generative AI tools for this project. I used only approved course materials, instructor examples, documentation, and my own work.

## Development Log

### Day 1 (commits shown in Your-Local-Farmer-Market)
Started with my previous GIT417 project as the base for this final project. Before adding on new features, I reviewed existing HTML, CSS, and JS to correct issues and make necessary improvements.
Initial work included:
- Reviewing existing structure
- Checking HTML validator for errors
- Checking CSS validator for errors
- Testing current JS functionalities
- Making updates required to begin the project

### Day 2 (commits shown in Your-Local-Farmer-Market)
Identified another improvement for the HTML, also decided to fork this repository to keep this original file intact
Work included:
- Update HTML
- Validate HTML
- Fork repository
- Continue work on new repository

### Day 3
Started working on new repository and planning what sections I would be adding to integrate the new functionalities. First addition was an events section with the idea to include a jQuery widget, and API call, and a slideshow. 
Work included:
- Update HTML header with "events" li
- Update HTML creating an "events" section with basic content
- Update HTML "events" section adding subsection "movieNight" (API will be called in there)
- Applied existing styles to section

### Day 4
Started by moving around some existing section to improve the exiting page and allow for new functionalities to integrate seamlessly. Continued working on events section, updating html, css and js to create an API call. Updated existing form to check for an exiting full name in local storage and to log the full name to local storage.
Work included: 
- Combine About Us and Services sections, update HTML and CSS for those sections
- Update HTML of movieNight subsection
- Created JS function to make an API call into the movieNight section
- Link jQuery library
- Added styles to movieNight section
- Added a Date object to the movieNight object
- Updated HTML to create empty paragraph for a welcome message
- Updated JS to check for an existing fullName in local storage
- Update JS to log fullName into local storage if non existed
- Updated CSS to style welcomeBack paragraph
- HTML and CSS validated with no errors
- JS still has error in console (logged as Problem 3)

### Day 5
Started by fixing styling and error from the day before. Then chose to improve my services section by replacing my vanilla JS with a jQuery UI Widget. Also implemented a slideshow/carousel feature using the Cycle2 library and following the class example from the zyBook section 6.3.
Work included:
- Downloaded Live Server extension
- Opened HTML on Live Server (it fixed my load error)
- Updated CSS on the events section
- Imported jQuery UI library
- Updated HTML following documentation on how to make the tab widget work
- Updated JS to add Tabs functionality
- Updated CSS to apply existing styles to the new tab links
- Updated HTML, added basic syntax for carousel and linked images
- Updated JS, added the code to make the carousel work
- Carousel doesn't work, problem logged on debugging log

### Day 6
Started by trying to fix problem 5, logged on debugging log. Then updated HTML and added styles to the carousel and gamePlay sections for better look.
Work included:
- Updated HTML with new scripts to fix issues with carousel
- Updated HTML to group photoGallery and gamePlay sections
- Updated CSS to style those sections
- Updated HTML to make the slideshow manual
- Updated JS to make carousel work with Prev/Next buttons
- Validated HTML - no errors
- Validated CSS - no errors
- Validated JS - no errors in console

### Day 7
Tested the site to make sure all the functionalities worked and notices the contactUs section wasn't working
Work included:
- Updated JS for contactUs section, logged in debugging log

## Debugging Log

### Problem 1
My original repository I was working from wasn't letting me fork or clone it

### What I tried
I tried cloning from GitHub Desktop, I also tried making a local copy of my original repo and renaming it

### What fixed it
I created a new local folder with my new repository name and copied all the existing files into it, then I submitted it to GitHub

### What I learned
I learned that you cannot fork your own files in GitHub, and that sometimes it is best to just start over

### Problem 2
My console displayed the following error: "Uncaught ReferenceError: $ is not defined"

### What I tried
I checked my JS for typos, compared my code to class examples. 

### What fixed it
Adding a script tag in my HTML to link a jQuery library

### What I learned
That sometimes the error is not coming from the file you are working on. You should always check all of your files to make sure you are not missing something somewhere else.

### Problem 3
My console displayed the following error "Unsafe attempt to load URL file:///C:/Users/sol_l/OneDrive/SOL/GIT%20(Web%20Development)/GIT%20418/Farmer-Market-Remastered/index.html from frame with URL file:///C:/Users/sol_l/OneDrive/SOL/GIT%20(Web%20Development)/GIT%20418/Farmer-Market-Remastered/index.html. 'file:' URLs are treated as unique security origins."

### What I tried
I looked up the error in some forums but couldn't find any answers. I reached out to the professor to get some help

### What fixed it
Downloading the Live Server extension and running my file using it fixed the problem

### What I learned
That opening your HTML directly into the browser from VS can cause a loading error

### Problem 4
After importing my jQuery UI library, swapping my buttons for li and anchor tags, and adding my JS, my tabs were not working

### What I tried
I went over the documentation again and I noticed that the ul for the tabs needed to be inside a div, I fixed that but it was still not loading

### What fixed it
After I placed the full section inside a div, both the actual tabs and the ul with the links, that's when it started working

### What I learned
That sometimes a quick read to the documentation is not enough, since there are very specific requirements that need to be followed on the HTML to ensure the jQuery loads correctly 

### Problem 5
When trying to create my slideshow function I get the following error on my console: jquery.cycle2.carousel.js:27 Uncaught TypeError: Cannot read properties of undefined (reading 'transitions')

### What I tried
I looked at some documentation and tried to find someone with the same issue. I also tried downloading the cycle2 file in other way to see if it would work.

### What fixed it
Changing my jQuery 4.0 script for the jQuery 3.7.1

### What I learned
That sometimes older plugins may not be compatible with newer versions of jQuery, and sometime you need to search for an older version to get your code to work

### Problem 6
When doing a final testing of the site I noticed my form wasn't displaying the success message

### What I tried
I check my JS to see what if my code was correct and noticed that when adding an if statement into the contactUs section I made it so it would only display the message if the first name wasn't loaded into the local storage

### What fixed it
I removed the message display from inside the else section to make sure it always executed

### What I learned
I learned that when adding functionalities to an exiting code you always need to test more than once to make sure you didn't introduced a bug

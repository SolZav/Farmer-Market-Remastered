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
- Updated HTML to create empty <p> for a welcome message
- Updated JS to check for an existing fullName in local storage
- Update JS to log fullName into local storage if non existed
- Updated CSS to style welcomeBack paragraph

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
Adding my <scrip> in my HTML to link a jQuery library

### What I learned
That sometimes the error is not coming from the file you are working on. You should always check all of your files to make sure you are not missing something somewhere else.

### Problem 3
My console displayed the following error "Unsafe attempt to load URL file:///C:/Users/sol_l/OneDrive/SOL/GIT%20(Web%20Development)/GIT%20418/Farmer-Market-Remastered/index.html from frame with URL file:///C:/Users/sol_l/OneDrive/SOL/GIT%20(Web%20Development)/GIT%20418/Farmer-Market-Remastered/index.html. 'file:' URLs are treated as unique security origins."

### What I tried
I looked up the error in some forums but couldn't find any answers. I reached out to the professor to get some help

### What fixed it
Not fixed yet

### What I learned



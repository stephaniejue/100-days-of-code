# 100 Days Of Code - Log

### Day 1: Tuesday, January 3, 2017

**Today's Progress**: Fixed some formatting on my Free Code Camp Quote Generator.

**Thoughts** I'm having issues with my AJAX running on Chrome and when pushed to github pages. When running it locally on safari, I don't seem to have issues. Since I haven't learned AJAX in my coding bootcamp, I have some digging to do. I feel good about the HTML/CSS progress I've made so far.

**Link(s) to work**: [Quote Generator](https://github.com/stephaniejue/quote_generator_ajax)


### Day 2: Wednesday, January 4, 2017

**Today's Progress**: Updated buttons and shadowing Free Code Camp Quote Machine.

**Thoughts** I finished some of the last touches included button effects and shadowing. Its baffling how long little things take and how much back and forth happens, but I'm getting closer to a look I like. I pushed my page to github pages but need to research the security error "This page is trying to load scripts from unauthenticated sources." Still have some learning to do around AJAX, but I'm happy to have a working version on codepen and github pages!

**Link(s) to work**: [Quote Machine - Github Pages](https://stephaniejue.github.io/quote_generator_ajax/), [Quote Machine - Codepen](http://codepen.io/stephjuechin/pen/WoGRbz)

### Day 3: Thursday, January 5, 2017

**Today's Progress**: Worked on address book app inheritance.

**Thoughts** Today was frustrating trying to figure out why my application.html.erb file wasn't being rendered for my other views. Because application.html.erb has my page headers, bootstrap also wasn't loading. After spending some time checking my file paths, I chose to do a workaround I found on stackoverflow. I created a partial html_header.html.erb and moved all of my header info to there, then added <%= render 'layouts/html_header' %> to each page. Seems to work for now. I'll get started with bootstrap tomorrow!

**Link(s) to work**: [Address Book App](https://github.com/stephaniejue/address_book_app_rails)

### Day 4: Friday, January 6, 2017

**Today's Progress**: Created a wildlife app at LEARN academy and continued working on it after school.

**Thoughts** Created a rails app using scaffolding today and learend about AJAX and JSON. The app has a relational database and functionality to add/remove sightings to animals using AJAX. This took most of the day and the bones of it I worked on with my pair programmer. After class I continuted cleaning up some of the code and adding in some formatting, including bootstrap. Unlike my Address Book App (above), the application.html.erb file IS working and I'm having a much more succesful time messing with the look of the application. I'd like to add more functionality tomorrow.

**Link(s) to work**: [Wildlife Tracker App](https://github.com/stephaniejue/StephRya/tree/master/wildlife_tracker_with_validations)

### Day 5: Saturday, January 7, 2017

**Today's Progress**: Created a weather app with basic API call and AJAX/jQuery functionality

**Thoughts** Today I started on a new app as part of FCC's projects. I'm pretty happy with the basic functionality I have so far. I was able to pull geolocator info usina an API and include that in an API call to OpenWeatherMap for weather information. I ran into a few bumps, including forgetting to add the jQuery CDN (oops!) but I'm happy that I was able to figure out most of the functionality that I'll need for the app. Next up I'll fine tune the display, including what type of info is provided to the user.

**Link(s) to work**: [Weather App Github](https://github.com/stephaniejue/weather_app), [Weather App Codepen](http://codepen.io/stephjuechin/pen/LxVMwm)


### Day 6: Sunday, January 8, 2017

**Today's Progress**: Continued working on my weather app

**Thoughts** After creating the API request yesterday I worked on formatting the data today. I created 2 functions to convert kelvin (the default temp returned) into farenheit and celsius. I added sunrise and sunset times and converted those times from unix to javascript local time format. I also added a weather icons library and table to ogranize all weather elements. 

**Link(s) to work**: [Weather App Github](https://github.com/stephaniejue/weather_app), [Weather App Codepen](http://codepen.io/stephjuechin/pen/LxVMwm

### Day 7: Monday, January 9, 2017

**Today's Progress**: Continued working on my weather app

**Thoughts** Had to create a workaround because geolocator api was returning a 403 error. Used $.getJSON("http://ipinfo.io"..) instead, which is working pretty well (and in codepen!). Created function to change time icon depending on local time of user. Need to do some cleanup with my js file and figure out the 403 errors. Might look in to google's geo api instead. Still happy about my progress, not feeling as lost as I thought I would with triaging AJAX/API errors.

**Link(s) to work**: [Weather App Github](https://github.com/stephaniejue/weather_app), [Weather App Codepen](http://codepen.io/stephjuechin/pen/LxVMwm)

### Day 8: Tuesday, January 10, 2017

**Today's Progress**: Continued working on my weather app

**Thoughts** Added jquery on click functionality to swtich from F to C temp. Had to work around using jquery after an AJAX call. Also fixed time icons to account for double digit hours.

**Link(s) to work**: [Weather App Github](https://github.com/stephaniejue/weather_app), [Weather App Codepen](http://codepen.io/stephjuechin/pen/LxVMwm)

### Day 9: Wednesday, January 11, 2017

**Today's Progress**: Added toggle button and button.js to my weather app

**Thoughts** Added a toggle button to switch temps for a more visual effect. For some reason code isnt working the same on codepen or github pages as it is locally, something to triage more tomorrow.

**Link(s) to work**: [Weather App Github](https://github.com/stephaniejue/weather_app), [Weather App Codepen](http://codepen.io/stephjuechin/pen/LxVMwm)

### Day 10: Thursday, January 12, 2017

**Today's Progress**: Finished FCC weather app and 10% done with the challenge!

**Thoughts** Put the finishing touches on my weather app today. I added background images that change for night vs day, I'll have to check tomorrow morning if its working correctly. In the future, I may play around with some additional background images based on the weather condition, but I need to move on for now. I set a goal to finish this by end of week and told myself I would get as close to "perfect" as possible. Yesterday I was feeling a frustrated for getting carried away with the design aspects of this app, but I'm happy how it turned out. Trying not to get caught up in the little things going forward. Up tomorrow (and this weekend): finishing my portfolio.

**Link(s) to work**: [Weather App Github](https://github.com/stephaniejue/weather_app), [Weather App Codepen](http://codepen.io/stephjuechin/pen/LxVMwm)

### Day 11: Friday, January 13, 2017

**Today's Progress**: Starting/Restarting my portfolio

**Thoughts** I'm setting a goal to have the majority of the layout/template figured out this weekend. I just started playing around with some templates and am trying to figure out what pieces I'd like to combine. Long way to go, but need to get this done.

### Day 12: Saturday, January 14, 2017

**Today's Progress**: Lots of work done on my portfolio

**Thoughts** I finally settled on a good template that feels like me. I got some of the basic content updated and a few changes to the formatting. I want to add in some animation with JavaScript/Jquery tomorrow. I cleared out in-progress content enough so that I can start sending this out. Also, need to add email functionality. Really happy with my progress! At least I have something to show for interviews now.

**Link(s) to work**: [Portfolio Github](https://github.com/stephaniejue/stephaniejue), [Portfiolio GitHub Pages](https://stephaniejue.github.io/stephaniejue/)


### Day 13: Sunday, January 15, 2017

**Today's Progress**: Almost done with my portfolio!!

**Thoughts** I still have a few things I want to add to and finish, but I have a working portfolio! and I got it up and running with my domain name. So excited to share this after two full days of work this weekend. Not going to spend too much time reflect, already committed to git a lot today, that counts.

**Link(s) to work**: [Portfolio Github](https://github.com/stephaniejue/stephaniejue), [LIVE Portfolio](http://www.stephaniejue.com/)

### Day 14: Monday, January 16, 2017

**Today's Progress**: Not much to report, but worked on my portfolio a little

**Thoughts** Trying to figure out the contact form for my portfolio, then realized I need to figure out PHP for Heroku for the tutorial I'm doing. So spent some time installing and configuring... going to work on it more tomorrow.

### Day 15: Tuesday, January 17, 2017

**Today's Progress**: Still fighting with my contact form

**Thoughts** Got my static site up on heroku with contact_me.php, but it's still not working. It's giving me a success alert, which is the frustrating part. I downloaded MAMP to try and figure this out on a local server, but still no luck. Digging continues tomorrow.

### Day 16: Wednesday, January 18, 2017

**Today's Progress**: Group projects! Working on VolunteerUP!

**Thoughts** Today we started working on our group projects at LEARN. After class, I added some styling/formatting changes to feel more like a real application. Will be putting in lots of work on this in the next two weeks. Excited to see what we can make!

**Link(s) to work**: [VolunteerUP Github](https://github.com/stephaniejue/VolunteerUP)

### Day 17: Thursday, January 19, 2017

**Today's Progress**: Group projects continued

**Thoughts** We're making tons of progress which is great! We already have a lot of the basic functionality in place. Spent some time fixing tests and merge conflicts. Also got to work on some fuzzy searches. The searches aren't perfect because of postgres's pg_trgm similary threshold. Will try to figure that out tomorrow.

**Link(s) to work**: [VolunteerUP Github](https://github.com/stephaniejue/VolunteerUP)

### Day 18: Friday, January 20, 2017

**Today's Progress**: Brushing up on JavaScript for Xander Challenge

**Thoughts** Along with working on VolunteerUP, I did some brushing up on Javascript for a code challenge I have. Reading up on closures, anonymous functions and call backs. I didn't get very far, so I'll have to do more on Sunday.

**Link(s) to work**: [VolunteerUP Github](https://github.com/stephaniejue/VolunteerUP)

### Day 19: Saturday, January 21, 2017

**Today's Progress**: Fixing Apartments App

**Thoughts** I tried to fix my apartments app today, soemthing what messing up with login with twitter/facebook and the google apis.

**Link(s) to work**: [Apartments App Github](https://github.com/stephaniejue/apartments_app)

### Day 20: Sunday, January 22, 2017

**Today's Progress**: Work on Apartments App

**Thoughts** I had a lot of issues after opening my Apts app yesterday. I wanted to clean it up to send over to a potential internship. I ended up doing a lot of little bug fixes to get the maps and authentication apis working, Foundation, and S3 working on my dev environemnt. Its still not in as good of shape as I would hope, but it's live for now. I need to work on the search feature and admin pages, and figure out more functionality to add to it.

**Link(s) to work**: [Apartments App Github](https://github.com/stephaniejue/apartments_app), [Apartments App Heroku](https://nameless-headland-26041.herokuapp.com/apartments)


### Day 21-25: Monday, January 23, 2017 - Friday, January 27, 2017

**Week's Progress**: Apartments App

**Thoughts** This week we got a ton done on the apartments app. I've been so busy I forgot to log. Some of the major things I implemented are the waitlist functionality, user roles, media share buttons, and cause tags. Along with that I created tests for each and helped in resolving testing issues. The app is looking great! Finishing up next week before demo night.

**Link(s) to work**: [VolunteerUP Github](https://github.com/stephaniejue/VolunteerUP)

### Day 26: Saturday, January 28, 2017

**Today's Progress**: RuboCop and Dotenv on Apartments App

**Thoughts** Today I played around with two new gems: RuboCop and dotenv. I implemented rubo cop and started working through the offenses. Glad I got it working and it seems to be a pretty good system once you get up and running. I also FINALLY installed dotenv which has solved all my issues with S3 in dev. Glad I got experience. I rolled them out on Apartments app first, but will probably work on putting them in our VolunteerUP.

**Link(s) to work**: [Apartments App Github](https://github.com/stephaniejue/apartments_app)


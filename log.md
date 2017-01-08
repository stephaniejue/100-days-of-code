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

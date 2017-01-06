# 100 Days Of Code - Log

### Day 0: Tuesday, January 3, 2017

**Today's Progress**: Fixed some formatting on my Free Code Camp Quote Generator.

**Thoughts** I'm having issues with my AJAX running on Chrome and when pushed to github pages. When running it locally on safari, I don't seem to have issues. Since I haven't learned AJAX in my coding bootcamp, I have some digging to do. I feel good about the HTML/CSS progress I've made so far.

**Link(s) to work**: [Quote Generator](https://github.com/stephaniejue/quote_generator_ajax)


### Day 1: Wednesday, January 4, 2017

**Today's Progress**: Updated buttons and shadowing Free Code Camp Quote Machine.

**Thoughts** I finished some of the last touches included button effects and shadowing. Its baffling how long little things take and how much back and forth happens, but I'm getting closer to a look I like. I pushed my page to github pages but need to research the security error "This page is trying to load scripts from unauthenticated sources." Still have some learning to do around AJAX, but I'm happy to have a working version on codepen and github pages!

**Link(s) to work**: [Quote Machine - Github Pages](https://stephaniejue.github.io/quote_generator_ajax/), [Quote Machine - Codepen](http://codepen.io/stephjuechin/pen/WoGRbz)

### Day 2: Thursday, January 5, 2017

**Today's Progress**: Worked on address book app inheritance.

**Thoughts** Today was frustrating trying to figure out why my application.html.erb file wasn't being rendered for my other views. Because application.html.erb has my page headers, bootstrap also wasn't loading. After spending some time checking my file paths, I chose to do a workaround I found on stackoverflow. I created a partial html_header.html.erb and moved all of my header info to there, then added <%= render 'layouts/html_header' %> to each page. Seems to work for now. I'll get started with bootstrap tomorrow!

**Link(s) to work**: [Address Book App](https://github.com/stephaniejue/address_book_app_rails)

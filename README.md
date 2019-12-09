# CONTACT - ABERDEEN

Project One: User Centric Frontend Development

This is a website created to promote the Contact club night and Aberdeen DJ; Jonny Kennedy. 
The site includes information about Contact & DJ Jonny Kennedy along with details about previous events run by Contact and links to
social media sites.

## Demo
A live demo can be found [here](https://jsudron.github.io/Contact-Aberdeen/).

## UX
 
### User stories

As a member of Contact I expect to be able to have a site which is easily expanded and can be updated with any relevant information. The site must be functional but also stylish, 
whilst showcasing what the club night is all about.
As a club owner I expect to find out why I'd want to host a club night with Contact and be able to easily contact them.
As a DJ I expect to find out why I'd want to perform at a Contact club night and be able to easily contact them.
As a club-goer I expect to be able to find out about what the club night is all about and how to find them.

### Strategy

Aimed to keep the design minimal but still showcase the artwork I was provided by the client along with being as user-friendly as possible.

### Scope 

Contact Aberdeen has run club nights before with DJ Jonny Kennedy heading these up. However, having been out of the scene for some time we wanted
to give club owners a glimpse into what Contact club nights are all about. We also wanted to use the site as a platform for DJs to get in touch
should they want to perform at a Contact club night. Therefore providing an easy means of contact on the site was a must.

### Stucture

The site structure is fairly straightforward with a fixed navbar allowing for easy access to each section.
Also provided a footer with access to Facebook, Mixcloud & Soundcloud along with Google map links to the venues.

### Skeleton

- Wireframe - Home & About Sections [Wireframe](https://github.com/JSudron/Contact-Aberdeen/blob/master/assets/wireframes/Wireframes-part%201.jpg)
- Wireframe - Gallery, Bookings & Location Sections [Wireframe](https://github.com/JSudron/Contact-Aberdeen/blob/master/assets/wireframes/Wireframes-part%202.jpg)

### Surface

Went for a dark, minimal colour scheme taken from [Coolors](https://coolors.co/000000-ffffff-494949-7c7a7a-ff5d73), a free pallete generator website.
This included black, white, greys (outer space & trolley grey) & fiery rose, which adds a nice contrast on buttons & hover effects.
A mobile first design process was implemented to ensure the site looks & functions as good as possible on a wide range of devices.
The 'about' section has been tailored to small, medium and large devices in order to keep the images at a good size whilst still looking effective.
The navbar was kept collapsible among all devices in order to keep the minimal look, however this may be changed in the future for desktop sites.

## Technologies
1. HTML
2. CSS
3. Bootstrap (4.3.1)
4. JavaScript

## Features

The use of the scrollSpy feature in Bootstrap was implemented. A smooth scrolling effect was then added to this in CSS.
Added JavaScript code to make the navbar collapse when an anchor link is closed.
A carousel was used for the gallery as this was the most effective way show off the large number of photos on all screen sizes.

### Features Left to Implement

Eventually, I'd like to add a 'music' section which would have Soundcloud music embeded directly to the site.
Would also be useful to add in an 'upcoming events' section once new bookings are made, this would include flyers with relevant info & links to
buy tickets.


## Testing

### User stories

Below details how the user stories were provided with the intended outcomes to showcase the 'Contact' club night.
For members of Contact:
The simple navbar & scrollSpy function provides an easy way to navigate the site without having to go back and forth through webpages. The design is minimal, in keeping with the style used at club
nights. Sections can easily be added to the site & the responsive design means changes can look great on a range of devices. The 'About' section has a profile of each member, along with information
and futher images of the event in the gallery. The venue locations are detailed, along with links & their are links to all of the relevant social media spaces to provide further exposure to the 
club night.
For club owners:
Club owners can find out details of what type of music is played and the concept of the club night in the 'About' section. The 'Gallery' section is also a great way to entice them to book by showing
a range of visuals of the events. Should they want to book 'Contact' the 'Bookings' section is an easy way to get in touch. The footer also provides links to social media which includes Mixcloud &
Soundcloud links so they can have a listen to the type of music played at events. 
For prospective DJs:
The website has an easy to using contact form for getting in touch if they shoudl want to play at the club night. The footer provides the dates & times of events, whilst the 'About' sections
explains the type of music played at the club nights.
For club-goers:
The website explains the type of music played whilst also providing a 'Find Us' section which displays a map of the main venue. The footer provides further addresses, club times and 
a Google maps link showing the venues. The 'Gallery' section also shows punters what to expect on the night.

### Functionality
The contact/booking form gives error notifications when typing in an invalid e-mail address.
The 'required' attribute also alerts the user if a field has not been entered on the form when clicking submit.
All fields must be filled in for the form to submit correctly.

The scrollSpy links all work with a smooth animation.

All links to other webpages e.g. social media links have been tested. They all open using 'target="_blank" which opens the link in a new tab on the browser.

The code was put through [W3C](https://validator.w3.org/) a markup validation service used to check code.

The site was tested across multiple browsers (Chrome, Safari, Internet Explorer, Firefox & CM Browser) and on multiple devices, using [Responsinator](http://www.responsinator.com/).
It was also directly tested on an Android Phone, iPhone, iPad, Macbook and PC. No issues were found.

## Deployment

The site is hosted on GitHub pages, deployed directly using the master branch. The deplyed site updates automatically when new commits are made and
then pushed through on GitPod. The landing page is named 'index.html' in order to deploy correctly.
To run locally, you can clone this repository directly into the editor of your choice by pasting 'git clone https://github.com/JSudron/Contact-Aberdeen.git' into the terminal.
To cut ties with this GitHub repository, type 'git remote rm origin' into the terminal.

## Credits

### Content

All content in the 'About' section was written by myself.

### Media

The header image 'bw-audience.jpg' was taken from [Pexels](https://www.pexels.com/) stock image library,which added the greyscale filter to on Photoshop.
The image 'location-image' was a screenshot from Google maps.
The remaining photos used in this site were created and obtained from the client Jonny Kennedy.

### Acknowledgements

Parts of code were learnt from various sites, which was then amended by myself to obtain the look & feel I was after. 

- Navbar Section -
Code learnt from navbar tutorials at [Mdbootstrap](https://mdbootstrap.com/docs/jquery/navigation/hamburger-menu/) & Code Institute tutorials).
Also took the navbar collapse JavaScript code from [Stackoverflow](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click).

- Header section -
Code learnt from Code Institute tutorials & 'HTML & CSS design and build websites' by Jon Duckett.

- About section - 
Code learnt from Code Institute tutorials and [W3schools](https://www.w3schools.com/bootstrap/bootstrap_theme_band.asp).

- Gallery section -
Code learnt from carousel tutorials at [GetBootstrap](https://getbootstrap.com/docs/4.0/components/carousel/).

- Bookings section -
Code learnt from Code Institute tutorials.

- Footer section - 
Code learnt from Code Institute tutorials.

- Smooth scroll -
Code learnt from Slack users.

#### This is for educational use

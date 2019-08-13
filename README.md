# Sea Turtle Conservation in Costa Rica

Milestone 1 project: User-Centric FrontEnd Development - Code Institute.

As my first project at Code Institute I’ve decided to create a new website for Sea Turtle Conservation project VerdiAzul in Costa Rica.
[Visit website in GitHub pages.](https://github.com/jdtiding/Turtle-Conservation-Project) 

Current website:  <http://verdiazulcr.org/>  is only in spanish, contains old information, and has not been updated since 2011.

By creating new, modern, responsive website I would like to encourage new potential volunteers from all over the world to come to VerdiAzul 
to provide support to this amazing project.

## UX

Main goal of the project is to create strong online presence of the organization that will help attract new volunteers to come to support the project.

Since VerdiAzul is an independent non-government non-profit group, they exist thanks to the support from the volunteers visiting them.
***

##### Perfect volunteer:
- speaks english;
- is looking for meaningful travel opportunities;
- is passionate about ensuring the future of the world’s oceans;
- loves sea turtles and / or nature;
- would simply like to explore the world in a responsible and positive way;
- likes meeting new people;
- is open to new challenges and opportunities;
- is looking for a quiet place to run away from civilization and do something good for the future of the planet;
- age 16 to 70;
***

##### On the website a potential volunteer will find all necessary information about the project:
- location;
- species of the turtles nesting in this area;
- requirements to join the program;
- price: what's included / excluded;
- short history of VeriAzul;
- gallery showing volunteers at work, releasing turtles and pictures of the beach;
- contact form to get more information about the project;
***
Balsamiq Mockups 3 was used to create [wireframes](https://github.com/jdtiding/Turtle-Conservation-Project/tree/master/wireframes).
***

## Features

This site uses the Bootstrap's scrollspy feature.
***
A responsive, fixed navigation bar with:
- [logo and name of the organization](https://jdtiding.github.io/Turtle-Conservation-Project/index.html) on the left side (clicking the [logo or text](https://jdtiding.github.io/Turtle-Conservation-Project/index.html)
returns users to the home page);
- links to sections on the right side:
    - [Home](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#home)
    - [Volunteer](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#volunteer) dropdown menu:
        - [Overview](https://jdtiding.github.io/Turtle-Conservation-Project/#overview)
        - [For Who](https://jdtiding.github.io/Turtle-Conservation-Project/#forwho)
        - [Activities](https://jdtiding.github.io/Turtle-Conservation-Project/#activities)
        - [Price](https://jdtiding.github.io/Turtle-Conservation-Project/#price)
    - [About Us](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#aboutus)
    - [Gallery](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#gallery-section)
    - [Contact](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#contact)

is placed on the top of the webpage.

Below 768px navbar collpases to hamburger menu.
***
At the bottom page has a footer with:
- name and address of the organization;
- icons linking to: [google maps](https://www.google.nl/maps/place/Asociaci%C3%B3n+Vida+Verdiazul/@10.1628267,-85.8099637,17z/data=!3m1!4b1!4m5!3m4!1s0x8f9e468a78c3600b:0xa545abca3d618879!8m2!3d10.1628267!4d-85.807775?hl=en-GB), 
[contact form](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#contact)
and [facebook](https://www.facebook.com/vida.verdiazul.1);
- copyright information; 

***

### [Home Page](https://jdtiding.github.io/Turtle-Conservation-Project/index.html)

Fullscreen Bootstrap Image Slider with caption contains 3 slides changing every 7 seconds.

First slide contains main header, every slide contains a short sentence and a button that links to volunteer section.

Every slide contains navigation arrows on the sides and indicators at the bottom of the slide.
***
### [Volunteer section](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#volunteer)

Dropdown menu linking to:
- [Overview](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#overview)
    
In this section user will find short information about location of the project and also a little bit about the turtles that nest in the area.

Section contains main centered header.  
On medium and large devices text is divided in 2 columns.  
Every column contains centered header and paragraph.

On small devices user will see only 1 column.
***

- [For Who](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#forwho)

This section contains information about the pontential volunteer profile and requirements.

Responsiveness see Overview section.
***

- [Activites](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#activities)

In this section user will find general description and list of daily activites.

Responsiveness see Overview section.
***
- [Price](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#price)

The Price section contains: 
- one full-width column: general information linking via envelope icon to contact form for more information;
- two responsive columns: information about what's included/excluded from the price.

Responsiveness see Overview section.
***

### [About Us](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#aboutus)

At the top or the page centered main header is placed.

Page consists of two full-widht columns placed one above each other and are visible this way on all devices.

I've chosen this way because in the future I would like to add more information to the subsection "Who are We?" and make both columns responsive like in subsections above.
***

### [Gallery](https://jdtiding.github.io/Turtle-Conservation-Project/#gallery-section)

The Gallery page is laid out in columns of thumbnail images, two columns wide for small devices, three columns wide for medium and six columns wide for large ones.  

Each thumbnail features a picture of everyday life in VerdiAzul.

Each image can be clicked to open a fancybox window to view enlarged picture, to move on to the next image, view the previous one, or return to the gallery page.
***

##### The Gallery and the Contact page both have the same, fixed background image of a turtle.
##### Scrolling up or down through those pages,especially on large devices, gives a nice impression and can encourage a potential volunteer to fill in the form and ask for more information.
***

### [Contact](https://jdtiding.github.io/Turtle-Conservation-Project/#contact)

The Contact page features a contact form, which requests first name, last name, email address and provides a box to leave a message.

For medium and large devices first and last name are visible in one row, for small devices every single input is displayed one below other.

On medium and large devices contact form is centered and occupies 70% of the page.  
Small devices display contact form as 100% width of the page. 

The bottom of the form contains a Send Button.
***

## Features to implement in the future

- translation to Spanish for volunteers from Central/South America;
- translation to French - Costa Rica is a very popular holiday destination especially for French-speaking part of Canada or Belgium;
- translation to German - the majority of the people visiting Costa Rica come from Germany.
- adopt a turtle - sections that would link to a new page where a turtle/turtle nest can be adopted;
- reservation form;
- the price section - information to be added about the standard prices depending on the lenght of stay.
- FAQ secion that will include more detailed information about accommodation, leasure time, how to get there etc.;
***

## Technologies used

- HTML and CSS programming languages;
- AWS Cloud9 - for IDE while building the website;
- Bootstrap CDN to provide icons from FontAwesome;
- jQuery to reference Javascript needed for the responsive navbar, image slider and Fancybox gallery modal;
- Popper.js reference Javascript needed for the responsive navbar.
- Fancybox for a gallery modal popup to view gallery images;
- Google Fonts to style the website fonts;
- AutoPrefixer to make sure the css code is valid for all browsers;
***
The project uses Bootstrap 4 to simplify the structure of the website and make the website responsive easily.
***

## Testing

Testing information can be found in separate [TESTING.md](https://github.com/jdtiding/Turtle-Conservation-Project/blob/master/TESTING.md) file.
***

## Deployment

This project was developed using the [Cloud9 IDE](https://aws.amazon.com/cloud9/), committed to git and pushed to [GitHub](https://github.com/jdtiding/Turtle-Conservation-Project)
using the built in function within AWSCloud9.
***

## Credits

The text for the Volunteer page was created by me.  
The text for About Us page was translated by me from the original [VerdiAzul](http://verdiazulcr.org/) website.
***
All the photos used in this site are from my private collection.  
The Gallery and the Contact page bacground-image was taken from [Pexel](https://www.pexels.com/).
***
CSS code for shadows and hover responsiveness of gallery images was originally taken from [Material Design Box Shadows](https://codepen.io/sdthornton/pen/wBZdXq).
***

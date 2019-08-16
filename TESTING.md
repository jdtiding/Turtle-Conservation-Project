# Sea Turtle Conservation in Costa Rica - testing details

[Main README.md file](https://github.com/jdtiding/Turtle-Conservation-Project/blob/master/README.md)

[Visit website in GitHub pages](https://github.com/jdtiding/Turtle-Conservation-Project)
***

## Validation check

### [W3C Markup Validation](https://jigsaw.w3.org/css-validator/#validate_by_input)

W3C Markup Validation Service was used to check the validity of the html code.

Fixed issues:
- 1 missing end tag;
- ul list nested in ul list: 
    - dropdown pill in navigation bar was changed to dropdown link,
    - css code was updated accordingly;
***

### [W3C CSS Validation](https://validator.w3.org/#validate_by_input)

W3C CSS Validation Service was used to check the validity of the CSS code.

No issues were found.
***

## Browser testing

### Devices and platform:

The webpage was tested on following devices and platforms:  

**Desktop:**  
HP 14-cf0925nd, Windows 10:

- Google Chrome Version 76.0.3809.100 (Official Build) (64-bit);
- Internet Explorer 11 Version 11.615.17763.0;
- Microsoft Edge 44.17763.1.0;
- Firefox Quantum 68.0.2 (64-bit);
- Opera version 62.0.3331.116;
***

**Tablet:**  
Lenovo Tab 4 10, Android 7.1.1:
- Google Chrome;
- Microsoft Edge;
- Firefox;
- Opera;
***

**Mobile:**  
Sony Xperia Z, Android 5.1.1:
- Google Chrome;
- Microsoft Edge;
- Firefox;
- Opera;

Sony Xperia Z5, Android 7.1.1:
- Google Chrome;
***

**Apple devices:**  
**- Safari:**  
*I've asked my friends to check the website on their mobile devices and report any issues they find.*  
*Additionally I've run online tests on [Cross Browser Testing Cloud Lambda](https://www.lambdatest.com/) for desktop, tablet and mobile Apple devices.*
***

### Functionality check

The following items were checked accross all the platforms and devices:

#### [Navabar](https://jdtiding.github.io/Turtle-Conservation-Project/index.html)

1. Click on the logo/text in the navigation bar and verify that it links to the home page;
2. Click on each navigation menu/dropdown menu item and verify that it links to the correct page;
3. Click on each navigation menu/dropdown menu item and verify that offset is correct;
4. Click on dropdown menu and verify that it expands;  
    *Dropdown menu didn't work, problem was solved immediatley by adding data-target="navbarResponsive" to the .navlink.dropdown-toggle and 
    id="navbarResponsive" to .dropdown-menu.*
5. Hover over the logo/text and over each navigation menu/dropdown menu item and verify the hover color change works as expected;
6. Verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu at the appropriate place;
***

#### [Home Page Image Slider](https://jdtiding.github.io/Turtle-Conservation-Project/index.html)

1. Check image slider that slides change every 7 sec;
2. Click on prev/next button and verify that it goes to next/previous slide;
3. Click on every image slider indicator (at the bottom of the page) and verify that it goes to the correct image;
3. Click on button on every image and verify that it links to Volunteer page;
4. Hover over button on every image and verify the hover color change works as expected;
4. Check every slide that text is correctly centered and doesn't overflow outside the image;
***

#### [Price page](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#price)

1. Click on envelope icon and verify that it links to Contact form;
2. Hover over the envelope icon and verify the hover color change works as expected;
***

#### [Gallery page](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#gallery-section)

1. Click on every image and verify that it opens enlarged;
2. Verify responsiveness: one column wide for very small devices, two columns wide for small devices,  
  three columns wide for medium devices and six columns wide for large ones; 
3. Background image verify that stays fixed during scrolling;
***

#### [Contact page](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#contact)

1. Try to submit the empty form and verify that an error message about the required fields appears;
2. Try to submit the form with all inputs valid and verify that the page reloads.
3. Verify that the form display behaves and centres the way expected:
    - 70% width for medium and larger devices, centered;
    - 100% width for small devices;
3. Background image verify that stays fixed during scrolling;
***

#### [Footer](https://jdtiding.github.io/Turtle-Conservation-Project/index.html#contact)


1. Hover over each icon and confirm color transitions expected.
2. Click on google maps and facebook icon to confirm it opens a separate tab for it's link.
3. Click on envelope icon to confirm it links to contact form;
4. Hover over copyright text and confirm colour transitions expected.
5. Click on copyright text to confirm it opens a separate tab for it's link.
6. Verify that the footer is responsive and looks good on all device widths.
***

### Results

#### Issues found:

##### Desktop devices:

1. Internet Explorer:
  - Image slider Home page and background images for Gallery and Contact pages don't scroll smoothly. Images are "jumping" during scrolling.  
    Internet Explorer is not widely used these days, and in Microsoft Edge the webpage displays correctly, issue will not be investigated further.

2. Chrome and Opera:
  - Image slider 2nd and 3rd photo do not display correctly.  
    On the right side of the page white strip appears through the whole height of the page.  
    Images are going back to 100% width after scrolling the page a little bit down.  
    **Solved by changing image width from 100vw to 100%**
***

##### Tablets:

1. Chrome:
  - Fixed images not supported;

2. Opera:
  - Fixed images not supported;

3. Firefox:
  - Fixed images supported, but scrolling through image slider was not smooth.    
    For better UX background images were set to scroll both for medium and small devices.  
    That signifcantly improved scrolling through the home page.
***

##### Mobile devices:

1. Chrome:
  - Fixed images not supported;

2. Opera:
  - Fixed images not supported;
  - Text and button on landscape view image slider home page overflow on image slider indicators.  
    **TO BE INVESTIGATED**

3. Firefox:
  - Fixed images supported, but scrolling through image slider was not smooth.    
    For better UX background images were set to scroll both for medium and small devices.  
    That signifcantly improved scrolling through the home page.
  - Navigation bar: while clicking links dashed border of the color of the hovered text appears.  
    **TO BE INVESTIGATED**
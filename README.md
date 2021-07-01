# Wipeout Surf Camps
Read Me file. Live site here.

![Mockup](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/screenhot-website.jpg?raw=true)

Wipeout Surf Camps is a site that hopes to open the world of surfing to newcomers, while catering to an existing customer base that has been built over the years. This is the first iteration of the site, with the company relying solely on word of mouth previously. Wipeout Surf Camps will be useful for surfers to gain an understanding of what each location offers, and will provide an option to contact the company or to book directly. For this, the site needs to be easy to navigate, well laid out and as informative as possible.

## Structure 
The site is a simple structure consisting of six individual pages with the following features:

* Navigation bar
    * This is the same on each of the pages and includes links to the Logo, Home, Gallery, Contact Us and Book pages. This allows easy navigation throughout the site without the need for a ‘back’ button. Clicking on the Logo will bring you back to the landing page. You will know you are on this page because the surfer icon will highlight in yellow. 

    ![Navigation](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/header.jpg?raw=true)

    * When you navigate to the other pages, then a yellow sun will indicate your location.

    ![Sun-Icon](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/navigation-sun-symbol.jpg?raw=true)

    * This functionality is the same across all devices.

* Footer bar
    * The footer is the same on each of the pages and contains a link to each of the social media sites that the company has – Instagram, Facebook and Twitter. The branded logo of each site is in line with the aesthetic of the Wipeout Surf Camps site.

    ![Footer](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/footer.jpg?raw=true)

* Landing page
    * The landing page features a call to action, directing you to the two surf house locations. To select a house, when scrolled over/hovered on an image pops up. When clicked, it takes you to the individual information for that location.

    ![Landing-page](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/surfhouse-1.png?raw=true)

    * The background image used is that of a surfer in action – a taster of what the user may experience with the company!

* Surf House One   
    * Corralejo. The page contains information on the location, gallery images of the house itself and a Google map showing precise location. Details on accommodation, surfing lessons and prices are also included. To view the next house, click on the main logo button (also the 'Home' button) which will return the user to the landing page.

* Surf House Two   
    * Maspalomas. The page contains information on the location, gallery images of the house itself and a Google map showing precise location. Details on accommodation, surfing lessons and prices are also included. To return to the landing page, the user clicks the main logo button (also the 'Home' button).

* Gallery
    * The gallery is a collection of images taken from camps held previously. The company offers a photography service, and with the permission of guests uses images from this in the gallery.
    Images are set with a 4px border, while the background is a simple white to prevent clashing. The images are responsive to device size.

    ![Gallery](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/gallery.jpg?raw=true)

* Contact

    * Along with providing direct contact numbers for the founders, this page sets out the history of Wipeout Surf Camps.
      Text is overlaid on a transparent scrim as this allows the text to be read easily over the background image of a wave.

    ![Contact](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/contact-us.jpg?raw=true)

* Book

    * A booking form allows users to select which location they are interested in and send a direct inquiry to the customer service team. 
      Entry bars are rounded with a [ ]% border as the curve is more aesthetically pleasing against the background image of a wave being surfed. 
      The ‘Surf’s Up!’ button is highlighted when hovered over, alerting the user to the fact that if they click then their form will be submitted.

    ![Book](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/surfs-up-button-yellow.jpg?raw=true)

* Design

    * Colour Scheme: Ocean colour scape – dropper tool from imagery
      Get rgb colours

* Logo 

    * The logo is simple and uses the same font as the header text - Lobster. The client wanted an image of a surf board that would fit with the theme and also wanted to use an open source (free) image. As one could not be found, to address this, a snowboarding image was used which fits quite well given its simplicity.

    ![Logo-plain](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/logo-plain.jpg?raw=true)

    ![Logo-yellow](https://github.com/krigla3/Wipeout-surf-camp/blob/master/docs/logo-yellow.jpg?raw=true)

* Typography
    * Headings: Lobster, sans serif as backup.
    * Body: Raleway, sans serif as backup

* Responsiveness

    * Responsiveness is good across all screen size and devices. 
      This was achieeved by adding multiple media queries in CSS that take effect on the following resolutions: 1980px, 1075px, 650px, 410px.

* Features left to implement

    * A discussion was had on whether or not to embed video clips in the gallery and to add audio to the landing page. On reflection, the client decided to wait until they had time to edit some new footage, but are keen to revisit the idea. 
    A chat option was also considered, but given the timeline for completion, the client also decided to wait.
    By implementing both ideas at a later date, it will give users a fresh experience and allow the client to promote the changes across their social media.

## Technologies Used

* HTML
* CSS
* Font Awesome
* Github
* Google fonts
* Color picker tool

## Deployment

Wipeout Surf Camp was deployed to GitHub Pages by following the below steps:

1. Navigate to the ["Wipeout-surf-camp" repository](https://github.com/krigla3/Wipeout-surf-camp) on GitHub.
1. Navigate to the 'Settings' tab.
1. Navigate to 'Pages' from the menu on the left. 
1. Select 'master' branch in the source drop-down.
1. Click 'Save'.
1. A link to the live deployed page is generated and can be found here: https://krigla3.github.io/Wipeout-surf-camp/




## Project Status

* I am still working on this project. There are multiple solutions I would like to implement in the future. 
  With more time I plan to make the overall responsiveness of the site even better. 
  Additionaly I would like to work on the aesthetic through the whole website. 
  Potentially audio would be added to the page and also embeded youtube surf videos.



## Testing

* Check the responsiveness of the website on different screen sizes across different browsers (Google Chrome, Internet Explorer, Microsoft Edge).

    * Test: 
        1. Open the website in each of the aforementioned browsers.
        1. Right-click on the screen and choose 'Inspect'.
        1. Grab and drag the responsive window slowly down to 300px and then back again, checking that everything is displayed correctly in each size / breakpoint.
    * Result:
        1. All elements are responsive and display correctly in two of the tested browsers and in each of the window sizes. (Google Chrome and Microsoft Edge) 
        1. Site is unresponsive when tested with Internet explorer.

* Check the responsiveness of the website on different mobile devices. Samsung S20, Samsung S21, Huawei P9 lite.

    * Test: 
        1. Open the website with each of the mentioned devices.
        1. Click on all navigation items (Landing Page, Gallery, Contact, Book, Each surf house) one by one to make sure the attached links are correct and that they lead the user to the correct parts of the website.
        1. Click on all social media links (Facebook, Twitter, Instagram) one by one to make sure that the links are in working order and that they all open in a separate tab.
    * Result:
        1. All links working and directing user to the correct pages.
        1. All links are working and all of them open in separate / new tabs.

* Check that the links in the navigation bar navigate to correct pages.

    * Test: 
        1. Open the website in a browser.
        1. Click on all navigation items (Landing Page, Gallery, Contact, Book, Each surf house) one by one to make sure the attached links are correct and that they lead the user to the correct parts of the website.
    * Result:
        1. All links working and directing user to the correct pages.

* Check that the links to social media pages in the Footer work and open in new tabs.

    * Test: 
        1. Open the website in a browser.
        1. Click on all social media links (Facebook, Twitter, Instagram) one by one to make sure that the links are in working order and that they all open in a separate tab.
    * Result:
        1. All links are working and all of them open in separate / new tabs.

* Check that the name of the page user is currently on is highlighted (yellow sun symbol, yellow font when hovered over) in the navigation bar.

    * Test: 
        1. Open the website.
        1. Open each of the pages in the navigation bar to see whether the active page has a yellow sun symbol next to it in the menu.
    * Result:
        1. Each of the navigation bar element has a yellow sun symbol next it when the page is active.

* Check validation of the Contact Us form.

    * Test: 
        1. Open the website in a browser and navigate to the Contact Us page.
        1. Fill in the form leaving different input areas empty each time to make sure there is a warning message displayed each time you leave any of the fields empty.
    * Result:    
        1. The form cannot be submitted until each of the input fields has been filled in correctly so the validation is working.

* Check validation of HTML and CSS through the whole website with HTML validator and and Jigsaw validator.

    * Test: 
        1. Copy and paste the HTML code in the validator
        1. Copy and paste the CSS code in the validator
     * Result:    
        1. No major errors shown through the interface.

## Issues/Resolutions?
* For two surfhouse pages once the website is opened with a smaller resolution device like a phone, a right margin is appearing.
  This affects the page in a way that a user would have to scroll down in order to see the content. In the future I would have this updated to improve the aesthetic of the page on mobile device. 

* HTML validator showed warnings for h1 titles and article titles. This did not affect the overall performance of the site. As I was close to project deadline I was unable to   edit these titles into h2 headings in order to fit better wit the semantic markup.
  

## Sources

* [Google Fonts](https://fonts.google.com/) have been used to import Lobster and Raleway fonts. 
* [Colorpicker Tool](https://imagecolorpicker.com/) has been used for selecting the color for the header logo and main navigation links 
* [Font Awesome](https://fontawesome.com/) used to implement the sun icon from main navigation, peace sign from book page and bed icon from the main page.
* [Pexels](https://www.pexels.com/) used to import most of the photos on the page.
* [Main Page Quote](https://www.surfertoday.com/surfing/the-best-surfing-quotes-of-all-time) 
* [House bbq photo](https://www.countryliving.com/gardening/garden-ideas/g1435/outdoor-kitchens/)
* [Bunkbed Blue Room Photo](https://www.pinterest.com/pin/729372102140587007/)
* [Bedroom 3 Photo](https://pixabay.com/photos/bed-bedroom-closet-furniture-lamp-1839184/)
* Code Institute ‘Love Running’ Training Module
  

## Credits

* [FlexBox](https://www.w3schools.com/css/css3_flexbox.asp) tutorial has been used to address the site responsiveness on smaller devices.
* [Footer-responsivenes](https://codepen.io/Nazarja/pen/bGwvWNz) tutorial was used to implement the footer structure.
* Structure of readme file is inspired by the [Sussex Walks](https://github.com/OlgaJ1989/sussex-walks) repository and the Love Running Code Institute readme.


## Acknowledgements
* Special thanks to my mentor Daisy McG for her guidance and support throughout the project.
* A big thank you for providing moral support through the project to my girfriend Roberta Carroll and my cousin Daniel Matasic. 

## Contact
* For any queries on the creation of this project, please contact David Maric. email: david.maric4@gmail.com







     

















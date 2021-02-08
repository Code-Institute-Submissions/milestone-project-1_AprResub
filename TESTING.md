# Glada Tander Sthlm AB Website - Testing details

[Main README.md file](/README.md)

[View website in GitHub Pages](https://github.com/peter199834/milestone-project-1)

## Testing

- [W3C CSS validation](https://jigsaw.w3.org/css-validator/)
- [W3C Markup Validation](https://validator.w3.org/)
    - I used **W3C CSS Validation Service** and **W3C  Markup Validation Service** to check that the code is valid.

### Client stories testing:

Most common path through the website: 
- Home > Om praktiken(/About the clinic) > Vi i teamet(/Us in the team) > Kontakta oss(/Contact) 
- Home > Aktuellt(/News) 

### Testing client stories from UX section of README.md

1. As a new visitor to the website, I want learn more about the staff and their approach, so I can feel more connected with them and get a better understanding if they would be a good choice for me.
    1. As you scroll down the page there is a clear flow of information about the clinic, the staff and the approach.
    2. The "Vi i teamet" or the "Om praktiken" menu item scrolls you down to information about the clinic, the staff and the approach.
2. As a new visitor to the website, i want to learn more about their treatments and its cost.
    1. There is a part of the section labelled "Behandlingsrutiner" with information about the treatments and its cost.
3. As a visitor to the webstite, i want to find contact information.
    1. As most websites the contact information is furthest down inside the footer.
    2. There is a menu item labelled "Kontakta oss" and one called "Hitta hit" which scrolls you down to the footer where the contact information is.
4. As a visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
    1. No matter what page the new visitor lands on, they can easily find and use the navigation bar. 
    2. The logo image always leads back to the home page (the starting place for most client stories).
    3. The website follows the typical layout of where the information should be, like having contact information at the bottom of the pages.


### Manual (logical) testing of all elements and functionality on every page.

#### Home Page:

1. Navigation bar:
    1. Go to the "Home" page from a desktop.
    2. Change the screen size from desktop to tablet to verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu at the appropriate place.
    3. When checking responsiveness of navbar, verify that there is no overflow causing ugly size changes to menu items. _During testing there were overflow problems here. This was fixed by reducing size of the button and logo margins_.
    5. Click on the logo in the navigation bar and verify that it links to the home page. 
    6. Click on each navigation menu item and verify that it links to the correct page (and part of page). 
    9. Change screen size to small and click burger icon, verify that the menu drops down and that the menu text is centred.
    10. Repeat verification of functionality and responsiveness on mobile phone and tablet.

2. The full width images:
    1. Go to "Home" page from a desktop. 
    2. Confirm that the picture is 100% of the width and looks good on all browser sizes.

3. About the clinic(/"Om praktiken") section:
    1. Reduce and expand width of window to confirm that the text and icons in this section responds correctly and looks good on all device widths.

4. About us(/"Vi i teamet") section:
    1. Reduce and expand width of window to confirm that the profile images and corresponding texts looks good on all browser sizes.
    
5. Footer: 
    1. Hover over the logo and click on it to see it responds as expected. 
    2. Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths. 

6. Review all functionality and responsiveness on mobile phone and tablet.

#### News(/"Aktuellt")

1. Navigation bar: 
    1. Navbar code is identical on all html pages. Testing already completed.

2. News section:
    1. Change the screen sizes to verify that the section looks good on all sizes.
    
3. Footer:
    1. Footer code is identical on all html pages. Testing already completed.


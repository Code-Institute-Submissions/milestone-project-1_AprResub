# Christin och Michael

## Dentist and dental hygienist

---

A comprehensive website for a small dentist practice in Stockholm, Sweden. Website features an about page, a profile page, contact information and a relevant information page. The primary goal of the website is to provide information about the practice and its workers.

The business goals of the website are:
* Build brand awareness
* Be a source of information

The customer goals of this website are:
* Clear easy to find information.
* Getting in contact with the denstists.

## UX

#### Ideal client

##### The ideal client for this business is:
* Swedish/english speaking
* Lives/resident in Sweden
* Older than 23.

##### Visitors to this website are searching for:
* A dentist/dental hygienist.
* Information about the practice and/or the workers.

##### This project is the best way to help them achieve these things because:
* You can't get the information anywhere else, except in person with the dentist and/or dental hygienist.
* This website is:
    * Easy to navigate.
    * Steps the client through easily understandable information.
    * Gives the client the information they need without overloading them.

##### Client stories
1. As a new visitor to the website, I want to learn more about the staff and their approach, so I can feel more connected with them and get a better understanding if they would be a good choice for me.
2. As a new visitor to the website, i want to learn more about their treatments and its cost.
3. As a visitor to the website, i want to find contact information.
4. As a visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.

##### Wireframe: 

- [Home and news/"aktuellt"](wireframe.pdf)


## Features

Each page features a responsive **navigation bar** with conventional placing of **logo** (top left) and the menu items (top right).
Each page has a **footer** with **copyright information** and a **logo** (bottom right) aswell as contact information.

#### Home
The main page features two pictures of Stockholm (where the dental clinic is at), an "about the dental practice" section and an "about us" section.
The purpose of the two pictures of Stockholm and the UX is to give a positive emotional response to the user.
The "about the dental pracice" section has the text on the right and left side of the icons which are in the middle for desktop and tablet. On mobile the icons are to the far left and the correspondent text to the right of the icon.
The "about us" section has the first profile picture to the right and the correspondent text to the left of it. The second profile picture is to the right and the correspondent text to the left of it.
Note: The sections have been called other names than "About the dental practice" and "About Us". You may see this reflected in commits but I changed the names to "About Us" and "About the dental practice".

#### News/"Aktuellt"

The news/"Aktuellt" page features a "relevant information" section with relevant information.

### Existing features

- Header Logo - Exists on [every page](../index.html) and allows all users to easily recognise the business brand. Clicking the logo returns users to the home page as they would expect.
- Header Navigation Bar - Exists on [every page](../index.html) and allows all users to easily navigate all the website's pages and find what they are looking for.
- Footer Copyright and Contact Info - Exists on [every page](../index.html) and protects business copyright.
- Footer Logo - Exists on [every page](../index.html) and allows all users to easily recognise the business brand.

### Features to Implement in future
- Option to choose language to either english or swedish. This allows english speaking customers to view the website and get a better understanding of the clinic.
- Add a "treatments" page, which provides more information about the treatments used by the dentist.
- Add clickable images with correspondent text on desktop, and slides of pictures with correspondent text as shown in the wireframes. This was the original plan but wasn't added because it would've taken too much time and required javascript.
- Improve styling on the text.

## Technologies Used

- I used HTML, CSS and Javascript programming languages.
- [Gitpod](https://gitpod.io) - I used **Gitpod** for their IDE while building the website.
- [BootstrapCDN](https://www.bootstrapcdn.com/)
    - I used **Bootstrap4** to simplify the structure of the website and make the website responsive easily.
    - I used BootstrapCDN to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
- [jQuery](https://jquery.com/)
    - I used **jQuery** to reference Javascript needed for the responsive navbar.

## Testing 

Testing information can be found in separate [TESTING.md file](TESTING.md)

## Deployment

This project was developed using the [Gitpod IDE](https://gitpod.io), committed to git and pushed to GitHub.

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/peter199834/milestone-project-1), the following steps were taken: 
1. Log into GitHub. 
2. From the list of repositories on the screen, select **peter199834/milestone-project-1**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**.
6. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.


### How to run this project locally

To clone this project into Gitpod you will need:
1. A Github account. [Create a Github account here](https://github.com/).
2. Use the Chrome browser.

Then follow these steps:
1. Install the [Gitpod Browser Extentions for Chrome](https://www.gitpod.io/docs/browser-extension/).
2. After installation, restart the browser.
3. Log into [Gitpod](https://gitpod.com) with your gitpod account.
4. Navigate to the [Project GitHub repository](https://github.com/peter199834/milestone-project-1).
5. Click the green "Gitpod" button in the top right corner of the respository.
6. This will trigger a new gitpod workspace to be created from the code in github where you can work locally.

To work on the project code within a local IDE such as VSCode, Pycharm etc:
1. Follow this link to the [Project GitHub repository](https://github.com/peter199834/milestone-project-1).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open the terminal.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

## Credits

### Content
- The text for the Home page and News(/"Aktuellt") page was created for and by Michael and Christin Fischer.

### Code
- I recieved help from a [tutorial](https://www.youtube.com/watch?v=gt8zOLQ8A0w) on how to make a responsive navbar with a logo.
- I recieved help from a [tutorial](https://www.youtube.com/watch?v=vsBaCblIOuQ) on how to make a responsive footer.
- I recieved help from [w3schools](https://www.w3schools.com/) on understanding concepts and adding social links.

### Other

Special thanks to Anna Greaves, for uploading and sharing her educational purposed website to [github](https://github.com/AJGreaves/portrait-artist/) and giving permission to use her readme as an example to follow. It was very helpful and made it easier to structure the readme. I did not copy any essential parts of Annas readme, however i did not change the "How to run this project locally" and "Deployment" part except for some of the links, since i saw no purpose in doing so. I would have written the same steps, but maybe using some different words. Rewriting it would make no functional difference.

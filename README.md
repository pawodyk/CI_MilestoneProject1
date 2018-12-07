# Milestone Project 1 
## Author Pawel Wodyk

 This project focus on a frontend-only website using the technologies that I have learned throughout User Centric Frontend Development.  

 The site closely followed the requiremets provided by the "band". The site allowes the person visiting the website to get the fealling of the band. The site was designed in the theme of the 60s rock band, with bright colours and use of groovy border type around text fields and funky font type.
 The user could read abount the band listen to their music and navigate throuaught the webpage with ease thanks to the sticky menu bar that is available in any section of the website.
 
[Deployed website on the GitHub Pages](https://pwodyk.github.io/CI_MilestoneProject1/)

## Rquirements for the project

``` text
    Build a static (front-end only) website for a band. As a starting point, you may want to use wireframes, as we did in the UX lesson (you can use Balsamiq or any other tool, including just pen and paper). You can use either your assets or the assets within the following GitHub repo.
    The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world. You have been given the following requirements after interviews with the client’s representatives:
        - Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.
        - Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.
    The band has provided you, the developer, with the following assets that they would like to showcase on their website:
        - Photos of the band members
        - A video clip
        - Audio clips
    Also, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter and YouTube pages.
```

## UX

Link to the initial design [wireframe](UX-Files/)

User stories:

1. I am a band fan and would like to listen to their music and read their stories
    - the user can achive that by listening to the top tracks from each of the featured albums and could also use the spotify widget to listen to other songs on their service directlly from our website.
    - The user could read about each band members as well as their history directlly from the website or use the provided links to the social media websites like facebook or twitter to contect with the band

2. I never heard about The Monkees and I would like to learn more about them
    - The user is greated with the video of one of their greatest hits streight from the first page.
    - the user can then read about the history of the band and about its members 
    - they can also listen to the music available in the *albums* sections

3. I know The Monkees and I would like them to play at my venue
    - The user can send the request form to the monkees directlly at the website
    - They can also view the link to the band social media

## Features

### Existing Features

- Feature 1 - The Splash screen with video playing when you visit the website. Allowes user to get a fealing of the website and see the band in acction.

- Feature 2 - Sticky menu that allowes navigation anywhere on the website. Allowes user to navigate the website.

- Feature 3 - Play top track from albums and see the album art.

- Feature 4 - Submit the message to the band requesting the show.

### Features Ideas for future implementation

- Implement link to the shop beside the albums.

## Technologies Used

- HTML5 & CSS3
  - This website is based on HTML5 and CSS3.

- [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/)
  - I used the Bootstap framework for desigining the page layout.

- [Font Awesome Icons](https://fontawesome.com/)
  - I used font awesome for social links icons.

- JavaScript
  - Simlple JavaScript code was used to:
    1. Allow pause the video on click.
    2. To colapse navigation bar ([Bootstrap - collapse](https://getbootstrap.com/docs/3.3/javascript/#collapse)).

## Testing

All the features on the website has been tested manually.

### Testing process

1. Testing Responsive design of the website
    1. The site has been tested in range of most commonlly used resolutions bettween iphone 6 resolution of 375x667px to full hd 1920x1080px
    2. I tested the extreame resoltutions eg. 1000x100px
        - results: the site and each section is fully responsive and scallable to the resolution with minumum width of 300px. below this threashold the site is still usable but some features may not displayed correctlly

2. Testing Sticky navigation menu
    1. The menu is working while scrolling
    2. It is collapsing correctlly in the mobile resolution however on Firefox it is pushing the content down which cause it to go up once the menu is collapsed, this bug do not reproduce on the Chrome.
    3. Each section link is working correctlly

3. Testing video pausing on click
    1. the script is working when video is on causing it to pause
    2. it also work when video is paused causing it to resume
    - on chrome the video is paused by default and do not autoplay until clicked.

4. Testing the contact form
    1. the contact form require the name phone number and message to be entered and do not submit without it
    2. the email section is not required however once some text is entered it need to be in email format to submit
    3. the submit button is working correctlly and take the user to the dummy thank you website which could be replaced in the future to submit message to the database.

5. Testing audio files
    1. the audio files are playing as expected with an abitity to control the volume, mute or pause the audio file.


## Deployment

The Website was deployed on GitHub Pages from the Master Branch.

The link to the deployed website:
    https://github.com/pwodyk/CI_MilestoneProject1

## Credits

### Content

- text in sections *History* and *Band* was taken from [Wikipedia - The Monkees article](https://en.wikipedia.org/wiki/The_Monkees)
- the biography for each band member was taken from [Biography.com website](https://www.biography.com/)

### Media

- Media files acquired from Code Institute's [project-assets](https://github.com/Code-Institute-Org/project-assets) GitHub repository.

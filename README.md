# Pop-up Exhibition

This Pop-up Exhibition site is covering all you need to know about the famous music photographer Denton Thornton's first ever pop-up exhibition that will be presented in three cities globally and your source to get your hands on the limited free tickets. 

## Features

### Existing Features

Pop-up Exhibition is a one-page fully responsive home page with fixed navigation bar at the top for quick and easy access to the sections. 

* **Navigation bar:**
    * A fully responsive navigation bar for takes the user to the different sections _About_, _Gallery_, _Exhibition Dates_ and _Book Tickets_ further down on the home page, that allows the user to read about the photographer, see the Exhibition Dates and finally book the limited tickets to chosen exhibition location. 
    * The fixed navigation bar allows the viewer to easily access the requested sections.

* **Landing page cover section:**
    * This section should attract the user to visit the exhibition with a one of the photographers most famous photograph. 
    * There is a cover-box that highlights the three cities the exhibition will be shown in and a call-to-action button to encourage the viewers to book their tickets. 
    The cover box is fully responsive and is a fixed box on smaller devices. 

* **About section:**
    * The About section is for the user who is not that familiar with the photographer to read into who he is and be intruiged to visit the exhibition. 
    * The About section is also featuring a photo of the photographer himself. 

* **Gallery section:**
    * For those who doesn't know Denton Thorntons work there is a small gallery selection to showcase some of his biggest photographs. 
    * Photos was resized to fit the banner to 300px and cover image was compressed not to take too long to load on the page. All photos have been uploaded to the 'assets/images/' folder. 

* **Exhibition Dates section:**
    * A list of the current set dates of the exhibition featuring three cities and its location. 

* **Book Tickets section:**
    * A form that allows the user to book their tickets by filling out first name, surname and email and finally the requested location in forms of radio buttons. All fields are _required_ and must be filled out by the user before submitting their form.

* **Footer section:**
    * A fixed footer for easy access to the social media links. 
    * The icons direct the user to the social media pages in a new window for the user to follow news and updates, not having to loose access to the current webpage. 


### Features Left to Implement

A potential webshop to sell small posters when the exhibition is on. 


## Testing

All links have been tested and clicked on to confirm they are directing to the correct end-destination, both during the building of the site and a final check before deploying. 
During the building of the site there was a conistent check in preview window to see that all changes looked good and how (if) it affected the rest of the site. 

Setting up the site and it's structure and styling was quite unproblematic, going through one section at the time and testing it live before moving on to the next one. However I had the following issues:

* Container with 100% changing size when button border expands 1px on hover
Solve help support: 
Ok, so I think you'll need to set the form div position to absolute, and the height to fit-content. That will stop it resizing. You'll have to center it then using this css:

    * In the first HTML check a header to the Gallery section was missed. I tried to add it but decided that visually it wouldn't look good and trust the images speak for themselves.
    * In the Form section I had repeated the same label-id for the three radio buttons which was changed to unique id's.

    I

* HTML (https://validator.w3.org/)






My first repository on Github.
:dancer:


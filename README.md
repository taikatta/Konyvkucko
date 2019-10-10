# Könyvkuckó
## Hungarian children's books in Deansgrange Library!

This is my first Milestone Project on the Full Stack Web Developer Code Institute course.

#### Summary

I moved to Ireland 5 years ago and since then every time we visit back to Hungary my luggage is packed with Hungarian books. I had an idea of launching a Hungarian Library somewhere in Dublin. Last year I applied for a grant, as a first step I wanted to buy only children's books. The collection is about 120 books by now and it is growing, I got books from authors, organizations, individuals. The launch of the Hungarian children's book will be on the 29th of October, 2019.

## UX

The website is for Hungarian families living in Ireland and would like to inform users about the selection of Hungarian books available to borrow.

The books are hosted by Deansgrange Library, but they can be requested via the inter-library loans system from other libraries who are part of Libraries Ireland. The requested books will be delivered to the users local library.

User Stories

* As a Hungarian parent living in Ireland I would like to know about the books that are available to borrow from Libraries Ireland

* As a Hungarian parent living in Ireland I would like to be able to contact Konyvkucko with my questions or in case I want to donate books to the Hungarian Library

## Features

* I set scroll-behavior property to smooth for the whole HTML, this way instead of a straight jump, there is a smooth scrolling effect.

* I used a fixed navbar, to allows users to navigate through the website quickly without the necessity to go back to the top of the page. ( I used [Bootstrap](https://getbootstrap.com/docs/4.3/components/navbar/)'s responsive navigation header here.)

* The Our Books section allows users to request the book they want by clicking the `Request it` button, which takes the user to Libraries Ireland webpage. (I used [Bootstrap](https://getbootstrap.com/docs/4.0/components/card/)'s Card decks as I needed a set of equal width and height cards. I used [Jumbotron](https://getbootstrap.com/docs/4.0/components/jumbotron/) here to showcase this section.)

* I created the Gallery section to share some photos taken at the library. I used [Bootstrap](https://getbootstrap.com/docs/4.0/components/carousel/)'s Carousel, a slideshow for cycling through images. I added the previous and next controls as well.

* The Contact section is added to let users to get in touch with me. I used [Bootstrap](https://getbootstrap.com/docs/4.0/layout/grid/)'s Grid system here, for a better layout and align content. Also used [Bootstrap](https://getbootstrap.com/docs/4.1/components/forms/)'s Forms, the user can leave some fields blank and still able to submit the form, the only verification is the email verification. I used [Font Awesome](https://fontawesome.com/icons/envelope-open-text) icons in this section.

* Please note, that although this section contains a form, information entered into the fields will not feed anywhere, as the scope of the project does not include any back-end functionality.

* At the Footer I used [Font Awesome](https://fontawesome.com/icons/facebook-square)'s Facebook icon. Clicking on the icon will open the Konyvkucko's Facebook page in a new tab.

#### Features Left to Implement

* I would like to add all the books we have at the library and also a search bar, to make it easier to search within the books.


## Technologies

* HTML5 - provided the structure of the website
* CSS - was used to style my pages
* [Bootstrap Framework (4.3.1)](https://getbootstrap.com/) - used for the responsive design, collapsable navbar, card (content container) and carousel (slideshow)
* Git - used for version control
* [GitHub](https://github.com/) - used to host the deployed website and my repository
* [Font Awesome](https://fontawesome.com/) - used to import icons
* [Google Fonts](https://fonts.google.com/) - used to import Montserrat fonts
* [tiny png](https://tinypng.com/) - used to compress images
* [JQuery](https://getbootstrap.com/docs/4.1/getting-started/introduction/) - was imported via the Bootstrap framework, used to create a responsive collapsible navbar, the carousel
    
## Testing

Throughout the development of the project, I carried out testing. I used the Chrome Developer Tools consistently.

I used [W3C Validator](https://validator.w3.org/) to check the markup validity of Web documents in HTML and CSS. Highlighted errors:
* I used the same `id` in two different places.
* When I deleted a `<div>` I forgot to delete the closing `</div>`

#### Operational Test

| Nr | Test          | Before image  | After image  | Test result |
| ---|:-------------:| :-----:| :-----:| :-----:|
| 1 | Click - **Books** Button      |    ![alt text](https://github.com/taikatta/Milestone1-Konyvkucko/blob/master/assets/images/Home.png "Home") |![alt text](https://github.com/taikatta/Milestone1-Konyvkucko/blob/master/assets/images/books_after.png "Books") | Passed |
| 2 | Click - **Gallery** Button      |   ![alt text](https://github.com/taikatta/Milestone1-Konyvkucko/blob/master/assets/images/Home.png "Home") |![alt text](https://github.com/taikatta/Milestone1-Konyvkucko/blob/master/assets/images/Gallery_after.png "Gallery") |Passed |
| 3 | Click - **Contact** Button      |   ![alt text](https://github.com/taikatta/Milestone1-Konyvkucko/blob/master/assets/images/Home.png "Home")|![alt text](https://github.com/taikatta/Milestone1-Konyvkucko/blob/master/assets/images/Contact_after.png "Contact") |Passed |


## Deployment

This website is hosted using GitHub pages, deployed directly from the master branch. Every time I made a change to the site, I used `git commit` and `git push` to send the changes to GitHub.

#### How to clone your repository to create a local copy
* Select the [Repository](https://github.com/taikatta/Milestone1-Konyvkucko)
* Click on the 'Clone or Download' button
* Copy the URL provided
* Open terminal (Mac) / Open Git Bash (Windows) 
* Find the directory you want to clone the repository to
* Type `git clone` and paste the URL, press Enter
* Your local clone has be created

## Credits

#### Content

At Our Books section the short description of the books are from the author's ([Berg Judit](https://www.bergjudit.hu/)) webpage.

#### Media

The first background photo was taken from [Stavros Sotiriou's](https://ssaphoto.co.uk/deansgrange-library) website. I have Stavros' permission to use the photo in my project.

The second and third background photos are mine. The photos in slideshow were also taken by me.

The photos of the book covers in the Books session are from the author's ([Berg Judit](https://www.bergjudit.hu/)) webpage. 

#### Acknowledgements

Thanks to my mentor, Narender Singh for guiding me on the right path.

Anthony O'Brien, you helped and offered advice when I struggled to make this website. You deserve a big thank you from me.

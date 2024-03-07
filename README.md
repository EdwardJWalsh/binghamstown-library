# Binghamstown Library

The Binghamstown Library website is the official website for Binghamstown Library. It is not only a library but a community hub that offers a wide range of services for all members of the family.

Users of this website will be able to find all the information they need about our library and range of services as well as opening times, how to contact us and the register form. This site is targeted towards people of all ages.


![README_am_i_responsive](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/9900ba6c-d089-46bb-b681-2a1f93b48b68)

# Features

## Navigation bar

* Featured at the top of the page, the navigation bar includes the name of the website in the top left hand corner which is also a link to the homepage.
* It includes the links to the other pages of the website - the 'Services' page and the 'Register' page.
* The menu is responisive and collapses when viewed on a smaller screen at which point the user is provided with a drop-down menu.

* Picture of Navigation bar when viewed on larger screen:
![README_navbar_](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/55881e32-c2b5-4ec4-8b71-f5a6124d5f3d)

* Picture of navigation bar when viewed on mobile screen:
![README_navbar_dropdown](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/a1b7abdc-8501-488a-b47a-80f4597ae888)

* This makes the website easy to navigate on any screen size.

## The About Us section

* The about us section describes the ethos of the library:

![README_about_us](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/f12ff1c4-80d2-43e0-98d9-3e3d47c14f9e)

## Opening Times

* The opening times table allows users to see our business hours in a clear and well laid out way:

![README_opening_times](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/504a8449-cd1b-4e0c-bfbf-603f7c137e49)

## The Services page

* This page displays all of the services on offer in the library with information about each one and an image for clarity.

![README_services_page#1](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/41eb2a77-826c-460c-9c74-2a63caab43c9)
![README_services_page#2](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/3cc5e11d-966f-488f-b999-976137505616)
![README_services_page#3](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/69482169-8433-4410-887f-64460478e4ec)

## The Register page
* This page contains a form for registering for the library along with a short video on the benefits of reading.

![README_register_page](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/0ed68633-b6c6-4690-b298-f0b949a3d19e)


# Testing

* I tested the page in different browsers to make sure it works properly in Chrome, Firefox and Opera.
* I confirmed that the navigation bar and menu still worked and all sections were readable.
* I confirmed that the register form works.

# Bugs

* I found that my images were not showing up in browsers after deploying the site, this was because I used absolute file paths in stead of relative ones. After changing these the images showed up correctly.
* The images and text in the 'services' section were not stacking as I would like them to when I deployed the site. I was able to fix this using media queries.
* I found that the text in the logo migrated down to the div below this when viewd on smaller screens. I suspect this is due to my query media settings. Unfortunately I was not able to fix this bug.

# Validator Testing

##CSS
No errors were found whhen running the code through the official (Jigsaw) validator

![README_CSS_Validation](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/232a4bb1-a0f3-4b0a-b870-d73bd6d6f994)

##HTML
One error was found when running through the official HTML validator, as far as I can see this is not a 'stray end tag' and is actually the closing tag for the above section. (Pictures included):
There was also a suggestion to use alternative syntax for my headers on all three HTML pages, although I found this one to be the one that suited best.

![README_HTML_Validation](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/984df3dc-fb40-4226-9108-32ed52d4e173)

I ran my page through Lighthouse and found it had a high accessibility rating:

![readme_lighthouse](https://github.com/EdwardJWalsh/binghamstown-library/assets/155949281/ad42a6ae-72dc-4d4a-a901-43f52af0cd86)

# Deployment
The page was deplied through GitHub Pages.
The live link can be found here - https://edwardjwalsh.github.io/binghamstown-library/

# Credits
The code made to include the social media links and the media queries was taken from Love Running project, as well as the code for the register form.
The video was uploaded from Youtube at the following link -"https://www.youtube.com/embed/6Py3j3OyRPM"
The images on the site were uploaded from Pexels.com and Stocksnap.com






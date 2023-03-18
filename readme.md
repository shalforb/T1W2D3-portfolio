# Coder Academy - Portfolio

## Overview
This is a portfolio website for displaying the services that Coder Academy provides. This is in development phase and we will keep on adding those features in this readme that we add on to the website.

## Components

### Header
Header has logo and name of the company along with the navigation bar. Here is the code for the header; 
we have:

```html
header {
    background-color: #ffb6b6;
    padding: 16px;
    text-align: center;

    .logo-name {
        margin-bottom: 24px
    }
        .name {
            font-size: 28px;
        }
            .coder-text {
                color: #45A7C5;
            }

            .academy-text {
                color: #1c3C5C;
            }
    .nav-items {
        width: 100%;
        display: flex;
        justify-content: space-around;
        font-size: 18px;

        a {
            text-decoration: none;
            color: #004a60;
        }
    }

}
```

### Footer
Footer has social media links, contact number and address. Here is the code that we have:

```html
<footer>
            <div class="social-media">
                <a href=""><i class="fa-brands fa-github"></i></a>
                <a href=""><i class="fa-brands fa-linkedin-in"></i></a>
                <a href=""><i class="fa-brands fa-instagram"></i></a>
            </div>
            <div class="info">
                <p>Contact: 0404040404</p>
                <p>Address: 1 Street St, Suburb</p>
            </div>
    </footer>
```

### Components
These will contrain the styling of individual components which are as following at the moment:
- Header
- Footer 

### Defaults
This will contain the default variables such as colors, breakpoints, etc/

### Pages
This will contain the styling of each individual HTML pages.

### Services
Services page displays the list of services that we provide. 

### Contact
Contact page can be used to contact the company.
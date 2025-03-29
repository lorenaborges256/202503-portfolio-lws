# Portifolio

## Overview

This is a portfolio website to show the services provided by Lorena Web Solutions. This is currently under development. We will keep on adding new features in the website and readme as we move further.

Write using instruction for assessment, and show what it will present.

## Components
### Header
Header has logoand the name of the company with the navigation bar to different pages such as Home, Services, About and Contact.

```html
<header>
   <div class="logo-name">
        <img src="image/logo.png" alt="logo">
         <p class="name">
            <span class="company-text">Company</span> 
            <span class="name-text" >Name</span>
        </p>
   </div>
    <nav>
        <a href="#">Home</a>            
        <a href="pages/services.html">Services</a>
        <a href="pages/about.html">About</a>
        <a href="pages/contact.html">Contact</a>
    </nav>
</header>
```

### Footer
Footer has social media links and some other information such as contact and address. Here is the code we have for the footer:

```html
<footer>
    <div class="social-media">
        <a href="https://www.facebook.com" target="_blank"> <i class="fa-brands fa-facebook"></i></a>
        <a href="https://www.linkedin.com" target="_blank"> <i class="fa-brands fa-linkedin"></i></a>
        <a href="https://www.whatsapp.com" target="_blank"> <i class="fa-brands fa-square-whatsapp"></i></a>

    </div>
    <div class="info">
        <p>Company Name</p>
        <p>Address: 1 Street, suburb</p>
        <p>Phone</p>
        <p>Email</p>
    </div>
</footer>
```

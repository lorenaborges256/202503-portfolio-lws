# DEV1001-Introduction to Web Development
## Assessment 1 - Portfolio - Individual Programming Project

## Assessment Purpose Overview

The Assessment Purpose of DEV1001 - Introduction to Web Development is to build a website showcase, to future employers, presenting my talent to design, develop and deploy a website by incorporating best practices in HTML and CSS, while adhering to principles of responsive design, accessibility, and user interactivity.

As I am still a student with limited experience and professional projects, I have taken the liberty to create a fictional business name, address, contact details, logo, as well as its vision, mission, and project descriptions, and to complete the content on this website. 

These fictional elements were included to enrich the articles and provide a cohesive structure. However, information about myself—such as my personal background, where I am from, my hobbies and interests, is completely real and authentic. 

## Assessment features

This project includes:
- **Accessible and Semantic HTML Elements:** Using tags like ``` <header>```, ``` <main>```, ``` <section>```, ``` <article>```, ``` <nav>```, and ``` <footer>``` to enhance the website's structure and accessibility.
- **Responsive Design:** Media queries and fluid layouts allow the website to adapt seamlessly across devices, from mobile screens to desktops.
- **Modern CSS Techniques:** Styled using CSS variables, flexbox, and keyframe animations for a professional, modern look.
- **Interactivity:** Smooth animations, hover states, and subtle transitions that enhance user engagement.
- **Cohesive Design Theme:** Consistent colors, fonts, and spacing for visual harmony, aligned with the design brief.

## Errors and Validations
### HTML
All .html files were validated and all have received this message:
**Document checking completed. No errors or warnings to show.**

### CSS
All CSS files were sucesseful validatd by W3C CSS level 3 + SVG  validation tool.

## Credits
- Font Awesome for icons.
- W3 schools CSS Tutorials for Animations and Text Effects inspirations.
- W3C Validator for ensuring HTML and CSS validity.


----------------------------------------------------------------------------


# LWS Lorena Web Solutions

## Website Portfolio Overview

This project is a portfolio website designed to showcase my skills, creativity, coding expertise, and the services offered by Lorena Web Solutions company.

The website has been developed following the best practices of syntactically and semantically valid HTML5 and CSS3, ensuring both accessibility and responsive design. It was built using a mobile-first approach and has been also fully optimized for tablets and larger screens.

The site comprises four pages: **Home**, **Services**, **About Us**, and **Contact**. Each page provides relevant content and incorporates appropriate design elements tailored to different screen sizes, offering a seamless user experience across devices.

Additionally, the website includes animated elements that enhance interactivity by highlighting buttons or displaying essential information relevant to each page.

Further details on these features and design practices are covered in this document.

## Components

### Header and Navigation bar

The header prominently features the company logo, its written name, and a navigation bar. These elements are consistently displayed across all screen sizes, ensuring users can easily navigate and access them throughout the website's pages.

For medium-sized screens, the written company name has been intentionally removed as part of a creative design decision aimed at enhancing clarity and maintaining a streamlined layout. This adjustment reflects thoughtful consideration of user experience and design aesthetics.

```html
<header>
       <div class="logo-name">
            <img src="image/LWS_logo.png" alt="Company logo">
        </div>
        <div class="name">Lorena Web Solutions
        </div>
        <nav>
            <a id="highlight" href="#">Home</a>            
            <a href="pages/services.html">Services</a>
            <a href="pages/about.html">About Us</a>
            <a href="pages/contact.html">Contact</a>
        </nav>
    </header>
```

The navigation bar was designed to visually indicate the active page as you switch between different sections of the website. The current page is highlighted to help users easily identify where they are. To achieve this, a subtle text effect has been applied, adding visual emphasis to the active link. Follow the HTML and CSS part of the code:

```html
<nav>
    <a id="highlight" href="#">Home</a>            
    <a href="pages/services.html">Services</a>
    <a href="pages/about.html">About Us</a>
    <a href="pages/contact.html">Contact</a>
</nav>
```

```css
#highlight{
    color: var(--primary-background);
    font-size: 1.8rem;
    font-weight: bold;
    animation: highlight 3s 4;
}
  
@keyframes highlight {
    50% {text-shadow: 1px 1px 10px var(--primary-background);}
}
```

### Main 

Each page, **Home**, **Services**, **About Us**, and **Contact**, contains its own unique content in the main section, which has been thoughtfully designed to adapt to different screen sizes, ensuring the display of relevant information on any device.

```html
<main>
    <article class="anouncement">
        <div class="anouncement-text">
            <h4>Welcome to Lorena Web Solutions! Let's build something extraordinary together!</h4>
        </div>
    </article>
    <article>
        <div class="company-name-article"> Lorena Web Solutions
        </div>         
        <div class="company-image">
            <img src="image/LWS_workspace.jpg" alt="Company Image Home Page">
        </div>
        .
        .
        .
</main>       
```

To improve navigation, multiple anchor tags have been implemented to connect related content seamlessly. This user-friendly approach allows users to quickly jump between sections without the need to frequently scroll up and down.

```html
.
.
.
    <div class="about-text"> 
        <h2>Who We Are</h2>
        <p>Welcome to Lorena Web Solutions! My name is Lorena, and I am a passionate web developer based (...).
        </p>
    </div>
    <a href="#" class="btn-about">Back to top</a>
</div>                
<div  id="about2" class="about-y2">
    .
    .
    .

```
### Footer

Footer has social media links, Google Maps embeded maps, address, contact information and a form for Subscrib for a Newsletter.

All those elements will be shown at the same time, only on large screen. This decition reflects thoughtful consideration of user experience and design aesthetics.

```html
        <footer>
            <div class="map">	
                <iframe
                    src="https://www.google.com/maps/embed(...)>
                </iframe>
            </div>
            <div class="social-media">
                <a href="https://www.facebook.com/company_name" target="_blank"> <i class="fa-brands fa-facebook"></i></a>
                <a href="https://www.linkedin.com" target="_blank"> <i class="fa-brands fa-linkedin"></i></a>
                <a href="https://www.whatsapp.com" target="_blank"> <i class="fa-brands fa-square-whatsapp"></i></a>            
            </div>
            <div class="social-name">
                <p>Facebook</p>
                <p>Linkedin</p>
                <p>WhatsApp</p>
            </div>
            <div class="info">
                <p class="footer-address">Address: 1234 Main St, Anytown</p>
                <p class="footer-phone">Phone: +61 1234 567 890</p>
                <p class="footer-email">Email: contact@lws.com.au</p>
            </div>
            <div class="subscribe">	
                <h3>Subscribe to our newsletter</h3>
                <form>
                    <label for="fname">Name:</label>
                    <input type="text" id="fname" name="firstname" placeholder="Your name...">
                    <label for="fname">Email:</label>
                    <input type="email" id="email" name="email" placeholder="Your email...">  
                    <input type="submit" value="Subscribe">
                </form>
            </div>
        </footer> 
```

## Future Enhancements

As the course progresses, we will continue to learn more about coding and explore new tools. This knowledge will enable us to develop more engaging pages and dynamic elements, further enhancing this portfolio website.
Planned future improvements include:
- Adding real service sections and expanding content to showcase a wider range of offerings.
- Integrating additional animations to improve interactivity and user engagement.
- Implementing a fully functional contact form with backend support for seamless communication.


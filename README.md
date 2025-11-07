This is a modern, responsive personal portfolio website by Carl Steven Vinluan. It is built as a multi-page static site using HTML, CSS, and vanilla JavaScript, and features a clean, card-based design with a parallax, gradient background.

1\. Pages

a. index.html (Home): A landing page that serves as a summary of the entire portfolio, including a hero section, featured project, personal vision, and a mini contact section.

b. skills.html (Skills): A detailed breakdown of technical, design, and soft skills, organized by category. Features a hide-on-scroll secondary navigation bar.

c. projects.html (Projects): A gallery of projects featuring video players, a scrollable image gallery.

d. about.html (About): A complete "about me" page including a personal bio, education, organizational experience, and interests.

e. contact.html (Contact): A two-column contact page with social media links and a functional contact form.

2\. Features

a. The layout adapts for desktop, tablet, and mobile screens, including a responsive hamburger menu.

b. All content is held in semi-transparent cards with a backdrop-filter blur.

c. Gradient Parallax Background: The animated gradient background is fixed in place, creating a parallax depth effect as the content scrolls over it.

d. Dynamic JavaScript Elements:

d1. Image Lightbox: Clickable gallery images that open in a full-screen modal.

d2. Hide-on-Scroll Nav: The secondary navigation on the Skills page hides on scroll-down and reappears on scroll-up.

e. Functional Contact Form: The contact form is set up to work with [Formspree](https://formspree.io/) to handle email submissions.

f. On-Page Navigation: The Skills page uses scroll-padding-top to ensure anchor links land correctly below the sticky navigation bars.

3\. Technologies used

1. HTML5: For the core structure and content.  
2. Tailwind CSS: Used via the CDN for all styling and layout.  
3. style.css (Custom CSS): A single external stylesheet  
4. JavaScript (Vanilla): For all interactivity, including the mobile menu, image lightbox, and hide-on-scroll navigation.  
5. Formspree: Used as a free, simple backend to make the contact form functional.  
6. Font Awesome: For social media icons on the contact page.
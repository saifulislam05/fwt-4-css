# Camping Gear and Essentials W-T-4 

## Hosted Link: [View Project](https://saifulislam05.github.io/fwt-4-css/)
## Project Description
The "Camping Gear and Essentials" project is a responsive web page that showcases a range of camping gear and services. It includes a header section with navigation links, a hero section with a captivating background, a services section featuring various camping gear, an "About Us" section describing the company's story, mission, vision, and team, and a contact section with contact details and a contact form.



## HTML Structure

### Header Section:
![image](https://github.com/saifulislam05/fwt-4-css/assets/73392705/fa9f701b-61a1-4e32-9df7-4c83830426ed)
- `<header>`: The header section of the web page.
  - `<nav class="navbar">`: Navigation bar.
    - `<h2><a href="#"></a></h2>`: Company logo.
    - `<ul class="nav_items">`: Navigation links.
      - `<li><a href="#"></a></li>`: Individual navigation items.
### Hero Section:
![image](https://github.com/saifulislam05/fwt-4-css/assets/73392705/e312de4c-7666-473e-bf91-deda6ba30125)

- `<section class="hero">`: Hero section with background image and content.
  - `<div class="overlay">`: Semi-transparent overlay.
  - `<div class="content">`: Content within the hero section.
    - `<h1></h1>`: Title.
    - `<p></p>`: Description.
    - `<a href="#services" class="btn"></a>`: Button to navigate to services section.
### Service Section: 
![image](https://github.com/saifulislam05/fwt-4-css/assets/73392705/7d190c9c-c267-4480-86cf-c7023ffc6bc5)

- `<section class="services" id="services">`: Services section showcasing camping gear.
  - `<h2 class="title"></h2>`: Section title.
  - `<p class="titles-para"></p>`: Section description.
  - `<div class="cards">`: Container for service cards.
    - `<div class="card">`: Individual service card.
      - `<img src="service-image.jpg" alt="Service">`: Image.
      - `<h3>Service Name</h3>`: Service name.
      - `<p>Service description.</p>`: Service description.
### About Section:
![image](https://github.com/saifulislam05/fwt-4-css/assets/73392705/f9d0f268-fe32-47c3-873a-b47dd5aec98e)

- `<section class="about" id="about">`: About Us section.
  - `<h2 class="title"></h2>`: Section title.
  - `<p class="titles-para"></p>`: Section description.
  - `<div class="row company-info">`: Company information.
    - `<h3>Our Story</h3>`: Story title.
    - `<p>Company story description.</p>`: Story description.
  - Similar structure for mission, vision, and team information.
### Contact Section:
![image](https://github.com/saifulislam05/fwt-4-css/assets/73392705/6895d0ba-f28d-41e5-a7ec-488b49bdb4f1)

- `<section class="contact" id="contact">`: Contact Us section.
  - `<h2 class="title">Contact Us</h2>`: Section title.
  - `<p class="titles-para">Reach out to us for any inquiries or feedback.</p>`: Section description.
  - `<div class="row">`: Contact information and form.
    - `<div class="col information">`: Contact details.
      - Address, email, phone, working hours, etc.
    - `<div class="col form">`: Contact form.
      - `<form>`: Form fields for name, email, message, and a "Send Message" button.

## CSS Styles

### Global Styles (`*`)
- Resets margin, padding, and box-sizing for all elements to create a consistent layout.

### HTML and Body (`html`, `body`)
- `scroll-behavior: smooth;`: Adds smooth scrolling behavior to anchor links.

### Container (`<div class="container">`)
- `.container`:
  - `width: 100%;`: Makes the container span the entire width.
  - `max-width: 1200px;`: Sets the maximum width of the container to 1200 pixels.
  - `margin: 0 auto;`: Centers the container horizontally.

### Header Section (`header`)
- `.navbar`: Styles the navigation bar in the header.
  - `background: #333;`: Sets the background color of the navigation bar.
  - `position: fixed;`: Fixes the navigation bar at the top of the viewport.
  - `top: 0; left: 0;`: Positions the navigation bar at the top-left corner.
  - `z-index: 10;`: Sets the stacking order of the navigation bar, ensuring it's above other elements.
  - `color: #ffffff;`: Sets the text color in the navigation bar.

- `.nav_items`: Styles the navigation items within the navigation bar.
  - `display: flex;`: Arranges the navigation items in a horizontal line.
  - `list-style: none;`: Removes the list-style bullet points.
  - `justify-content: space-between;`: Distributes the navigation items evenly.
  - `align-items: center;`: Vertically centers the navigation items.
  
- `.navbar a`: Styles the navigation links.
  - `color: #ffffff;`: Sets the text color of the navigation links.
  - `text-decoration: none;`: Removes underlines from the links.

- `.navbar a:hover`: Styles the navigation links on hover.
  - `color: #ddd;`: Changes the text color on hover.

### Hero Section (`section.hero`)
- `.hero`: Styles the hero section.
  - `height: 100vh;`: Sets the hero section's height to 100% of the viewport height.
  - `background`: Sets the background image and properties.
  - `background-position: center 65%;`: Specifies the background image's position.
  - `background-size: cover;`: Makes the background image cover the entire section.
  - `background-attachment: fixed;`: Fixes the background image in place.

- `.hero .overlay`: Styles the overlay element within the hero section.
  - `height: 100%; width: 100%;`: Makes the overlay cover the entire section.
  - `background: rgba(0, 0, 0, 0.2);`: Sets a semi-transparent black overlay.

- `.hero .content`: Styles the content within the hero section.
  - `display: flex;`: Arranges content in a flex container.
  - `height: 85%;`: Sets the height of the content within the hero.
  - `align-items: center; justify-content: center;`: Vertically and horizontally centers the content.
  - `flex-direction: column;`: Stacks content vertically.

- `.hero .content h1`: Styles the title within the hero section.
  - `font-size: 60px; font-weight: 700;`: Sets the font size and weight.

- `.content a`: Styles the button within the hero section.
  - `margin`, `padding`, `display`, `color`, `text-transform`, `font-size`: Styles for the button.
  - `border-radius`: Rounds the button's corners.
  - `background`, `border`, `transition`, `box-shadow`: Background, border, and hover effects.
  - `text-decoration: none;`: Removes underlines from the button.

### Services Section (`section.services`)
- `.services`: Styles the services section.
  - `padding: 80px 0 0;`: Adds top padding to the services section.

- `.title`: Styles the section title.
  - `font-size: 2rem;`: Sets the font size for the title.

- `.titles-para`: Styles the section description.
  - `text-align: center;`: Centers the text.

- `section .cards`: Styles the container for service cards.
  - `display: flex; flex-wrap: wrap;`: Arranges the cards in a flex container.
  - `max-width: 1200px; margin-top: 50px; padding: 0 10px;`: Sets the maximum width, top margin, and horizontal padding for the container.

- `section .cards .card`: Styles individual service cards.
  - `background`, `padding`, `border-radius`, `box-shadow`: Card background and styling.
  - `margin-bottom`, `width`: Spacing and card width.

- `.services .card img`: Styles the service card images.
  - `width`, `height`: Sets image dimensions.
  - `margin-bottom`, `border-radius`, `object-fit`: Additional styling for images.

### About Section (`section.about`)
- `.about`: Styles the About Us section.
  - `padding: 80px 0 0;`: Adds top padding to the About Us section.

- `.about h3`: Styles the subheadings within the About Us section.
  - `margin`: Sets margin for subheadings.

- `.about .company-info`: Styles the container for company information.
  - `margin-top: 30px;`: Adds top margin.

- `.about .row`: Styles the rows within the About Us section.
  - `padding: 0 10px;`: Adds horizontal padding to rows.

- `.about .team`: Styles the team information section.
  - `text-align: left; width: 100%;`: Aligns text to the left and sets width to 100%.

- `.about .team ul`: Styles the team members' list.
  - `padding-left: 20px;`: Adds left padding to the list.

### Contact Section (`section.contact`)
- `.contact .row`: Styles the rows within the Contact Us section.
  - `margin: 60px 0 90px; display: flex; max-width: 1200px; width: 100%; align-items: center; justify-content: space-between;`: Sets margin, flex layout, max-width, alignment, and spacing for rows.

- `.contact .row .col`: Styles the columns within the Contact Us section.
  - `padding: 0 10px; width: calc(100% / 2 - 50px);`: Sets padding, width, and calculates column width.

- `.contact .col p`: Styles the contact information within columns.
  - `margin-bottom: 10px;`: Adds bottom margin to contact information.

- `.contact .col p i`: Styles the icons within contact information.
  - `color: #7a7a7a; margin-right: 10px;`: Sets color and right margin for icons.

- `.contact form input`: Styles the input fields within the contact form.
  - `height: 45px; margin-bottom: 20px; padding: 10px; width: 100%; font-size: 16px; outline: none; border: 1px solid #bfbfbf;`: Sets input field dimensions, margin, padding, font size, and border.

- `.contact form textarea`: Styles the textarea within the contact form.
  - `padding: 10px; width: 100%; font-size: 16px; height: 150px; outline: none; resize: vertical; border: 1px solid #bfbfbf;`: Sets textarea dimensions, padding, font size, and border.

- `.contact form button`: Styles the "Send Message" button within the contact form.
  - `margin-top: 10px; padding: 10px 20px; font-size: 17px; color: #fff; border: none; cursor: pointer; border-radius: 5px; background: #333; transition: 0.2s ease;`: Sets margin, padding, font size, color, border, cursor, border-radius, and background for the button.

- `.contact form button:hover`: Styles the button on hover.
  - `background: #525252;`: Changes the background color on hover.




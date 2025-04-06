Responsive Design Meta Tag:

html
Copy
Edit
<meta name="viewport" content="width=device-width, initial-scale=1.0">
This allows the website to adapt to different screen sizes, making it mobile-friendly.

Internal CSS Styling: CSS is embedded inside the <style> tag. It defines styles for layout elements such as the navigation bar, images, and responsiveness through media queries.

2. Navigation Bar
The navigation bar (<ul class="ulis">) is styled with a dark background and contains five menu items:

Home

Skills

About

Projects

Contact (aligned to the right)

Each list item (<li class="lis">) uses float: left, except the "Contact" tab, which is floated to the right. Links use a hover effect and an active class to highlight the current section.

Styling Highlights:
css
Copy
Edit
li a:hover:not(.active) {
  background-color: #111;
}
.active {
  background-color: #5d4eab;
}
These create a clear, professional visual effect that improves user navigation.

3. Home Section
The Home section (<section id="home">) serves as the personal introduction of the developer. It includes:

A circular profile photo

A large, welcoming heading

A paragraph that introduces Abhinav’s background in full-stack development

Notable Image Styling:
css
Copy
Edit
img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
}
This CSS ensures the profile image is displayed in a clean, circular format, giving the page a personal touch.

4. About Section
 It is enclosed in a <fieldset> with a <legend> tag labeled "About Me", which gives it a styled and grouped appearance.

5. Skills Section
The Skills section follows the same <fieldset> and <legend> pattern, with a detailed paragraph explaining:

6. Projects Section
The Projects section presents Abhinav’s practical work using a description list (<dl>). Each project is listed with a title (<dt>) and a short description (although <dl> is used again instead of <dd>, which is a minor HTML error).
7. Contact Section
The contact section provides multiple ways to reach Abhinav:

A clickable phone number using tel:

An email link using mailto:

A GitHub link opening in a new tab (target="_blank")

This makes the site interactive and user-friendly, allowing visitors to quickly get in touch.

8. Footer
The footer contains a simple copyright:

html
Copy
Edit
<p>&copy; 2025 My Portfolio</p>
It gives a professional finishing touch and reinforces the portfolio’s ownership.

9. Responsive Design and Media Queries
The code includes media queries for devices with screen widths below 768px and 480px.

Examples:
css
Copy
Edit
@media (max-width: 768px) {
    .intro {
        flex-direction: column;
        text-align: center;
     }
}
The layout changes to column format on smaller screens

Font sizes and paddings are adjusted for readability

The image is centered

These changes ensure the website looks clean and functions well on smartphones and tablets.


and in project section i added an html file in <a> tag it explains the projects that are displayed in project section.

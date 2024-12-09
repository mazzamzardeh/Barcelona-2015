# who targets the project!

# my project targets fans of FC Barcelona, especially those interested in the club's historic 2015 treble-winning season. 

The site is designed for:

    - the People who want to relive iconic moments of Barcelona’s success.
    and the Fans interested in their favorite players, matches, and achievements.

    -  it also targets the Sports Historians: Those studying the impact of legendary teams like Barcelona's 2015 squad.
    -  Casual Visitors: Individuals looking for visually appealing and informative content about football.

The website is educational and entertaining, catering to a wide range of users who share an interest in FC Barcelona or football history.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

# what it includes ? 

   1- Homepage: Welcomes visitors with an introduction and navigation links to other pages.

   2- Matches Page: Highlights key matches (Champions League final, FIFA Club World Cup, UEFA Super Cup, and El Clasico), with results, goal scorers, and club logos.

   3- Players Page: Showcases the star players of 2015 (Messi, Neymar, Suárez) with photos and descriptions of their achievements.

   4- Contact Page: Displays developer details with a stylish contact form and animated background.

   5- Styling: Uses HTML and CSS, with features like animations, flexbox, and a responsive design.

   6- Media: Includes high-quality images and logos, ensuring a visually appealing experience.

   7-  and the website also includes Navigation: A header with a navbar and a footer with links to social media (like Instagram).

   8- Dynamic Features: Background animations and transitions for engaging visuals.

   :::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

# important css :

   1- Flexbox:

    To align and distribute content evenly, like centering the navigation bar and arranging player cards.
    Example:

    display: flex;
    justify-content: center;
    align-items: center;

   2- Backgrounds and Animations:

    Adding stylish backgrounds and making them dynamic with keyframes.
    Example:

    background: url('image.jpg') no-repeat center/cover;
    @keyframes moveBackground {
        0% { background-position: 0 0; }
        100% { background-position: 100% 100%; }
    }

   3- Responsive Design:

    Media queries ensure the site looks good on all devices.
    Example:

    @media (max-width: 768px) {
        .player-card {
            width: 100%;
        }
    }

   4- Styling Buttons:

    Hover effects for interactivity.
    Example:

    .back-button:hover {
        background-color: goldenrod;
    }

   5- Pseudo-elements:

    Creating decorative elements, like a background overlay.
    Example:

    body::before {
        content: '';
        position: fixed;
        background: rgba(0, 0, 0, 0.5);
    }

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

# issues i faced 

One of the challenges I faced during the project was when I published the website online. The background images on some pages were not showing as expected, even though everything worked perfectly when I ran the website locally on my computer. This issue was caused by incorrect file paths. After investigating, I realized the file paths needed to match the structure required for deployment, especially since GitHub Pages treats paths differently than a local environment. By correcting the paths and useing single quotes (' ' ) and ensuring the images were accessible, I resolved the issue and the background images displayed properly.

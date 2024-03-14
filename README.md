# ERPpage
A basic web page of ERP system

![image](https://github.com/Alolika-22/ERPpage/assets/76674148/bae2f6fe-1edc-493b-a65c-f0d9e8233cf7)

This is the first page 

CSS Styling:

body: Sets up a flexbox layout for content both horizontally and vertically within the viewport. It also defines a background color.
.welcome-text: Styles the welcome text with a large font size, bold weight, and centers it within its container.
.button: Styles the buttons with a background color, text color, padding, border, and cursor pointer. It also defines transition effects for hover and click states.
.button:hover and .button:active: Define styles for button hover and active states, respectively, changing the background color and applying a box-shadow and translation effect.
Content:

Inside the <body> element, there's a <div> with the class container, containing the welcome text and a series of buttons for navigation purposes. Each button is styled using the .button class, and the onclick attribute specifies the action to be performed when the button is clicked, navigating to different HTML pages using JavaScript's location.href.
Functionality:

The buttons are interactive and serve as links to different pages of the ERP system (dashboard.html, product-management.html, ordermanagement.html, order-calendar-view.html). They use JavaScript's location.href to navigate to the specified URLs when clicked, effectively allowing users to move between different sections of the 

When we click on the dashboard then this page is visible

![image](https://github.com/Alolika-22/ERPpage/assets/76674148/9abc11e9-e15d-430a-aa06-cc98129f2998)

HTML Structure:
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Defines the viewport settings for responsive web design.
<title>Dashboard</title>: Sets the title of the webpage displayed in the browser tab.
<link rel="stylesheet" href="styles.css">: Links an external CSS stylesheet named "styles.css" to apply styling to the HTML content.

CSS Styling:

body: Resets margin and padding to zero, sets the font family to Arial or sans-serif, and specifies a background color for the entire webpage.
dashboard: Styles the container for the dashboard content, setting its width to 80% of the viewport, centering it horizontally, applying padding, border radius, and box shadow, and setting its background color.
metrics: Uses flexbox to display the metrics side by side with space evenly distributed between them.
actions: Styles the container for action buttons and individual buttons, respectively, defining padding, background color, text color, border radius, and hover effects.


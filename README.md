# Responsive Carousel 

This project is a responsive carousel component that can be easily integrated into any website or web application. It allows users to cycle through a set of images or content in a visually appealing and user-friendly manner.
![Screen](https://github.com/AndyMagwayer/responsive-carousel/blob/main/Screenshot%202023-11-28%20213208.png)

## Deploy: https://responsive-carousel-ak.netlify.app/
## Features


- Responsive design: The carousel adapts to different screen sizes and devices, providing an optimal viewing experience for users.
- Touch and swipe support: Users can navigate through the carousel using touch gestures on mobile devices.
- Keyboard navigation: Users can also navigate through the carousel using keyboard arrow keys.
- Customizable: The carousel offers various options for customization, including the ability to change the transition effects, autoplay settings, and more.
- Accessibility: The carousel is designed to be accessible to all users, with proper keyboard focus management and ARIA attributes.

## Installation

To use the responsive carousel in your project, follow these steps:

1. Clone the repository: `git clone https://github.com/AndyMagwayer/responsive-carousel.git`
2. Include the necessary CSS and JavaScript files in your HTML file:

html
<link rel="stylesheet" href="path/to/carousel.css">
<script src="path/to/carousel.js"></script>
3. Add the HTML markup for the carousel in your HTML file:

html
<div class="carousel">
  <div class="carousel__track">
    <!-- Add your carousel items here -->
  </div>
  <div class="carousel__nav">
    <button class="carousel__prev">Previous</button>
    <button class="carousel__next">Next</button>
  </div>
</div>
4. Initialize the carousel in your JavaScript file:

javascript
const carousel = new Carousel('.carousel');
carousel.init();
## Usage

Once the carousel is properly installed, you can add your own content or images to the carousel by adding HTML markup inside the `.carousel__track` element. Each item should be wrapped in a `
` with the class `carousel__item`.

html
<div class="carousel__track">
  <div class="carousel__item">
    <!-- Add your content or image here -->
  </div>
  <div class="carousel__item">
    <!-- Add your content or image here -->
  </div>
  <!-- Add more carousel items here -->
</div>
You can customize the carousel by modifying the CSS classes or by changing the options provided by the JavaScript file. Refer to the [documentation](docs/README.md) for more information on customization options.

## Contributors

- [Andy Magwayer](https://github.com/AndyMagwayer)

## License

This project is licensed under the [MIT License](LICENSE).

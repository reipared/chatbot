# Chatbot

This project implements a simple customer chat interface with HTML, SCSS, and JavaScript.

## Table of Contents

- [Chatbot](#chatbot)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Usage](#usage)
    - [Installation](#installation)
    - [Integration](#integration)
    - [SCSS Customization](#scss-customization)
  - [Live Demo](#live-demo)
  - [Dependencies](#dependencies)
  - [License](#license)

## Overview

The customer chat interface provides a clean and responsive design for engaging with users. It includes a chat box, a chat button, and a modal for adding extra content.

## Features

- Open and close the chat box with a click on the chat button.
- Display and hide additional content with a modal.
- Responsive design for various screen sizes.

## Usage

### Installation

1. Download the necessary HTML, SCSS, and JavaScript files.
2. Link external dependencies such as Font Awesome, Google Fonts, and jQuery.

### Integration

Include the following code snippet in your HTML file:

```html
<!-- Add the necessary HTML structure -->

<!-- Include external dependencies -->
<link
	rel="stylesheet"
	href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
/>
<link
	rel="stylesheet"
	href="https://fonts.googleapis.com/css?family=Raleway|Ubuntu&display=swap"
/>
<script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>

<!-- Include your SCSS and JavaScript files -->
<link rel="stylesheet" href="path/to/styles.css" />
<script src="path/to/script.js"></script>
```

1. Customize the chat box and styles to fit your application. The SCSS files are provided for easy customization.

### SCSS Customization

The SCSS file(`styles.scss`) are structured for modularity and easy customization. You can modify variables, adjust styles, or add your own styles based on your project requirements.

## Live Demo

You can preview the chatbot [here](https://chatbot.reipared.com/)

## Dependencies

- [Font Awesome](https://fontawesome.com/) - Icon library used for chat icons.
- [Google Fonts](https://fonts.google.com/) - Fonts used for styling (Raleway and Ubuntu).
- [jQuery](https://jquery.com/) - JavaScript library for DOM manipulation (ensure it's included before your script).

## License

This project is licensed under the [MIT License](#license)

# ImagesGallery

A responsive image gallery created using HTML and CSS with Flexbox.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

## Introduction

This project demonstrates the use of Flexbox to create a responsive image gallery. The layout automatically adjusts to different screen sizes, ensuring a user-friendly experience on all devices.

## Features

- Fully responsive design powered by Flexbox
- Clean and minimalistic layout
- Easy to expand with additional images or customization

## Installation

To run this project locally:

git clone https://github.com/OlenaMyroshnykova/ImagesGallery.git
cd ImagesGallery
open index.html
# or
start index.html
# or for Linux
xdg-open index.html

## Usage

To customize the gallery:

Add your images to the images directory:

cp /path/to/your/images/* images/

Modify the index.html file to include your new images:

<div class="gallery">
  <img src="images/your-image.jpg" alt="Your Image Description">
</div>

Modify the styles.css file to adjust the Flexbox layout as needed:

.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.gallery img {
    max-width: 100%;
    height: auto;
    margin: 10px;
}

## Technologies

HTML5: Markup structure of the gallery  
CSS3: Styling, including Flexbox for layout management

## Contributing

Contributions are welcome! Feel free to submit suggestions or improvements.

## Authors

Olena Myroshnykova - Initial work - GitHub Profile

See also the list of contributors who participated in this project.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

# QR Code Component

Frontend Mentor is a website where front-end developers get a design and are asked to make it into a page to practice their skills. This repository is my approach for the following design: https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H

If you want to see this repository live you can do it here: https://avoscanemile.github.io/qr-component/

## HTML Structure

The HTML structure consists of the following key elements:

- `main` with the class `card`: This is the main container for the QR code and text.
- `img` with the class `card__img`: This is the element that displays the QR code image.
- `div` with the class `card__container`: This container holds the text elements.
- `h1` with the class `card__title`: This element displays the title text.
- `p` with the class `card__txt`: This element displays the descriptive text.

The HTML is semantically structured to create a card-like component with an image and accompanying content.

## CSS Styling

The CSS styling is done using CSS variables, ensuring easy customization. Here's a brief overview of the CSS styles and the purpose they serve:

- `:root` defines CSS variables (custom properties) to set colors, font styles, and font sizes.
- `html` and `*` apply general styling for the entire webpage, ensuring a consistent box model.
- `body` styles the background color and centers the content both horizontally and vertically using flexbox.

### Main Styling

- `.card` styles the card container. It has properties for width, margin, padding, border radius, background color, text alignment, and box shadow.
- `.card__img` styles the QR code image. It gives it a border radius for a rounded appearance.
- `.card__container` sets the maximum width for the content container.
- `.card__title` styles the title text with custom font size, font weight, and color.
- `.card__txt` styles the descriptive text with a custom color and font size.

## CSS Modules Used

- **CSS Functions**:
  - `clamp()`: Used for various aspects of the project, including font sizes, minimum and maximum width, and responsive design.
  
- **Layout Techniques**:
  - **CSS Flexbox**: Flexbox is used to create the column layout for the card container, ensuring proper alignment of elements.

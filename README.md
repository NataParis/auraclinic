## Aesthetic clinic website

This is a website dedicated to promoting and showcasing beauty services for women. It has been developed using HTML, CSS, BEM (Block-Element-Modifier), Bootstrap methodology and SCSS to ensure the quality of the codebase.

## Features

Index: Landing page with presentation of clinic.
Catalog Page: Details about various services provided.
Confidentiality policy Page: Area dedicated to legal requirements and personal data protection consent.
Registration Page: Form to be completed by potential customers for subscription on one of the chosen services (for further backend conversion).

## Technologies Used

- HTML5: Provides the structure of the web pages
- BEM Methodology: Organizes and names CSS classes for better structuring
- CSS: Styles the elements and layouts of the website in preprocessor scripting

## How to Use

Clone the repository: git clone https://github.com/yourusername/organic-food-website.git](https://github.com/NataParis/auraclinic.git

Work in your local branch on individual tasks, then make pull requests for review and merging with Master project

## Contributors

- Contributor: https://github.com/LydiaEire
- Contributor: https://github.com/AnzhelaR2202
- Contributor: https://github.com/NataParis
- Contributor: https://github.com/yana-mysh
- Contributor: https://github.com/alinarbcv

## Positioning of elements

This project is based on mixed approach using the Bootstrap framework for galleries as well as flex and grid based positioning

## Adoptive design

The loffowing sizes should be used in media queries:

- Mobile: max-width 360px;
- Tablet: max-width: 768px;
- Desktop: max-width: 1024px;

## BEM methodology

BEM assumes the division of your components to blocks, elements and modificators. This allows better recognition of classes used in code and supports simplier application of styles in templates

#### Example of classes structure BEM:

- `.block` - parent block like `.product-card`.
- `.block__element` - element inside parent block like `.product-card__title`.
- `.block--modifier` - block modificator with special feature like `.product-card--highlighted`.

### SCSS (Sass) Files structure

Files of SCSS type are placed in folder style and divided into smaller subtypes for simplier hierarchy of style support:

- `style.scss` - main SCSS file uniting all style components
- `_vars.scss` - variables like color, siwes, fonts
- `_mixins.scss`- file for repetitive styles
- `_template.scss` - file for basic blocks of website used in the same format on different pages
- `_components.scss` - file with styles for small repetitive components like buttons, product/service cards, interactive fields

### SCSS (Sass) Files structure

The images were copied from the following free resources:
www.freepik.com
www.istockphoto.com
www.canva.com

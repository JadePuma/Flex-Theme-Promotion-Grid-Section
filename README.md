# Promotion Grid

## Description

The Promotion Grid section is a versatile component designed to showcase collections, products, pages, and articles in a grid layout. Created by JadePuma, this section allows merchants to highlight key areas of their store in an engaging and visually appealing manner. With customizable settings for text alignment, image overlay, and the number of items per row, the Promotion Grid can be tailored to fit the design and functionality needs of any Shopify store.

## Features

- Display collections, products, pages, and articles in a customizable grid layout.
- Configurable text alignment and title display settings.
- Customizable overlay for images with adjustable opacity and text color.
- Responsive design for optimal viewing on desktop and mobile devices.
- Supports animation effects for when the grid appears on the screen.

## Requirements

To use the Promotion Grid section, you must have:
- Shopify's Flex theme or any compatible theme that supports sections.
- The following snippets included in your theme:
  - `color_to_rgba`
  - `collection_card`
  - `product_card`

## Snippets Needed

Ensure the following snippets are included in your theme for the Promotion Grid section to function correctly:

- `snippets/color_to_rgba.liquid`
- `snippets/collection_card.liquid`
- `snippets/product_card.liquid`
- `snippets/button.liquid`
- `snippets/column-width.liquid`
- `snippets/heading.liquid`

### Snippets Needed for Snippets

These snippets depend on certain values for their proper functionality and may require additional snippets to fully function within the Promotion Grid section. Below is a detailed explanation:

#### collection_card.liquid and product_card.liquid

- **collection/product**: The respective object to be displayed.
- **image**: An optional image object; if not provided, the default image from the collection or product is used.
- **title**: The title to be displayed on the card. If not provided, the collection's or product's title is used.
- **button_label**: The text for the call-to-action button.
- **promos_per_row**: Determines the number of promotions to display per row.
- **toggle_title**: A boolean value that controls whether the title is shown below the image or overlaid (applicable only for `collection_card.liquid`).

#### button.liquid

Renders a call-to-action button. Requires:
- **label**: The text of the button.
- **href**: The URL the button links to.
- **style**: The style class to apply to the button.

#### column-width.liquid

Determines the width of each promotion card based on the number of items per row. Requires:
- **value**: The number of promotions per row.

#### heading.liquid

Renders the section heading. Requires:
- **title**: The text of the heading.
- **heading_tag**: The HTML tag to use for the heading, e.g., `h2`.
- **text_alignment**: The alignment of the heading text.

#### Additional Dependencies

- `snippets/image-element.liquid`: Used within `collection_card.liquid` and `product_card.liquid` for rendering images with specific cropping and sizing. Essential for handling the visual representation of collection or product images.

By ensuring these snippets are included and properly configured in your theme, the Promotion Grid section can be fully functional and customized to fit the design and functionality needs of your Shopify store.

## Tutorial Video


## Installation

1. Copy the section code into a new `.liquid` file within the `sections` directory of your Shopify theme.
2. Include the required snippets in your theme’s `snippets` directory.
3. Add the Promotion Grid section to your desired page through the Shopify theme editor.

## Usage

To use the Promotion Grid section in your store:

1. Navigate to the page where you want to include the Promotion Grid in the Shopify theme editor.
2. Click 'Add Section' and select the Promotion Grid section.
3. Configure the section settings according to your preferences, such as the number of promotions per row, alignment, and overlay settings.
4. Add blocks to the section for collections, products, pages, or articles you wish to feature.

## Configuration

The Promotion Grid section offers several settings for customization:

- Header text and alignment.
- Number of items per row for desktop and mobile views.
- Image overlay color and opacity.
- Text color and font size within the overlay.
- Button styles for call-to-action links.

## Compatibility

The Promotion Grid section is designed to be compatible with Shopify's Flex theme. It may require adjustments for use with other themes.

## Changelog

### [1.0.0] - 2024-01-02
#### Added
- Initial release of the Promotion Grid section.
- Support for collections, products, pages, and articles.
- Customizable overlay and text settings.

## License

This section is provided under the MIT License. See the LICENSE file in the repository for full details.

## Support

For support with this section, please refer to the tutorial provided by JadePuma at [https://jadepuma.com/blogs/shopify-tutorials/promotions-grid-section-for-the-flex-theme](https://jadepuma.com/blogs/shopify-tutorials/promotions-grid-section-for-the-flex-theme)

## Credits

Created by JadePuma - [https://jadepuma.com](https://jadepuma.com)

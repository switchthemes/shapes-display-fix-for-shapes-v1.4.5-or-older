> [!NOTE]
> This repository contains files for updating Shapes v1.4.5 or older. If you’re updating Shapes v2.0.0 or newer, use the files in [this repository](https://github.com/switchthemes/shapes-display-fix).

# Display issue fix for Shapes theme

To manually fix the high pixel density display issue in Shapes theme, you require the files in this repository.

> For more information about the issue, refer to [our help guide](https://help.switchthemes.co/shapes/updates/display-issue).

## Steps to fix manually:

1. Replace the following files in your theme with the files included in this repository:

   - assets/block-sticker.css
   - sections/call-to-action.liquid
   - snippets/block-sticker.liquid
   - snippets/media-image-placeholder.liquid
   - snippets/media-image.liquid
   - snippets/product-tile-media-image.liquid
   - snippets/static-sticker.liquid

1. Copy the css from the `additional-styles.css` file, and then add it to the bottom of your `base.bundle.css` or `custom.css` file.
## PDF High Contrast and Black & White/ Grayscale Converter on macOS using Automator

This is a simple Automator workflow that converts a PDF file to high contrast black and white. To install, download the release from <https://github.com/z-aki/pdf_high_contrast_bnw_macos_automator/releases/latest> and open the `.workflow` file with "automator installer".

## High Contrast of PDF

Right click on a single PDF file in Finder, then select "quick action" > "pdf_high_contrast".

The output will be saved in the same directory as the original PDF file with the suffix `_contrast.pdf`.

The temporary file will be in `/tmp` folder

## Downsize Image

This is a simple Automator workflow that downsizes selected images (PNG/JPEG etc) to 50% of their original size. Repeated usage will continue to downsize the image by 50% each time.

Right click on a image files in Finder, then select "quick action" > "downsize_image".

The resulting images will be in the same folder as the first image file with the suffix. Original files are not modified.

## Reduce Gamma of PDF

This reduces the gamma of a PDF file to reduce its contrast. This is useful for PDFs that are too dark or have too much contrast. It can also be used just before the above high-contrast workflow for such PDFs.

## Subscribe to new releases

With github account: watch button on the top right of the repository page.

Without github account: RSS feed
<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/refs/heads/6.x/svgs/solid/square-rss.svg" width="50" height="50"> <https://github.com/z-aki/pdf_high_contrast_bnw_macos_automator/releases.atom>

Blog: <https://z-aki.github.io/automator/automator/>

## Screenshots:

![Right Click PDF](img_right_click_pdf.png)
![Comparison](img_compare.png)
![System Preferences](img_sys_pref.png)

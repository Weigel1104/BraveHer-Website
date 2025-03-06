# BraveHer Website Deployment Guide

## Usage Instructions

1. Copy the entire `src` folder to the target computer
2. Ensure the target computer has an internet connection
3. Simply double-click `src/index.html` to browse the website

## Image Optimization Details

To reduce website size and improve loading speed, this website uses the following image optimization strategies:

1. All images use Unsplash's online placeholder image service
2. Images are controlled through CSS for size and display, ensuring uniform appearance
3. Gradient backgrounds are used during image loading for better user experience
4. All images have appropriate alt text for improved accessibility

## Important Notes

- The website uses CDN to load fonts and icons, requiring an internet connection
- All pages use relative paths, no special server configuration needed
- To modify styles, edit the corresponding CSS files in the `src/styles` directory
- If the target computer cannot connect to the internet, refer to the offline deployment branch for a complete offline version

# BraveHer Website Local Deployment Guide

To make the website run completely offline, prepare the resource files according to these steps:

1. Font Files
   Download the following font files and place them in the `src/assets/fonts/` directory:
   - Poppins-Light.woff2
   - Poppins-Regular.woff2
   - Poppins-Medium.woff2
   - Poppins-SemiBold.woff2
   - Poppins-Bold.woff2

   Fonts can be downloaded from Google Fonts: https://fonts.google.com/specimen/Poppins
   
2. Font Awesome Icons
   Download the following files and place them in the corresponding directories:
   - Place the `all.min.css` file in the `src/assets/css/` directory
   - Place all files from the `webfonts` folder in the `src/assets/icons/` directory

   Font Awesome files can be downloaded from: https://use.fontawesome.com/releases/v6.0.0/fontawesome-free-6.0.0-web.zip

3. Image Resources
   All image resources are already included in the `src/images` directory.

## Usage Instructions

1. Download and prepare all the resource files mentioned above
2. Copy the entire `src` folder to the target computer
3. Simply double-click `src/index.html` to browse the website

## Important Notes

- All pages use relative paths, so no special server configuration is needed
- All resources are referenced locally, ensuring a complete offline browsing experience
- To modify styles, edit the corresponding CSS files in the `src/styles` directory 
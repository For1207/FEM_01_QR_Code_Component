# Frontend Mentor - QR code component

## The challenge

The challenge was to build out this QR code component and get it looking as close to the design as possible using HTML and CSS. The initial starter code for the project is provided by the  [Frontend Mentor] (https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H/hub).
The design files for a mobile and a desktop version can be found in `/design` folder.

## Implementation

At first step the author reworked index.html as follows:

- Added links to Google Fonts' 'Outfit' font.
- Created to div's to structure the content with class names `.main` and `.footer`.
- Linked the external stylesheet styles.css.

The rest of the work was done at `style.css`. The challenge suggests that designs should be recreated for two screen widths: 375px and 1440px and is not to be responsive. Following this logic the author used absolute CSS units. Using `@media` allowed him to use one css-file to style both: mobile and desktop designs and keep the project simple.

## Conclusion

The project recreates QR code component for mobile and desktop screen but because it is not responsive, it looks good at 375px and 1440px or around those screen widths values.

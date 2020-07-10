# ochre
Open resources for working with data published from the OCHRE platform.

## Structure
The TEMPLATE repository is the basic structure and files needed to create a splash page for a data-driven OCHRE site.
The template is based on the Tiwanaku project in OCHRE, so you will see images and other details specific to that project.
Replace any and all images with your own images.

## Contents
### Assets
Save your splash images here.

### CSS
Rename the TEMPLATE.css file to your own project name, then update the path in the index.html document %%TEMPLATE.css /
You may edit the css file directly or use the SASS css editing language.
If you opt NOT to use SASS, you can delete the sass directory and the .css.map file in the CSS directory.

### Icons
These files should create useful favicons in browsers and mobile links.

### Images
We include some OCHRE images for branding purposes. We ask that you use these somewhere on the webpage.

### Scripts
The required Bootstrap files are included in this template package so this page may be viewed offline.
Before going live, consider loading Bootstrap and the other scripts using a CDN instead.
Also included is a script to launch the ochreCSV.html page. See the Downloads section for details.

## Update fields in the index.html file
The fields and values to change have been marked with two percentage signs %%.
Search for %% and update the information to the desired value.
Add or remove HTML elements as needed.
Add any needed visual assets to the assets directory.
Included near the end of this page is the option to link to a page that serves as a Guide to you data. ODS can host this page if you write it.
Most of the classes used in this document are formatted by the included Bootstrap library.

## Downloads
### Default set
If the set has been consigured to allow downloads, then the HTML page will include a download button automatically. You do not need to change a thing.
### Alternate set
You may wish to allow visitors to download a different version of the set, perhaps a version that includes more columns than you wish to display on the HTML page.
Included on the index.html page is the code for a <button> that can launch the download of a different set from OCHRE.
Configure the second set in OCHRE.
Copy the set UUID (not the full URL of the persistent ID, just the UUID).
Paste the UUID into the id attribute of the button, i.e. <button id="1234...">.
Format and style the button however you wish, but do not change the <button id> attribute or the <button onclick> event.
The button launches the ochreCSV.html page included in the template. You may style and customize the text or other HTML elements of the ochreCSV.html page, but do not change the <button onclick> event or the scripts.
Styling of buttons is easy using Bootstrap: https://getbootstrap.com/docs/4.0/components/buttons/
Copy and paste the button code to configure as many buttons as you wish, launching downloads of different sets.

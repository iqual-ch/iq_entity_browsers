# iq_entity_browsers
## Installation
- Install the module using composer
- Follow instructions of drupal/dropzonejs to add DropzoneJS
  library (https://www.drupal.org/project/dropzonejs)
- Add exif.js library under "public/libraries/exif-js" to enable client
  side resizing (https://github.com/exif-js/exif-js)
- If any pagedesigner media type is not installed, you might want to delete
  the corresponding displays from the view (iq_media_browser)
- Add the entity browsers to the media reference fields you want. Make sure
  to match entity browser and media type.
- Grant Entity Browser permissions to roles
- Grant dropzonejs permission to roles

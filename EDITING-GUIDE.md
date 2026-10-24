# Editing guide

Open website/index.html in a text or code editor. All source is in this one file.

## Translations
The script contains `const copy` with three language dictionaries: `en` (English), `ms` (Malay), `zh` (Simplified Chinese). Edit the corresponding key in all three dictionaries to keep content aligned. Elements use data-i attributes to select translated text. Keep any intended HTML such as <br> and <span> intact.

## Contact and map
The WhatsApp destination is 60163512788 (digits only). Search for this number to update every occurrence. The telephone link uses tel:+60163512788. Update visible contact text too.

The `address` constant supplies the map query and directions. Also update the displayed address in the contact section if it changes.

## Courses, fees and offers
The cards are enquiry categories, not a confirmed course catalogue. Replace the course titles/descriptions in each language and the form options once the centre provides exact details. Update data-topic values and message preparation if categories change.

No prices or discount percentages were supplied. The current site asks visitors to enquire. Add only centre-approved prices, validity dates and terms, translated into all three languages.

## WeChat
No WeChat account or QR code was supplied. Current text asks visitors to request it through WhatsApp. Add a verified QR image or account ID when available; do not assume the telephone number is a WeChat ID.

## Visuals and accessibility
CSS custom properties at the start define navy, lime and cream colors. CSS also includes mobile layouts, hover effects and reduced-motion preferences. Keep form labels, focus outlines and required validation when editing.

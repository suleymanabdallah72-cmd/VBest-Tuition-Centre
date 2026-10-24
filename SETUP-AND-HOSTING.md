# Setup and hosting

1. Extract the ZIP.
2. Open website/index.html in a modern browser for a quick preview.
3. For a local web server, open a terminal in the website folder and run `python3 -m http.server 8000`, then visit http://localhost:8000.
4. To host independently, upload website/index.html as index.html to a static web host. There is no build command.

The existing ChatGPT Sites deployment is private. Extracting this package or uploading it elsewhere does not carry over its access control. Configure privacy or public access in your chosen host separately.

## External services
- Google Fonts loads DM Sans and Manrope; fallback fonts are included.
- Google Maps provides the embedded map and directions.
- WhatsApp links open https://wa.me/60163512788 with a prepared enquiry.
- Internet access is required for these external services.

## Enrollment behavior
The form requires guardian name, contact number, student name, student year/programme and consent. It opens WhatsApp with a prepared message for the visitor to review and send. It does not send messages automatically, save applications in a database or confirm enrollment. The centre confirms availability and registration.

The language preference is stored in the visitor's browser localStorage. Form submissions are not stored by this website. Visitors share the information with WhatsApp when they continue there.

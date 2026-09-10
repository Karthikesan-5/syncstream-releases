# SyncStream 2.0 - Releases

## v2.1.2 - 2026-09-08

- White flash after opening media fixed: film targets start black and the picture only swaps on the first decoded frame
- Object recognition: the dial sits on the disc's true centre (circumcentre of the feet, not the triangle's centroid)
- Object recognition: tapping the second film on the strip opens the second, not the first
- RFID: reader status and last tag shown in Admin > Diagnostics; errors and waiting state logged
- Dashboard pages: dark pane and LOADING notice while a site loads; the browser engine gets 30 s to start
- New swirling-fluid backdrop under an 85% black overlay
- Fluid wall reacts to touch only: no opening burst, no timed stirring
- RFID: if the configured reader never attaches, the app listens for any reader after 20 s; shared readers found through the Phidget Network Server
- Object recognition: the layer appears within a tenth of a second of placing the disc and goes home a quarter second after lifting it
- Object recognition: the disc follows only its own three feet; touching the content never moves the dial
- RFID: works with whichever reader is plugged in (no serial to configure); Diagnostics says plainly when another program such as the Phidget Control Panel is holding the reader
- Admin > BRAND: change the logo, place the corner mark (four corners, three sizes, three clear spaces) on a clear-space preview, switch the mark on or off, and change the background to an MP4 film or a JPG/PNG image
- The XP ZENTRUM mark sits in the top-right corner of every page; one logo change reaches every page, the landing wordmark included
- Brand files come from the Brand folder next to the app, the data folder's Brand folder, or the CMS media library; the choice is kept across updates
- The corner mark sits on the header line, right-aligned, resampled sharp to its exact pixel size, and stays off the landing page
- Admin frame enlarged to 1000 x 720 so every pane fits; the reader status is shorter
- Object recognition: the media strip is a slider - the current item large and centred over the family marks, the next one peeking at the edge; swipe or tap the edge to bring it in, tap the item to open it; a lone item stands centred; the pop-up lands at the centre of the glass
- RFID fixed at the root: the app itself was holding the reader (Unity's input layer opened it as a USB device); a card on the reader now triggers its content. Also: the reader is re-opened until it attaches, and Admin > Diagnostics has FREE THE READER, which stops the Phidget Control Panel that Windows starts at every login and removes its autostart with one prompt
- Liquid-glass material on the pin pad keys, the BRAND chips and buttons, the picker tiles and the logo preview: frosted body, pooled highlight, refraction band along each shape
- TAP TO BEGIN and the HOME breadcrumb line removed

## v2.1.1 - 2026-09-08

- WEBGL FLUID wall page in the dashboard: the 1x1 layout offers only the fluid, split layouts offer the websites
- Fluid page shipped inside the app: full screen, no control panel, settings fixed
- Pages can be addressed as app://<name> from the CMS webpages list
- RFID: a tag on the table's Phidget reader opens its assigned content full screen; lifting it returns home (rfid.json)
- Full-screen pages render at the screen's own resolution (4K on the 4K table); the tag's page covers the glass edge to edge
- One master controller at the side of the glass: the film transport and the page turner follow the item in hand; nothing on the pop-ups; shown only for a film or a document, on the main page and in object recognition
- Admin PIN pad and settings page in the HUD frame; chamfered glass keys and buttons; the rounded plates are gone
- Admin pages set in Inter; captions and rows aligned
- Sync page: the cloud plays forward and back; the loader is a live timer with the elapsed time and file count

## v2.1.0 - 2026-09-08

- Software Update tab in Admin: check, download and install new builds
- Video controls on every film card, including the object-recognition layer
- Transport dock rebuilt: live clock, play/pause, mute, loop, seek all working
- Vector icon set (Material Symbols) replaces pixelated glyphs
- Media strip scrolls freely with end walls; dial ring on the left column
- Admin PIN pad and settings page on glass plates; footer overlap fixed
- Video posters bake reliably; free-scroll strip no longer resets on CMS refresh


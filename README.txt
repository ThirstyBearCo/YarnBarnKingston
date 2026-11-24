THE YARN BARN
=============

Preview and edit
----------------
1. Extract the ZIP and open index.html in a browser.
2. Edit index.html for the homepage, bookings.html for classes and booking,
   and shop.html for the coming-soon online shop. Edit about.html for Libby’s
   story and visit.html for trading hours and directions. Use a code editor.
3. Put new pictures in assets/ and use relative paths. For example, add this
   inside a workshop card before its heading:
   <img src="assets/crochet-class.jpg" alt="Hands crocheting with green yarn" loading="lazy">
4. Change the colours in the :root section at the top of styles.css.
   The site uses system fonts and needs no build step.

Connect Square
--------------
1. In Square Appointments, set up and publish your class schedule and confirm
   participant limits, times and prices in Square.
2. In Square Dashboard, open Appointments > Online Booking > Channels.
   Under Add your booking flow to an existing site, choose Get URL or
   Get embed code, depending on what your booking channel offers.
3. Open bookings.html and search for SQUARE BOOKING SETUP. Remove the
   “Online bookings are coming soon” paragraph. For a link, uncomment the
   example anchor and replace PASTE_YOUR_SQUARE_BOOKING_URL_HERE with your URL.
   For an embed or Square-generated button, paste Square's code inside the
   booking-widget div. Square's booking flow can open in a separate window
   or tab.
4. Upload the extracted site files and assets folder to your web host together.
   Test the published booking page on a phone and desktop and confirm your
   workshop appears in Square before sharing the live link.

Square Australia booking setup
https://squareup.com/help/au/en/article/5355-set-up-online-booking-with-square-appointments

Before publishing
-----------------
Review the sample workshop descriptions and shop categories against your
actual plans. Keep the trading hours on visit.html aligned with the shop sign.
Monday is unlisted on the supplied sign and is omitted from the website.

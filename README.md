# The Plantains Place website

## What's in the folder
```
index.html      the public website
admin.html      the admin panel (open this to manage the site)
site-data.js    all the content (text, banners, photo data, contacts)
icons.js        icon set (WhatsApp, phone, location, social logos, etc.)
images/logo.jpg the logo
```

## Using the admin panel
1. Open `admin.html`. Default PIN: **plantains** (change it under Settings).
2. Use the menu on the left:
   - **Slide Banners**: home page banners plus the slideshow in the Rooms, Pool, Events and Food sections. Add, remove, reorder slides, change headlines and photos.
   - **Rooms & Blocks**, **Pool, Play & Events**, **Food**, **Activities**, **About Us**: edit text and photos.
   - **Gallery**: pick a category and upload many photos at once.
   - **Contact & Social**: phone, WhatsApp, email, address, hours, map and social links.
   - **Settings**: logo, name, colours, admin PIN.
3. Photos are resized and compressed automatically when uploaded. You can also drag a photo onto any photo box.
   - **Pop-ups:** each room, pool/play tile and food item has a "Pop-up details" area with a price note, longer description, highlights and extra photos. Visitors see these when they click the item.
   - **Activities:** each activity has a panel that opens below its button, with a description and a list of related activities (with optional photos).
   - **Slide Banners page:** a slider sets the height of the section banners (Rooms, Pool, Events, Food).
4. Click **Preview Site** to see your changes before they go live.
5. Click **Publish**. This downloads a new `site-data.js`. Upload it to the hosting, replacing the old one. The live site updates straight away.

## Important to know
- Your edits are saved as a draft **in the browser you use** until you publish. Use the same browser and computer until you've published, or the draft won't be there.
- The admin PIN is a simple lock, not strong security. Anyone can open `admin.html`, but they cannot change the live site because only the person who uploads `site-data.js` to the hosting can.
- This setup has no server. For changes that appear live instantly for everyone (without downloading and uploading a file), the site needs a small backend. That can be added later.

## Photos
Use only photos the owner took or approved. Photos posted by guests on TripAdvisor, Booking.com or Facebook belong to those guests.

## Booking
The booking and contact forms open WhatsApp with the details filled in, addressed to the number in Contact & Social. No payments are taken. The Booking.com link is optional.

## Social media
- Add the Facebook page link and the live Facebook timeline appears on the site.
- Instagram, TikTok and X posts: open a post, choose **Embed**, copy the code and paste it into "Embed code" under Contact & Social.

## Publishing the site
Upload the whole folder to any host (cPanel, Netlify, GitHub Pages) and point the domain to it. Open `index.html` directly to preview locally.

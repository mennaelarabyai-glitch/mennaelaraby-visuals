MENNA ELARABY PORTFOLIO WEBSITE (version 2)
==========================================

What's in this folder
- index.html   The whole website: layout, colours, text and your project list.
- media/       Your films (720p), short preview loops, poster frames, the hero
               background video, the link-preview picture and the icons.

Update the live site (Vercel)
- Open your project on vercel.com and deploy this whole folder again
  (index.html and the media folder side by side). The address stays
  https://mennaelaraby-visuals.vercel.app

What's on the page, in order
1. Opening screen: your name, the title, a short description, "Watch the
   showreel" and "Book a consultation". Behind it plays a moving wall of your
   films on computers (media/hero_wall.mp4) and the showreel on phones.
2. Numbers: years of experience, 164K and 18.8K (each with a "Watch on
   Facebook" link), 3-in-1.
3. Services with icons, then the 3 working stages and a "Book a consultation" button.
4. Work: every film has its own section with a large video. A visitor taps
   "Watch with sound" and the full film plays right there. The B A+ campaign
   has an introduction, then its 3 films one after another.
5. Client reviews.
6. About and the tools you use.
7. Contact.

Light and dark mode
- The moon/sun button switches. The site opens in the visitor's phone or
  computer setting and remembers their choice.
- Colours are at the top of the <style> part of index.html: the first block
  is light mode, the block under :root[data-theme="dark"] is dark mode.

Edit your work (open index.html in any text editor, search for
"EDIT YOUR PORTFOLIO HERE")
- Change the order: move a project block up or down in PROJECTS.
- Add a new film: copy one project block, give it a new id, and point
  video / poster / preview to new files in media/. goal, views,
  facebook (link to the post) and clientLogo (media/client_*.jpg) are optional.
- Add a size: [width, height] for each new video so its frame keeps the
  right shape while loading.

Client reviews
- In REVIEWS, paste the client's real words between the quotes after
  quote: "" (and the Arabic after the second quote: "" inside ar).
- A review with an empty quote shows as "Review coming soon".
- Add photo: "media/file.jpg" to show a picture instead of initials.
- To add another client, copy a block.

Booking button
- "Book a consultation" opens WhatsApp with a ready message. Change the
  number in WHATSAPP and the messages in WA_TEXT.

Arabic version
- Visitors switch with the عربي / EN button; the site remembers their choice
  and opens in Arabic for phones set to Arabic.
- Add #ar to the end of the address to share a link that opens in Arabic.

Video playback
- If a phone or app refuses silent autoplay (for example iPhone Low Power
  Mode), the videos start on the visitor's first tap anywhere on the page.
- To see what a phone allows, open the site with #playback-check at the end
  of the address.

Link previews (WhatsApp, LinkedIn, Facebook)
- media/og-image.jpg is the picture that appears when the link is shared.
  WhatsApp and Facebook can keep the old picture for a few days.

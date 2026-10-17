GROWUPLYT WEBSITE - KAISE UPDATE KARNA HAI

Folders:
  index.html        -> website (design yahi hai, ise mat chhedo)
  manifest.js       -> sirf yahi file edit karni hai (videos/designs ki list)
  videos/shorts/    -> Shorts / Reels (.mp4)
  videos/long/      -> Long videos (.mp4)
  designs/          -> posters / thumbnails (.webp ya .jpg)

Naya Short jodna:
  1) video ko videos/shorts/ mein daalo (jaise short-10.mp4)
  2) manifest.js mein shorts list mein "short-10.mp4", likh do

Long video jodna:
  1) videos/long/ mein daalo (jaise long-01.mp4)
  2) manifest.js mein long list mein "long-01.mp4", likh do (// hata do)

Design jodna:
  1) designs/ mein image daalo
  2) manifest.js mein { f: "design-26.webp", w: 1000, h: 1000 }, likh do
     (w = width, h = height pixels mein)

Hatana: manifest.js se line delete karo (file bhi delete kar sakte ho).

Video tips: MP4 (H.264), width 720 ya 1080, 10-30 MB tak. Bhaari ho to HandBrake / CapCut export.
WhatsApp number index.html ke upar SITE box mein hai. Instagram/YouTube/Facebook/email
link wahin daalo; khali ho to icon nahi dikhta.

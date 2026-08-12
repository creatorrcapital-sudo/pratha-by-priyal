PRATHA BY PRIYAL — Landing Page
================================
Theme: quiet-luxury / editorial minimal — inspired by torani.in
(warm off-white background · soft charcoal text · delicate light sans with
wide letter-spacing · airy whitespace · minimal outline buttons · charcoal footer)

HOW TO OPEN
-----------
Double-click index.html to view in any browser. To publish, upload the whole
folder (index.html + assets/) to any host (Netlify drag-and-drop, GitHub Pages, etc.).


ALREADY DONE
------------
✓ WhatsApp number wired in: +91 99581 06853
  (every "Order" / "Contact Designer" button opens a pre-filled chat)
✓ Party Wear & Everyday sections hidden for now (kept in the file, easy to switch back on)
✓ Logo (assets/logo.png, transparent gold) wired into header + charcoal footer
✓ Custom section shows your beadwork image (assets/custom.jpg)
✓ All 5 Rakhi photos wired (assets/products/rakhi1..5.png)


IMAGES — ALL ADDED
------------------
assets/logo.png            <- your logo (header + footer)
assets/custom.jpg          <- beadwork photo (Custom Pieces section)
assets/products/  <- 3 photos per piece (main + 2 thumbnails). Naming:
    Surkhi   ->  rakhi1-1.png  rakhi1-2.png  rakhi1-3.png
    Basanti  ->  rakhi2-1.png  rakhi2-2.png  rakhi2-3.png
    Kesar    ->  rakhi3-1.png  rakhi3-2.png  rakhi3-3.png
    Chameli  ->  rakhi4-1.png  rakhi4-2.png  rakhi4-3.png
    Nazuk    ->  rakhi5-1.png  rakhi5-2.png  rakhi5-3.png
  The "-1" photo is the main image; "-2" and "-3" become clickable thumbnails
  on the card. Currently only the "-1" photos exist — add "-2" and "-3" and the
  thumbnails appear automatically. Missing photos are hidden gracefully.
(Optional) assets/hero.jpg <- a campaign photo to fill the hero panel beside the headline
If any image is missing, the site falls back gracefully — nothing breaks.


RAKHI PIECES — ALREADY ADDED
----------------------------
Piece      Sale price   Original (shown struck-through)   Discount
Surkhi     ₹6,950       ₹8,690                            20% off
Basanti    ₹16,450      ₹20,560                           20% off
Kesar      ₹14,500      ₹18,130                           20% off
Chameli    ₹6,350       ₹7,940                            20% off
Nazuk      ₹8,990       ₹11,240                           20% off

Note on the originals: a true "20% off" means original = sale ÷ 0.8 (i.e. sale × 1.25),
NOT sale × 1.2. Using ×1.2 would make the page show "17% off" and clash with the
"20% Off" badge. So I used ÷0.8 above, which keeps every discount at an exact 20%.
(If you'd rather use your literal ×1.2 figures, say so — the badge will then read 17%.)

PHOTOS for the 5 pieces: drop them into  assets/products/  with these exact names:
    surkhi.jpg · basanti.jpg · kesar.jpg · chameli.jpg · nazuk.jpg
Portrait photos (3:4 ratio) look best. Until added, an elegant placeholder card shows.
To change a name/price later, edit PRODUCTS -> rakhi in the EDIT ZONE of index.html.


TO BRING BACK PARTY WEAR / EVERYDAY LATER
-----------------------------------------
In index.html, remove the "<!--" / "-->" comment markers around the PARTY WEAR and
CASUAL sections, and un-comment their two nav links near the top. Their product lists
are already in the EDIT ZONE, ready to edit.

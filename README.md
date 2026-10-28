# Shubh Vivah - digital wedding invitation

Ek hi file ka card: `index.html` (photos `img/` folder mein).

## Details badalna
`index.html` kholo aur "CARD DETAILS" wale hisse mein naam, date, events, venue, phone sab badlo.
Har text ke do roop hain: `en` (English) aur `hi` (Hindi). Dono badlo.
Apni photo lagani ho to `img/` folder mein daalo aur `images` mein uska naam likho,
jaise `"groom": "img/groom.jpg"`.

## Link se language
- Hindi card:   `https://USERNAME.github.io/REPO/#hi`
- English card: `https://USERNAME.github.io/REPO/#en`

## GitHub Pages par daalna
1. GitHub par naya public repo banao (jaise `shubh-vivah-card`).
2. Is folder mein terminal kholo:
   ```
   git init
   git add .
   git commit -m "Wedding card"
   git branch -M main
   git remote add origin https://github.com/USERNAME/REPO.git
   git push -u origin main
   ```
3. Repo mein Settings -> Pages -> Source: "Deploy from a branch" -> main / (root) -> Save.
4. 1-2 minute baad link ban jata hai.

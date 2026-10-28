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

## Admin page (code chhue bina details badalna)
1. Site ka link kholo aur aakhir mein `admin.html` likho:
   `https://helptogethergroup.github.io/shubh-vivah-card/admin.html`
2. Pehli baar "GitHub token" bharna hoga (page par steps likhe hain). Token sirf is shubh-vivah-card repo ko badal sakta hai.
3. Form mein English badlo, Hindi apne aap bhar jata hai (free translator se, ek baar padh lena).
4. "Save to website" dabao. 1-2 minute mein card update ho jata hai. Link wahi rehta hai.

Details `data.json` mein save hoti hain (`index.html` ke andar wali details sirf shuruaati hain).

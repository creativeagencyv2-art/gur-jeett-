1000 AI Reels Bundle website (static, no build step)

Edit assets/js/config.js to change: UPI ID, price, Drive link, email, phone,
and ENDPOINT (paste your Formspree URL to receive WhatsApp numbers + UTRs by email).

DEPLOY
- Netlify: app.netlify.com/drop -> drag this whole folder (index.html must be directly inside it).
- Vercel : open this folder in terminal -> run:  npx vercel --prod
           (Framework: Other, no build command, no output directory)

DAILY REPORTS - SETUP
1) To share boxes between friends: create a free Firebase project, add a Realtime Database
   (test mode), copy its URL (https://xxxx-default-rtdb.firebaseio.com) and paste it in index.html: const DB='...';
   Rules: {"rules":{".read":true,".write":true}}
2) Upload the whole folder to Netlify Drop / GitHub Pages / Cloudflare Pages (needs https).
3) Open the link on the phone: iPhone -> Share -> Add to Home Screen. Android -> Install app.
Without step 1 the site works on one device only.

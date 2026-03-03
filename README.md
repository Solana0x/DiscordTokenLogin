DISCORD TOKEN LOGIN
===================

⚠️ WARNING: Educational use only.

SCRIPT:
-------
let token = "YOUR_TOKEN_HERE";
function login(token) {
    setInterval(() => {
        document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
    }, 50);
    setTimeout(() => {
        location.reload();
    }, 2500);
}
login(token);

QUICK VERSION:
--------------
localStorage.setItem("token", '"YOUR_TOKEN_HERE"'); location.reload();

HOW TO GET TOKEN:
-----------------
1. Open Discord web (discord.com/app)
2. Press F12 → Network tab
3. Refresh page (F5)
4. Click any api/v9/ request
5. Copy "authorization" header value

HOW TO USE:
-----------
1. Go to Discord login page
2. Press F12 → Console tab
3. Paste script with your token
4. Press Enter
5. Wait for auto-reload (2.5s)

TROUBLESHOOTING:
----------------
- Can't paste? Type "allow pasting" first
- Not working? Clear cache/cookies
- Invalid token? Get new one

SECURITY:
---------
- NEVER share your token
- Clear console history after use
- Use at your own risk

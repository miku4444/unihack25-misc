# 🎴 EchoDeck: Making Card Games Accessible to All  

## 🌟 Inspiration  

In a world filled with social experiences, **card games** stand out as **timeless bridges** connecting people across generations and backgrounds. Yet, for the **visually impaired community**, these simple joys often remain **inaccessible barriers** rather than gateways to connection.  

> 🃏 **Card games aren’t just about the cards**—they’re about **laughter, strategy, and meaningful connections**.  

Our team was struck by this fundamental inequity. While digital entertainment has seen **tremendous advances in accessibility**, **physical card games**—with their **tactile nature and social dynamics**—have largely remained unchanged for those who cannot see the cards.  

### 🔥 Our Mission  
We envisioned a world where **everyone can play**, where **visual impairment doesn’t determine who gets included in game night**. Board and card games are one of the most **authentic ways people socialize face-to-face**, and we believe those moments should be available to **everyone, regardless of ability**.  

📢 This project isn’t just about making cards readable for the blind—it’s about ensuring that **no one feels left out when friends gather around a table**.  



## 📸 What It Does  

**EchoDeck** is a **web app** designed for accessibility, working on any device with a camera, though optimized for **mobile use**.  

🃏 **How it works:**  
1️⃣ **Point your camera** at your hand or deck of cards while playing.  
2️⃣ The app provides an **AI-generated identification** of the cards you’re holding.  
3️⃣ **Designed for screen readers**: Based on our market research, visually impaired users prefer using their **own screen readers** to interpret text rather than having the app read it aloud.  

🎯 **Game-Specific Detection:**  
- The **main page** includes a **list of over 100 games** with **pre-tailored attributes** to improve detection accuracy.  
- If your game isn’t listed, there’s also a **general detection mode** that can still recognize and describe the cards.  
  


## 🛠️ How We Built It  

🚀 **Tech Stack:**  
- **Next.js** for the frontend  
- **Convex** for the backend data storage  
- **GPT-4o API** for fast and accurate AI-generated descriptions  
- **Tailwind CSS** for a clean and responsive UI  

💾 Each **pre-filtered prompt** is stored in the database, allowing users to select them **without extra processing time**.  
 


## ⚡ Challenges We Ran Into  

### 1️⃣ Learning Frontend on the Fly 💻  
- **3 out of 5 team members** had little to no frontend experience.  
- We learned **on the spot**, reading docs, troubleshooting, and **supporting each other**.  

### 2️⃣ API Limitations & Optimization 🔄  
- API limits when processing images required us to **optimize requests**.  
- Solution: Using the **Convex backend** to convert images into URLs, reducing **file transfer size**.  

### 3️⃣ Managing Merge Conflicts & GitHub Workflow 🔄  
- Handling **GitHub merge conflicts** and learning **best collaboration practices**.  
- By the end, **everyone** became comfortable with **version control**.  

### 4️⃣ Deployment Hurdles 🚀  
- The app **worked in dev mode** but had issues when deployed.  
- API size limits when handling images required us to refine **backend processing** for efficiency.  


## 🏆 Accomplishments We’re Proud Of  

✅ Everyone on the team **learned GitHub effectively**.  
✅ We built a **fully functional, deployed product**—not just a local dev project.  
✅ We created a solution that **genuinely improves accessibility** for visually impaired players.  

🎉 *This isn't just a side project—it’s a tool that makes a real difference!*  


## 📚 What We Learned  

📌 The importance of **designing for accessibility** beyond standard UI/UX.  
📌 How to **adapt and learn new technologies** under pressure.  
📌 **Optimizing API calls** and **backend processes** for better performance.  
📌 **Collaboration, problem-solving, and the power of persistence**.  


## 🔮 What's Next for EchoDeck  

🚀 EchoDeck is just the beginning! Next, we plan to:  
✅ **Expand support for more card games** with **clearer & more concise AI-generated responses**.  
✅ Develop our **own machine learning models** for **better card recognition & lower latency**.  
✅ Introduce **Braille display compatibility** for broader accessibility.  
✅ Build a **native mobile app** for an even smoother experience.  

🎯 **Our ultimate goal: Make every card game fully accessible because everyone deserves to play!**  

![Clash Royale Happy Thumbs up](https://i.imgur.com/4FooLyV.png)

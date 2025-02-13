Here’s the **README.md** formatted version:  

```markdown
# 🚀 KiteAI Tool (Go Kite AI)  

**KiteAI** is a Node.js-based tool that supports both **Proxy and No Proxy** modes.  

🌐 **Website:** [KiteAI](https://testnet.gokite.ai?r=ehqJSY6f)  

✔️ **Daily Auto Questioning** (Max: 200 Points)  
✔️ **Multi-threaded Support**  

---

## 🖥 Setup Guide  

After downloading and extracting the tool, open a terminal and follow these steps:  

### 1️⃣ Install Dependencies & Configure the Bot  
- Run:  
  ```bash
  npm install
  ```
  This will install the required modules.  
- Configure the bot settings in **`config.js`**.  

### 2️⃣ Wallet & Proxy Setup  
- **Save your wallet addresses** in `wallets.txt`.  
- **Save proxy details** in `proxies.txt` using the following format:  
  ```
  http://username:password@ip:port
  ```

### 3️⃣ Setting Up Questions  
- Configure your questions in **`questions.js`**.  
- ⚠️ **Warning:** Avoid using the same questions as others. The system may detect duplicate questions and reduce your points.  
- **Generating Unique Questions:**  
  - Use AI tools like [poe.com](https://poe.com/) and [groq.com](https://groq.com/) to generate unique questions.  
  - When generating questions, focus on **one of these three topics** supported by KiteAI:  
    - **Kite AI Assistant**  
    - **Crypto Price Assistant**  
    - **Transaction Analyzer**  

#### 💡 AI Prompt for Question Generation  
Use this prompt on AI tools to generate questions:  
```plaintext
If you are a (insert topic here), generate (number of questions) engaging questions about blockchain, cryptocurrency, or Web3 technology. Make them thought-provoking and suitable for an AI assistant to answer.
```
- Once the questions are generated, update `questions.js` accordingly.  

### 4️⃣ Run the Tool  
Run the tool using one of these commands:  
```bash
node main
# or
node main-thread
```

---

## ⚠️ Autoref Feature (Referral System)  
- The **autoref feature** will generate referrals, but **you won’t earn points** unless the referred user completes:  
  - **3 agent actions**  
  - **Follows Kite AI on X (Twitter)**  
  - **Retweets on X (Twitter)**  

- **To try autoref**, run:  
  ```bash
  node autoref
  ```
- Referral wallets are stored in `wallets_ref.txt` in this format:  
  ```
  address|privatekey|mnemonic
  ```
- Private keys are saved in `privateKeys_ref.txt`.  

⚠️ **Note:** Your wallets **must be linked to a pre-registered account** for the tool to work.  

---

## 💬 Join Our Community  
📢 **Telegram Channel:** [forestarmy](https://t.me/forestarmy)  
▶️ **YouTube:** [Forestarmy](https://www.youtube.com/@Forestarmy)  

#kiteai 

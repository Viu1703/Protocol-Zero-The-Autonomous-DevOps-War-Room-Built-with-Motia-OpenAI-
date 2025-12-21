It is completely okay if Jarvis isn't speaking live on your laptop. For the video, **overlaying the audio in your video editor is the professional move.** It ensures the sound is crisp, clear, and perfectly timed, which judges actually prefer over a recording of a laptop speaker.

Since you asked for the README, here is a **Hackathon-Winning README Template** tailored for "Protocol Zero."

### **How to use this:**

1. Create a file named `README.md` in your project folder.
2. Paste the text below.
3. (Optional) Add screenshots of your Matrix Dashboard or Discord alert where indicated.

---

# 🛡️ Protocol Zero: The Autonomous DevOps War Room

> **"The server that heals itself."**

Protocol Zero is an autonomous, multi-agent AI system designed to detect, diagnose, and resolve critical infrastructure incidents without human intervention. Built on the **Motia** framework, it turns the chaotic "War Room" process into a structured, 10-second automated workflow.

---

## 🎥 Demo

**[▶️ Watch the 4-Minute Demo on YouTube]


---

## 🧠 The Problem

When a server crashes at 3 AM:

1. **Downtime costs money** ($9,000/minute on average).
2. **Human response is slow** (waking up, logging in, debugging).
3. **Panic leads to errors** (deleting the wrong database).

## 💡 The Solution

**Protocol Zero** replaces the panic with a cold, calculated AI response.

* **Detects** ransomware or outages instantly.
* **Debates** the fix (DevOps Engineer vs. Security Officer).
* **Executes** the solution via terminal commands.
* **Communicates** via Voice (Jarvis), Discord, and Twitter.

---

## ⚙️ Architecture & Tech Stack

This project uses an **Event-Driven Multi-Agent Architecture**.

* **Orchestration:** [Motia](https://motia.dev) (for agent flow and state management).
* **Intelligence:** **OpenAI GPT-4o-mini** (via Vercel AI SDK).
* **Runtime:** Node.js & TypeScript.
* **Integrations:**
* 🔊 **Jarvis Module:** Text-to-Speech voice interface.
* 💬 **Discord:** Real-time team notifications via Webhooks.
* 📊 **Matrix Logger:** Custom CLI dashboard for observability.



### **The Agent Swarm**

| Agent | Role | Personality |
| --- | --- | --- |
| **🕵️ AgentSecurity** | Risk Assessment | Paranoid, cautious. Warns about data loss. |
| **👷 AgentEngineer** | Quick Fixes | Reckless, speed-focused. Wants to restart everything. |
| **🧠 AgentManager** | CTO / Decision Maker | Decisive. Weighs inputs and authorizes the final command. |
| **📣 AgentPR** | Public Relations | Smooth, professional. Drafts tweets for customers. |
| **🤖 AgentJarvis** | Voice Interface | Robotic, calm. Speaks the status aloud. |
| **📡 AgentDiscord** | Comms Officer | Relays the final report to the human team. |

---

## 🚀 How It Works (The Flow)

1. **Trigger:** An external script (`attack.bat`) simulates a ransomware attack.
2. **Analysis:** `AlertAPI` picks up the signal and wakes the War Room.
3. **Debate:**
* *Engineer:* "Restart the pods!"
* *Security:* "Wait! We need to isolate the node first or we lose data."


4. **Decision:** `AgentManager` reviews both inputs and issues a `kubectl drain` command.
5. **Action:** The system executes the fix and logs it to the immutable State.
6. **Broadcast:**
* *Jarvis* announces: "Protocol Authorized."
* *Discord* receives a rich embed notification.



---

## 🛠️ Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/protocol-zero.git
cd protocol-zero

```


2. **Install Dependencies**
```bash
npm install

```


3. **Configure Environment**
Create a `.env` file and add your keys:
```env
OPENAI_API_KEY=sk-proj-xxxx...

```


4. **Run the System**
```bash
npm run dev

```


5. **Simulate an Attack**
Open a new terminal and run:
```bash
./attack.bat

```



---

## 📸 Screenshots

### **1. The Matrix Dashboard (Live War Room)**

![WhatsApp Image 2025-12-21 at 17 14 48_94021190](https://github.com/user-attachments/assets/116ec749-e57f-4063-ac09-8a247c4eeb8d)

### **2. Discord Notification**


![WhatsApp Image 2025-12-21 at 17 14 45_5338ed5e](https://github.com/user-attachments/assets/b76cefc4-c77f-476e-a4d5-f131c68db931)

---

## 🏆 Hackathon Tracks

* **AI Agents:** Fully autonomous multi-agent collaboration.
* **DevOps/Infrastructure:** Self-healing system automation.
* **Creative/Wildcard:** Voice-activated "Jarvis" interface.

---

## 👨‍💻 Author

Vinayak Tukaram More

* [GitHub](https://github.com/Viu1703)
* [Twitter/X](https://x.com/viu1703)

> *Built with ❤️ and ☕ for the Backend Reloaded Hackathon 2025.*

# 🚀 Free Unlimited AI Coding Setup Guide

This repository provides a step-by-step guide to setting up a professional AI coding environment for free. Save **$20/month** on expensive subscriptions by using **DeepSeek** models via **Agent Router** directly inside your favorite editor.

---

## 🎁 SPECIAL LIMITED OFFER: Get $150 Free Credits!
> [!IMPORTANT]
> **To receive the $150 Signup Bonus + $25 Daily Login Bonus, you MUST use the registration link below with your GitHub account. This is a limited-time promotional offer.**
>
> 👉 **[CLAIM YOUR $150 FREE API CREDITS HERE](https://agentrouter.org/register?aff=qhDL)** 👈
>
> *(Note: Sign up using your GitHub account to ensure the bonus is instantly credited to your dashboard.)*

---

## 📝 Description
With this guide, you will learn how to set up a completely free and unlimited coding environment as an alternative to expensive AI tools like Cursor or Google AntiGravity. This setup leverages **Agent Router** and the **Roo Code** extension to give you access to DeepSeek's premium models.

---

## ⏳ Prerequisites
Before starting, ensure you have:
* **IDE:** [Google AntiGravity](https://www.google.com/search?q=google+antigravity+download) or **VS Code** installed.
* **Account:** A valid [GitHub Account](https://github.com/) for authentication (Required to trigger the $150 bonus).

---

## 🎯 Model Options
We will be using **Agent Router** to access these high-end models:
1. **DeepSeek V3.2:** Best for fast, general coding, and quick bug fixes. *(Performance equivalent to Gemini 3 Pro)*.
2. **DeepSeek R1 0528:** Best for complex logic, reasoning, and system architecture. *(Performance equivalent to Gemini 1.5 Pro)*.

---

## 🔑 1. Setup Agent Router API Key
Follow these steps to get your unlimited free API key:

1. Visit the **[Agent Router Registration Page](https://agentrouter.org/register?aff=qhDL)**.
2. Click **Sign Up with GitHub**.
3. Navigate to the **Console** from the sidebar.
4. Check your **Account Data** to verify your **$150 balance**.
5. Click on **API Token** on the left menu.
6. Click **Create Token** and give it a name (e.g., `MyCoder`).
7. **Important:** Turn **ON** the toggle for **"Unlimited Quota"**.
8. Click **Submit** and copy your **API Key**.

> [!TIP]
> **Daily Bonus:** Log in to Agent Router daily to claim your free **$25 credit**, which is more than enough for a full day of heavy coding!

---

## ⚙️ 2. Install Roo Code Extension
To integrate AI into your code editor:

1. Open **Google AntiGravity** or **VS Code**.
2. Go to the **Extensions** view (`Ctrl+Shift+X`).
3. Search for **"Roo Code"**.
4. Install the official extension (look for the one with 1.4M+ downloads).

---

## 🛠️ 3. Configure Profiles in Roo Code
Open the **Roo Code** icon in your sidebar, go to **Settings**, and click **Add New Profile** to set up the following configurations:

### Profile A: DeepSeek V3 (Fast)
* **Profile Name:** `Agent-V3`
* **API Provider:** `OpenAI Compatible`
* **Base URL:** `https://api.agentrouter.org/v1`
* **API Key:** `[Paste your copied API Key here]`
* **Model ID:** `deepseek-v3`
* **Context Window:** `90000`
* **Max Output:** `8000`

### Profile B: DeepSeek R1 (Reasoning)
* **Profile Name:** `Agent-R1`
* **API Provider:** `OpenAI Compatible`
* **Base URL:** `https://api.agentrouter.org/v1`
* **API Key:** `[Paste your copied API Key here]`
* **Model ID:** `deepseek-r1`
* **Context Window:** `90000`
* **Max Output:** `8000`

> ⚠️ **Crucial:** For the **R1 profile**, scroll down in the settings and enable the **"Enable R1 Model Parameter"** toggle.

---

## 🚀 4. Advanced Performance Settings
Apply these settings in Roo Code for a seamless, distraction-free experience:

1. **Auto-Approve:** Enable `Read and Auto-approve` and `Read-write MCP mode`.
2. **Minimal Interruptions:** Disable the `Question` option.
3. **Custom Instructions:** Add the following text under "Custom Instructions for All Modes":
```text
No browse rule. Focus on clean, modular code and follow best practices. Do not ask for permissions for every small step.
🤝 Support & Feedback
If you find this guide helpful, please:

⭐ Star this repository to show your support.
🐞 Open an Issue if you encounter any setup problems.

Disclaimer: This guide is for educational purposes. All credits for the API service go to Agent Router.

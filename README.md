# 🍴 ForkCast — AI Meal Planner

> **Stop the dinner drama. Get cooked.** ✨

ForkCast is an AI-powered meal planning web app that eliminates decision fatigue around cooking. Tell it what's in your kitchen, your dietary needs, and what cuisine you're craving — it generates personalized recipes with full macro breakdowns and a 7-day meal plan, all powered by Claude AI.

🔗 **[Live Demo](https://hnk9919.github.io/forkcast/)** &nbsp;|&nbsp; 📁 **[GitHub Repo](https://github.com/hnk9919/forkcast)**

---

## 🌟 What It Does

ForkCast takes the guesswork out of meal planning by walking users through a guided, step-by-step flow and then using AI to generate fully tailored recipes in seconds.

- **Smart pantry input** — select from 300+ items across 17 categories (meats, produce, spices, dairy, frozen items, and more)
- **Dietary & allergy aware** — supports 20+ dietary styles and strictly avoids selected allergens
- **35+ cuisine options** — from Indian and Italian to Sichuan, Mediterranean, and West African
- **Macro breakdowns** — every recipe includes calories, protein, carbs, fat, and fiber per serving
- **7-day meal plan** — a full week of breakfast, lunch, and dinner mapped to generated recipes with nutrition notes
- **Scalable servings** — adjusts for 1 to 20 people
- **Missing ingredient alerts** — tells you exactly what to grab and suggests substitutes for what you don't have
- **Meal prep tips** — each recipe includes a chef-style prep tip for batch cooking

---

## 🚀 How It Works

1. **Enter your name** — personalised experience from the start
2. **Add your API key** — paste your Anthropic key (stored locally in your browser, never sent anywhere else)
3. **Set your preferences** — dietary style, allergies, cuisine cravings, and pantry inventory
4. **Final details** — number of people, calorie goal, spice level, cooking time, and intent (meal prep, party, quick meal, etc.)
5. **Generate** — Claude AI cooks up your personalised recipes and weekly plan
6. **Explore** — tap recipe cards to view full instructions, or switch to the weekly plan tab for your full 7-day schedule

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript (single-file app) |
| AI / Backend | [Claude API](https://www.anthropic.com/) (claude-sonnet-4-5) |
| Fonts | Clash Display, DM Sans (Google Fonts) |
| Storage | Browser localStorage (preferences + API key) |
| Hosting | GitHub Pages |
| Build process | None — zero dependencies, zero frameworks |

---

## ⚙️ Getting Started

### Prerequisites
You need a free Anthropic API key to use this app. Get one at [console.anthropic.com](https://console.anthropic.com). New accounts come with free credits.

### Run Locally
```bash
# Clone the repo
git clone https://github.com/hnk9919/forkcast.git

# Open the file directly in your browser
open index.html
```
No npm install. No build step. No server required. Just open the file.

### Use the Live Version
Head to [https://hnk9919.github.io/forkcast/](https://hnk9919.github.io/forkcast/) and paste your API key when prompted. Your key is saved in your browser for future visits.

---

## 📸 App Flow

```
Welcome Screen
     ↓
Enter Your Name
     ↓
Dietary Style → Allergies → Cuisine → Pantry  (4-step guided flow)
     ↓
Final Details  (people, calories, spice, time, intent)
     ↓
AI Generation  (Claude API call)
     ↓
Recipe Cards Grid  ←→  7-Day Weekly Plan
     ↓
Tap any card → Full recipe modal (ingredients, steps, macros, prep tip)
```

---

## 🔑 API Key

ForkCast requires an Anthropic API key to generate recipes.

- Your key is stored **only in your browser's localStorage**
- It is **never sent to any server** other than Anthropic's official API
- You can update your key anytime using the 🔑 button in the bottom-right corner of the app

---

## 💡 Project Background

This project was built to solve a real problem — decision fatigue around meal planning, especially for students and working professionals juggling multiple responsibilities. The goal was to build something that feels like a smart, helpful friend in the kitchen rather than a generic recipe search engine.

Built entirely through **vibe coding** — using Claude AI as a development partner to go from idea to a fully functional, polished web app without a traditional development workflow.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with 🍳 and Claude AI</p>

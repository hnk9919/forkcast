# 🍴 ForkCast — AI Meal Planner

> **Your AI meal bestie. Zero dinner drama.**

ForkCast is an AI-powered meal planning web app that eliminates decision fatigue around cooking. Tell it what's in your kitchen, your dietary needs, and what cuisine you're craving — it generates personalized recipes with full macro breakdowns and a 7-day meal plan, powered by the Claude API.

🔗 **[Live Demo](https://yourusername.github.io/forkcast)** · **[GitHub Repo](https://github.com/yourusername/forkcast)**

---

## 📸 Preview

> *(Add a screenshot or GIF of your app here)*

---

## ✨ Features

- **Personalized Dietary Filtering** — Choose from 20+ dietary styles including Vegan, Keto, Gluten-Free, Eggetarian, Pescatarian, and more
- **Allergy Detection** — Flag 20+ common allergens; Claude strictly excludes them from every recipe
- **35+ Cuisine Options** — Indian, Italian, Japanese, Mediterranean, Sichuan, Thai, Mexican, West African, and more
- **Smart Pantry Tracker** — 17 pantry categories (Meat, Seafood, Grains, Pulses, Spices, Frozen Items, etc.) with 200+ items to check off — saved to localStorage
- **Dynamic Recipe Generation** — AI generates fully detailed recipes with ingredients, step-by-step instructions, cooking time, servings, and meal prep tips
- **Macro Breakdown** — Every recipe includes calories, protein, carbs, fat, and fiber per serving
- **Missing Ingredient Alerts** — Highlights what you need to buy and suggests substitutes for missing items
- **7-Day Meal Plan** — A structured weekly plan with breakfast, lunch, and dinner mapped to generated recipes, plus daily calorie estimates and nutrition notes
- **Interactive Recipe Cards** — Tap any card to open a full recipe modal with an animated unfold effect
- **Adjustable Sliders** — Set number of people (1–20), number of recipes (1–10), and daily calorie goal (800–4000 kcal)
- **Preferences Saved** — Pantry, dietary choices, allergies, and cuisines are all saved in localStorage for your next visit
- **Floating API Key Manager** — Update your Anthropic API key anytime from the bottom-right corner without restarting

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript (no frameworks) |
| AI / Backend | [Anthropic Claude API](https://console.anthropic.com) (`claude-sonnet-4-5`) |
| Fonts | Clash Display · DM Sans (Google Fonts) |
| Storage | Browser localStorage |
| Hosting | GitHub Pages |

> Built entirely as a **single HTML file** — no build tools, no dependencies, no server required.

---

## 🚀 Getting Started

### Option 1 — Run Locally

1. Download or clone this repository
```bash
git clone https://github.com/yourusername/forkcast.git
```
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. Enter your name → paste your Anthropic API key when prompted → start cooking 🍳

### Option 2 — Use the Live App

Visit **[yourusername.github.io/forkcast](https://yourusername.github.io/forkcast)** directly in your browser — no installation needed.

---

## 🔑 API Key Setup

ForkCast uses the **Anthropic Claude API** to generate recipes. You'll need your own API key.

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up or log in
3. Navigate to **API Keys** → click **Create Key**
4. Copy the key (it starts with `sk-ant-`)
5. Paste it into ForkCast when prompted on first launch

> Your API key is stored **only in your browser's localStorage** — it is never sent anywhere except directly to Anthropic's API.

You can update your key anytime using the 🔑 button in the bottom-right corner of the app.

---

## 📱 How to Use

```
1. Enter your name
        ↓
2. Paste your Anthropic API key
        ↓
3. Pick your dietary style
        ↓
4. Select any allergies
        ↓
5. Choose your cuisine cravings
        ↓
6. Check off what's in your pantry
        ↓
7. Set people count, recipe count, calorie goal, spice level & cooking time
        ↓
8. Hit "Get Me Cooked" 🍳
        ↓
9. Browse recipe cards → tap to see full details
   Switch to Weekly Plan tab for your 7-day schedule
```

---

## 📁 Project Structure

```
forkcast/
│
└── index.html        # Entire app — HTML + CSS + JS in one file
```

---

## 💡 Why I Built This

Decision fatigue around meals is a real problem — especially for students and working professionals juggling multiple responsibilities. Most meal planning tools are either too complex or too generic. ForkCast was built to be hyper-personal: it knows what's already in your kitchen, respects your dietary restrictions, and uses AI to generate recipes you'll actually want to cook.

---

## 🔮 Future Ideas

- [ ] Export meal plan as PDF or image
- [ ] Voice input for pantry items
- [ ] Grocery list auto-generation based on missing ingredients
- [ ] Calorie tracking across the week
- [ ] Mobile app version (React Native)
- [ ] Share recipes with friends via link

---

## 🤝 Built With

- **Claude AI** by [Anthropic](https://anthropic.com) — for recipe generation
- **Vibe Coding** methodology — iterative AI-assisted development
- **GitHub Pages** — free hosting

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with 🍴 and a lot of AI magic</p>

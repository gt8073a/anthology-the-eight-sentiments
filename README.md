# 🎮 Anthology: The Eight Sentiments

*A word game about the emotional life of language.*

---

## ✨ What is Anthology?
**Anthology: The Eight Sentiments** is a creative word game powered by an AI Sentiment Engine.  
Every word you play is scored across **eight emotional axes**:

- **JOY** – elation, optimism  
- **TRU** – trust, safety  
- **FER** – fear, anxiety  
- **SUR** – surprise, novelty  
- **SAD** – sorrow, grief  
- **DIS** – disgust, distaste  
- **AGR** – anger, frustration  
- **ANT** – anticipation, suspense  

Your goal is to build a profile of words that matches a hidden **Target Profile**.  
The game feels part-poetry, part-psychology, part-strategy.

---

## 🧩 Why It’s Different
Most word games are about rules. Anthology is about **interpretation**.  

- You can play in **any language**.  
- You can use **any word** — slang, proper nouns, even nonsense.  
- Scoring is **non-deterministic** (the same word can feel different in different contexts).  
- You can **argue** with the engine to push meaning into your own territory.  

👉 These two design features are explained in detail:  
- [🗣️ Arguing with the Sentiment Engine](argue.md)  
- [🎲 Non-Determinism as a Feature](non-determinism.md)  

---

## 📖 How a Round Works
1. The game sets a **Target Profile** tied to a theme.  
2. You submit words, one at a time.  
3. Each word is scored across the 8 sentiments, and added to your **Current Profile**.  
4. You track the **Delta Profile** (the difference between target and current).  
5. When you’re close enough, you reach the 🏆 **Good State**.  

---

## 🧵 Sample Rounds
Want to see it in action? Check out these full round transcripts:

- [Sample Round 1: The Hard Days of My Favorite Sweater](sample_round1.md)  
- [Sample Round 2: A First Date in the Rain (Arguing + Non-Determinism)](sample_round2.md)  

---

## 🚀 Run It Yourself
Clone the repo and run locally:

```bash
git clone https://github.com/gt8073a/anthology-the-eight-sentiments.git
cd anthology-the-eight-sentiments
# instructions for running your version go here when i write them for Ollama
```


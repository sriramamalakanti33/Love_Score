# 💘 Love Score Calculator

A fun Python script that calculates a **"love score"** between two names using simple logic and randomization. Based on vowels, consonants, name lengths, and matching characters, it gives you a percentage and a playful message about the strength of the relationship.

---

## 📦 Modules Used

This project uses **only built-in Python libraries**:

* `random` – To generate unpredictable score elements.
* `time` – To simulate a "calculating" delay.

No installation required!

---

## 🚀 How It Works

### 1. 📝 Input

You’ll be prompted to enter two names.

### 2. 🧠 Logic

Several factors influence the final love score:

* **Matching Vowels**: +10 to +30 points if both names have the same number of vowels.
* **Matching Consonants**: +20 to +40 points if both names have the same number of consonants.
* **Same First Letter**: +10 to +30 points if both names start with the same letter.
* **Equal Length**: +1 to +10 points for same-length names.
* **Bonus Random Score**: Always adds +10 to +50 to keep things interesting.

The final score is capped at 100%.

### 3. 🎉 Output

After a short “Calculating…” delay, the script prints:

* The calculated **love score**
* A playful message based on the score:

| Score Range | Message                                |
| ----------- | -------------------------------------- |
| 90–100%     | ❤️ Unbreakable relationship            |
| 70–89%      | 💍 Strong, likely to marry             |
| 50–69%      | ✈️ Good bond, honeymoon in Paris?      |
| Below 50%   | 💔 Weak match that *might* have worked |

---

## 👨‍💻 Usage

```bash
python love_score.py
```

Follow the prompts and enjoy the results!

---

## 📄 Example

```
Please type Name 1:
Alice
Please type Name 2:
Andrew
Calculating...
Alice and Andrew have a 78% relationship.
They have a strong relationship that will most likely lead to a marriage.
```

---

## 📁 File Structure

```
Love_Score/
│
├── Love_Score.py     # Main script
└── README.md         # Project description and documentation
```

---

## 💡 Note

This program is purely for **entertainment** and should not be taken seriously. Have fun with friends, but remember — love isn't measured in percentages!

### ❤️ Relationships are complex

Human emotions, compatibility, mutual respect, shared values, communication styles, cultural backgrounds — all these and more influence a relationship. A playful algorithm based on name letters or birthdates can't capture this depth.

---

### 🤖 These tools are for **fun**, not facts

Love score apps, astrology matchers, or personality quizzes are usually meant for entertainment. They’re engaging and can spark conversation or laughter — but they don’t reflect psychological, emotional, or real-life compatibility.

---

### 🔍 No scientific basis

Matching vowels or first letters doesn’t have any scientific correlation with emotional bonding, mutual understanding, or long-term happiness. Real relationship compatibility is studied through fields like psychology and sociology — not by matching strings or random numbers.

---

### ✅ That said...

There's nothing wrong with using these tools for **fun**. If it makes you smile, or brings joy or a memory with someone, it’s serving a purpose — just not a predictive or serious one.

---

So if you or your friends ever get a low love score — don’t worry 😄. Real relationships are built with effort, trust, and understanding — not Python scripts.

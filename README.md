# 📚 German Noun Dictionary Dataset (83K+ Words)

A high-performance German noun dictionary dataset designed for fast lookup, language learning, and NLP applications.

---

## 🚀 Overview

This dataset contains **83,000+ German nouns** with structured linguistic information:

- Grammatical gender
- Plural form
- English meaning
- Special gender cases (NG, ND)

It is optimized for:
- Browser extensions (Tampermonkey, Chrome, Kiwi)
- Offline dictionaries
- APIs and backend systems
- Language learning tools
- NLP / AI preprocessing

---

## 📦 Data Structure

Each entry in the dataset follows this format:

```json
{
  "word": {
    "gender": "M | F | N | NG | ND",
    "plural": "string or null",
    "meaning": "string or null"
  }
}

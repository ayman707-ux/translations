# Anime Realms Translations

Welcome to the official translation repository for **[Anime Realms](https://animerealms.org)**!

This repository contains the localization files used directly on the website. By contributing here, you help make Anime Realms accessible to fans all over the world.

## 📂 Repository Structure

We use standard JSON files for localization. Each file represents a language code.

- `en.json` (English - **Source of Truth**)
- `es.json` (Spanish)
- `fr.json` (French)
- ...and so on.

## 🚀 How to Contribute

We welcome contributions from everyone! You don't need to be a coder to help, but you do need a GitHub account.

### 1. Improving an Existing Language
1.  **Fork** this repository to your own account.
2.  Open the file for the language you want to edit (e.g., `es.json`).
3.  Find the text that needs improvement.
4.  Edit the **Value** (the text on the right), but **NEVER** the **Key** (the text on the left).
5.  Submit a **Pull Request (PR)**.

### 2. Adding a New Language
1.  Fork the repository.
2.  Copy `en.json` and rename it to your language code (e.g., `pt-BR.json` for Brazilian Portuguese).
3.  Translate the values inside the new file.
4.  Submit a Pull Request.

---

## ⚠️ Important Rules (Please Read)

To ensure your contribution is accepted quickly, please follow these rules:

### ✅ DO: Translate the Value
Only change the text on the **right side** of the colon.

```json
// Correct ✅
"home_page_title": "Bienvenue sur Anime Realms"
````

### ❌ DON'T: Touch the Key

The text on the left is used by the code. If you change it, the website breaks.

```json
// Incorrect ❌ (Do not translate "home_page_title")
"titre_page_accueil": "Bienvenue sur Anime Realms"
```

### ❌ DON'T: Break JSON Syntax

Be careful with quotes (`"`) and commas (`,`).

```json
// Incorrect ❌ (Missing comma at the end)
"search_placeholder": "Rechercher anime"
"login_btn": "Connexion"
```

### 📝 Interpolation Variables

If you see words inside curly braces like `{name}` or `{count}`, **do not translate them**. They are placeholders for dynamic data.

  * **English:** `"Welcome back, {username}!"`
  * **Spanish:** `"¡Bienvenido de nuevo, {username}!"` ✅

-----

## 🤝 License

By contributing to this repository, you agree that your translations can be used freely by Anime Realms on the website and related platforms.

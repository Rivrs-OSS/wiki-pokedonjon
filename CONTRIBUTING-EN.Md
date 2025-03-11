---
description: >-
  Find here all the information you need to help us modify this wiki
icon: pen-to-square
---

# Contribution

Welcome! This guide will walk you step by step through the <mark style="color:blue;">**contribution**</mark> process to the <mark style="color:blue;">**EpicWorld**</mark> project wiki on <mark style="color:blue;">**GitHub**</mark>.

## 📋 <mark style="color:blue;">Prerequisites</mark>

* Create a GitHub account: [GitHub Sign Up](https://github.com/join).
* Install Git on your computer: [Download Git](https://git-scm.com/downloads).
* Choose a simple and user-friendly editor like [Visual Studio Code](https://code.visualstudio.com/).

## ⚙️ Install and Configure Git

After installation, open your terminal and configure your name and email (the ones used for GitHub):

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

## 🚀 <mark style="color:blue;">Make a Contribution</mark>

### <mark style="color:blue;">1.</mark> <mark style="color:blue;">Fork the Repository</mark>

* Go to [wiki-epicworld](https://github.com/Rivrs-OSS/wiki-epicworld)
* Click on the <mark style="color:blue;">**Fork**</mark> button in the top right to create a copy of the repository on your account.

### <mark style="color:blue;">2. Clone Your Fork to Your Computer</mark>

Copy the link to your fork and run the following command in your terminal:

```bash
git clone https://github.com/YOUR-USERNAME/wiki-epicworld.git
cd wiki-epicworld
```

### <mark style="color:blue;">3. Create a New Branch</mark>

Create a separate branch for each topic you work on to keep your contributions organized:

```bash
git checkout -b branch-name
```

Example: `git checkout -b add-capture-guide`

### <mark style="color:blue;">4. Edit the Wiki</mark>

* Use Visual Studio Code to edit markdown (`.md`) files.
* You can also create new files, for example, `how-to-capture-pokemon.md`.

Example of a simple markdown structure:

```markdown
# Main Title

## Subtitle

Your content here...

- Bullet list item
- Second point

[A useful link](http://example.com)
```

### <mark style="color:blue;">5. Add Your Changes to Git</mark>

In your terminal, add and commit your changes:

```bash
git add .
git commit -m "Added guide on capturing Pokémon"
```

### <mark style="color:blue;">6. Push Your Contribution</mark>

Send your changes to GitHub:

```bash
git push origin branch-name
```

### <mark style="color:blue;">7. Open a Pull Request (PR)</mark>

* Go back to your forked project on GitHub.
* Click on <mark style="color:blue;">**Compare & pull request**</mark>.
* Clearly describe your contribution and then confirm by clicking <mark style="color:blue;">**Create pull request**</mark>.

## 💡 <mark style="color:blue;">Best Practices and Tips</mark>

* Keep your explanations clear and concise.
* Check spelling and grammar.
* Structure your markdown pages properly.
* Use Visual Studio Code’s markdown previews (Ctrl + Shift + V) before submitting.

## 🛠️ <mark style="color:blue;">If You Encounter Issues</mark>

Feel free to create an [issue](https://github.com/Rivrs-OSS/wiki-epicworld/issues) on GitHub to ask for help or to raise a question.

Thank you for your contribution! ✨


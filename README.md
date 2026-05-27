# 📝 Mad Lib Generator

A Python command-line program that collects words from the user by type (noun, verb, adjective, etc.) and assembles them into a humorous pre-written story template — demonstrating string formatting, user input handling, and dynamic text generation.

---

## Features

- ✅ Multiple story templates to choose from
- ✅ Prompts user for words by type (noun, verb, adjective, adverb, name, place)
- ✅ Assembles and displays the completed story with clean formatting
- ✅ Replay with a new template or the same one

---

## Demo

```
=== Mad Lib Generator ===

Choose a story:
  [1] The Adventure
  [2] A Day at the Zoo
  [3] The Missing Recipe

Your choice: 1

I need some words to build your story!

Enter a noun:       spaceship
Enter a verb:       exploded
Enter an adjective: purple
Enter a place:      library
Enter a name:       Gerald

--- Your Story ---

One sunny morning, Gerald decided to take their purple spaceship
to the library. Nobody expected what happened next — it exploded
right in the middle of the parking lot. Everyone agreed it was
the most exciting Tuesday in history.
```

---

## How to Run

**Requirements:** Python 3.x

```bash
# Clone the repository
git clone https://github.com/f-anselm88/mad-lib-generator.git

# Navigate into the project
cd mad-lib-generator

# Run the program
python madlib.py
```

---

## How It Works

1. User selects a story template from the menu
2. Program prompts for each required word type one at a time
3. Words are injected into the template using Python f-strings
4. The completed story is printed with proper formatting

---

## What I Learned

- Dynamic string construction using f-strings and `.format()`
- Organizing templates as data structures (dictionaries/lists)
- Building clean, menu-driven CLI applications

---

## Author

**Anselm Munango**
[f-anselm88.github.io](https://f-anselm88.github.io) · [GitHub](https://github.com/f-anselm88) · [LinkedIn](https://linkedin.com/in/anselm-munango-bs) · [anselm.mu@gmail.com](mailto:anselm.mu@gmail.com)


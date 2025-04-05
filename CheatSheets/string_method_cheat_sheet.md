# Python String Methods Cheat Sheet (Beginner Friendly)

| Method | Description | Example Code | Example Output |
|--------|-------------|--------------|----------------|
| `.lower()` | Converts all characters to lowercase | `name.lower()` | `"reginald hook"` |
| `.upper()` | Converts all characters to uppercase | `name.upper()` | `"REGINALD HOOK"` |
| `.title()` | Capitalizes the first letter of each word | `name.title()` | `"Reginald Hook"` |
| `.strip()` | Removes whitespace from both ends | `name.strip()` | `"Reginald"` *(if extra spaces)* |
| `.replace(old, new)` | Replaces one word or letter with another | `name.replace("Hook", "Lee")` | `"Reginald Lee"` |
| `.startswith("R")` | Returns `True` if string starts with given value | `name.startswith("R")` | `True` |
| `.endswith("k")` | Returns `True` if string ends with given value | `name.endswith("k")` | `True` |
| `.find("H")` | Returns the index of first occurrence of substring | `name.find("H")` | `9` (position of 'H') |

> 💡 *Remember to use parentheses `()` to actually call each method!*

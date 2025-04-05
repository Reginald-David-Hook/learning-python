
# Python Quotes vs. Parentheses Cheat Sheet

### ✅ Parentheses `()` – Do Something or Group Something
Used to **call functions**, **methods**, or **group math expressions**.

```python
print("Hello")       # Call a function
name.lower()         # Call a string method
(2 + 3) * 4          # Grouping math
```

---

### ✅ Quotes `' '` or `" "` – Define Strings
Used to define text data.

- Use `'` or `"` for simple strings:
```python
name = 'Reginald'
city = "Jacksonville"
```

- Use `"` when the string contains `'`:
```python
quote = "It's a great day"
```

- Use `''' '''` or `""" """` for multi-line strings or docstrings:
```python
bio = """Reginald is learning Python
through projects and GitHub."""
```

---

### ✅ Nesting Quotes Safely

```python
print("It's sunny")                   # ✅ OK
print('She said, "Hello!"')          # ✅ OK
print('It\'s sunny')                 # ✅ Escape with backslash
```

---

### 🔄 Summary Table

| Type | Example | Use For |
|------|---------|---------|
| `'` or `"` | `"Hello"` or `'Hello'` | Defining strings |
| `()` | `print()`, `lower()` | Function/method calls or math grouping |
| `''' '''` / `""" """` | Multiline or docstrings | Multiline text or docstrings |
| `\'` or `\"` | `'It\'s fine'` | Escape inner quotes |

> 💡 Tip: Stick to one quote style in a file for consistency.

# Contributing to This Project

Thanks for contributing! To keep the Git history clean and readable, please follow the commit message conventions below.

## ✅ Commit Message Guidelines

Each commit message should follow this format:
```bash
<emoji> <type>: <short summary>

<optional longer description — wrap lines at 72 chars>
```

### 🧠 About the 50/72 Rule

Commit messages follow the 50/72 rule:

* First line: ≤ 50 characters — short summary of the change

* Body text: ≤ 72 characters per line — detailed explanation (optional)

Why? This keeps git log, GitHub, and tools like git shortlog clean and readable in terminals, GUIs, and code reviews.

### 🔖 Allowed Commit Types and Emoji Tags

| Badge      | Emoji  | Use When...                                  |
|------------|--------|-------------|--------------------------------|
| `build:`   | 🛠️     | Build tools or infra changes (not updates)   |
| `chore:`   | 🔧     | Routine tasks or config cleanup              |
| `ci:`      | 🤖     | CI/CD pipeline, scripts, or workflows        |
| `deps:`    | 📦     | Add or update dependencies                   |
| `docs:`    | 📝     | Updating docs, READMEs, help text            |
| `feat:`    | ✨     | Adding a new feature or functionality        |
| `fix:`     | 🐞     | Fixing a bug                                 |
| `perf:`    | 🎯     | Performance improvements                     |
| `refactor:`| ♻️     | Code changes that don't affect behavior      |
| `release:` | 🚀     | Creating a tagged release                    |
| `style:`   | 🎨     | Code formatting or whitespace only           |
| `test:`    | 🔬     | Adding or tweaking tests                     |

### 🔖 Emojis for Project Meta Information

For consistency, you may use the following emojis in headings and messages.

| Emoji  | Use For...              |
|--------|-------------------------|
| 🏷️     | A Git tag               |
| 🌿     | A Git branch            |
| 📌     | A software version      |
| 📸     | A snapshot              |
| 📅     | A deployment window     |
| 🧠     | Summary or explanation  |
| 🔖     | Important note          |
| ✅     | Task list or scope      |
| 💡     | Example                 |

### 💡 Example

```bash
✨ feat: Add support for multilingual content

Enables i18n with content translation, language switcher, and
language negotiation based on browser preference.
```

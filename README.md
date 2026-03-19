# 📝 Day 4: HTML Advanced Forms & Input Types

Welcome to Day 4! Today's session was all about moving beyond simple text inputs. I explored the "Advanced Input Types" that HTML5 provides to make forms more interactive and user-friendly.

## 🚀 Live Demo
Want to see these inputs in action? Click the button below:

<a href="https://itsdishayk.github.io/HTML-Forms-Advance-Input-Types/">
  <img src="https://img.shields.io/badge/View%20Live%20Forms-orange?style=for-the-badge&logo=github" alt="Live Demo Button" height="40">
</a>

---

## 🛠️ Key Concepts Learned

In this project, I integrated several advanced `<input>` types:

| Input Type | Purpose |
| :--- | :--- |
| `type="color"` | Opens a native color picker for the user. |
| `type="date"` | Provides a calendar interface to select dates. |
| `type="range"` | Creates a slider to choose values within a min/max range. |
| `type="number"` | Restricts input to numeric values only. |
| `type="time"` | Allows users to pick a specific time of day. |

### 💡 Why use these?
These types are great because they provide **Native UI**—meaning on an iPhone or Android, they will automatically open the phone's built-in date picker or color wheel, making the user experience much smoother.

---

## 📖 Code Snippet Example

```html
<label for="favcolor">Pick a color:</label>
<input type="color" id="favcolor" name="favcolor">

<label for="birthday">Birthday:</label>
<input type="date" id="birthday" name="birthday">

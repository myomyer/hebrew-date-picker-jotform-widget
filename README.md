# Hebrew Date Picker for Jotform

A compact Hebrew Date Picker widget for Jotform. Converts between **Gregorian** and **Hebrew** dates, with optional **after-sunset rollover** to align correctly with the Jewish calendar day.  
Displays Hebrew dates in **gematria** (day, month, year) while also passing both **Hebrew (display)** and **English (submission)** values back into Jotform.

---

## ✨ Features
- 🔄 Convert **Gregorian ↔ Hebrew** dates
- 🌅 After-sunset rollover handling
- 📝 Submits both Hebrew and English versions of the date
- 🎨 Compact, theme-aware design (inherits Jotform styling)
- 📦 Easy to embed via Jotform’s iFrame widget or custom widget system

---

## 🛠 Development
The widget uses:
- [Hebcal API](https://www.hebcal.com/home/developer-apis) for date conversion
- Native HTML, CSS, and JavaScript
- `JFCustomWidget.sendData` to communicate with Jotform

---

## 📜 License
This project is licensed under the **MIT License** – see [LICENSE](LICENSE) for details.

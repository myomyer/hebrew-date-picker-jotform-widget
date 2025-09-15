# Hebrew Date Picker (from Civil Date)

This Jotform widget converts a Civil (Gregorian) date into its Hebrew calendar equivalent.  
It listens to a standard Jotform **Date Picker** field, applies optional "After Sunset" rollover, and outputs the Hebrew date string.

## Features
- Pulls date from a regular Jotform Date Picker field.
- Converts to Hebrew (using Hebcal API).
- Optional **After Sunset** checkbox (bumps date forward by 1 day).
- Submissions show only the Hebrew date in the widget column.
- Civil Date remains in its own Jotform field.

## Setup
1. Add a **Date Picker** to your Jotform form.
2. Add the **Hebrew Date Picker (from Civil)** widget.
3. In widget settings → General, set **Civil Date Field Unique Name** to match the Date Picker’s unique name (found in Field Properties → Advanced → Field Details).
4. Publish and test — submissions will include both:
   - Civil Date (native Jotform column)
   - Hebrew Date (widget column)

---

## 🛠 Development
The widget uses:
- [Hebcal API](https://www.hebcal.com/home/developer-apis) for date conversion
- Native HTML, CSS, and JavaScript
- `JFCustomWidget.sendData` to communicate with Jotform

---

## 📜 License
This project is licensed under the **MIT License** – see [LICENSE](LICENSE) for details.

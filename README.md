# TaskVault

**TaskVault** is a minimal personal task manager designed to collect, store, and manage links or URLs as actionable tasks.

---

## 🔥 Features

- ✅ Add any link (Twitter, YouTube, Medium, etc.) as a task.
- ✅ Paste from clipboard to add links manually.
- ✅ Semi-automated iOS Shortcut integration.
- ✅ Hosted on GitHub Pages.
- ✅ Works fully offline (PWA enabled).
- ✅ Clean, distraction-free interface.

---

## 🔗 iOS Automation Flow

You can fully automate link collection using iOS Shortcuts:

### Step 1: Create a Shortcut

- Read Clipboard
- If Clipboard contains `https://`
- Encode URL (Clipboard)
- Set Variable `EncodedTask` to Encoded URL
- Open URL: `https://santymetal.github.io/taskvault/?task=EncodedTask`

### Step 2: Create Automation

- Trigger: App Open → Apps like Safari, Twitter, YouTube
- Action: Run the above shortcut
- Disable: "Ask Before Running"

🎯 Now, whenever you copy a link and open any supported app, TaskVault auto-launches with the link added.

---

## 💡 Internals

- TaskVault accepts new tasks via query params:
  

- `main.js` parses the URL on load and automatically adds the task.

---

## 📦 Hosting

The app is completely hosted using GitHub Pages:

👉 [TaskVault Live App](https://santymetal.github.io/taskvault/)

---

## 🚀 Future Plans

- Notifications (once browser API permits PWA notifications on iOS)
- Web Share Target API integration
- Cross-device sync via local backend (optional)
- Share extension for faster task creation

---

## 🙌 Credits

Built by [Santosh](https://github.com/santymetal).

---

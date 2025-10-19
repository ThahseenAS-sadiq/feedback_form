# 📝 Feedback Form (HTML + CSS + JS)

A simple and responsive **feedback form** built using **HTML, CSS, and JavaScript**.  
Includes a **200-character limit** with a live counter and form validation using `addEventListener`.

---

## 🚀 Features

- ✅ 200-character limit with live counter  
- 🎧 Real-time updates using `addEventListener`  
- ⚡ Form validation for empty or long inputs  
- 💬 Success and error messages shown dynamically  
- 🖤 Fully responsive modern UI (dark mode look)  
- 🧱 Single-file project — easy to edit and host

---

## 🧩 Technologies Used

- HTML5  
- CSS3  
- JavaScript (Vanilla)

---

## 💡 How It Works

1. Type feedback in the textarea (max 200 characters).  
2. Character counter updates automatically as you type.  
3. On clicking **Submit**, validation checks the input.  
4. Displays a success message (simulated using `fakeSubmit()` in JS).  
5. Replace `fakeSubmit()` with a real API call using `fetch()` to connect a backend.

---

## 📁 File Info

- `feedback_form.html` → Contains all HTML, CSS, and JS in one file.  
  You can open this file directly in your browser or host it using GitHub Pages.

---

## ⚙️ How to Run Locally

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git

##Future Enhancements

1.Connect to a backend using fetch()

2.Save feedback locally (localStorage)

3.Add input animations or toast alerts

4.Improve accessibility and mobile view



cd <your-repo-name>
open feedback_form.html    # or use Live Server in VS Code

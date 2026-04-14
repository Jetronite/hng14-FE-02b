# 🧙‍♂️ Frontend Wizards — Stage 1B

## 📌 Testable Profile Card

This project is a responsive, accessible **Profile Card component** built using **semantic HTML, modern CSS, and vanilla JavaScript**. It strictly follows the provided requirements, including testability using `data-testid` attributes.

---

## 🚀 Live Demo

👉 *Add your deployed link here*
Example: [https://your-project-name.netlify.app](https://your-project-name.netlify.app)

---

## 📂 GitHub Repository

👉 *Add your repo link here*
Example: [https://github.com/your-username/profile-card](https://github.com/your-username/profile-card)

---

## 🧩 Features

* ✅ Semantic HTML structure (`article`, `header`, `figure`, `nav`, `section`)
* ✅ Fully responsive layout (mobile, tablet, desktop)
* ✅ Accessible design (WCAG-friendly contrast, keyboard navigation)
* ✅ Dynamic **current time in milliseconds** using `Date.now()`
* ✅ Avatar image with meaningful `alt` text
* ✅ Social links opening in a new tab securely
* ✅ Clearly structured:

  * Name
  * Bio
  * Avatar
  * Social links
  * Hobbies
  * Dislikes
* ✅ All elements include required `data-testid` attributes for testing

---

## 🧪 Testability

Every visible element includes a `data-testid` attribute as required:

| Element                | data-testid              |
| ---------------------- | ------------------------ |
| Profile Card           | `test-profile-card`      |
| Name                   | `test-user-name`         |
| Bio                    | `test-user-bio`          |
| Time                   | `test-user-time`         |
| Avatar                 | `test-user-avatar`       |
| Social Links Container | `test-user-social-links` |
| Social Items           | `test-user-social-*`     |
| Hobbies                | `test-user-hobbies`      |
| Dislikes               | `test-user-dislikes`     |

---

## ⏱️ Time Implementation

* Uses `Date.now()` to display current epoch time in milliseconds.
* Updates every **1 second** to remain accurate.
* Uses `aria-live="polite"` to notify assistive technologies of updates.

---

## ♿ Accessibility

* Meaningful `alt` text for images
* Proper semantic structure for screen readers
* Keyboard navigable links (Tab + Enter)
* Visible focus states
* `aria-live` for dynamic content updates

---

## 📱 Responsiveness

* **Mobile:** Vertical stacked layout
* **Tablet/Desktop:** Avatar aligned beside content
* Uses **Flexbox/Grid** for flexible scaling
* Handles long text gracefully

---

## 🛠️ Technologies Used

* HTML5
* CSS3 (Flexbox / Grid)
* Vanilla JavaScript

---

## 📦 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/profile-card.git

# Navigate into the project folder
cd profile-card

# Open index.html in your browser
```

---

## 📁 Project Structure

```
/profile-card
│── index.html
│── style.css
│── script.js
└── README.md
```

---

## 📝 Notes

* Social links use:

  ```html
  target="_blank" rel="noopener noreferrer"
  ```
* Avatar supports both URL and uploaded image sources
* Designed to be easily testable with automated tools

---

## 📅 Deadline

**17th April 2026 — 11:59 PM**

---

## 📤 Submission Link

[https://docs.google.com/forms/d/e/1FAIpQLSfyENWbGf9qRkmDj77BIEAPkO0WwIqDpeR6_dte026HA-KuWQ/viewform](https://docs.google.com/forms/d/e/1FAIpQLSfyENWbGf9qRkmDj77BIEAPkO0WwIqDpeR6_dte026HA-KuWQ/viewform)

---
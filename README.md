````markdown
# Job Application Form

A simple, responsive job application form built with HTML and CSS. This project demonstrates clean form structure, user-friendly validation, and interactive styling using CSS pseudo-classes.

## 🚀 Features

- Responsive design
- Custom radio button styles with `:checked`
- Real-time validation using `:valid` and `:invalid`
- Focus styling with `:focus`
- Hover effects on the submit button
- First input field uniquely styled with `:first-of-type`

## 📋 Form Fields

- **Full Name** (`input[type="text"]`, `id="name"`)
- **Email Address** (`input[type="email"]`, `id="email"`)
- **Position** (`select`, `id="position"`)
- **Availability** (`fieldset.radio-group`, `input[type="radio"]`, `name="availability"`)
- **Message** (`textarea`, `id="message"`)
- **Submit Button** (`button[type="submit"]`)

## 🎯 CSS Pseudo-classes Used

- `:focus` – Highlights focused fields
- `:valid`, `:invalid` – Real-time form validation colors
- `:hover` – Submit button hover effect
- `:checked` – Styles for selected radio buttons and labels
- `:first-of-type` – Unique styling for the first input

## 🛠 How to Use

1. Clone the repo or copy the files.
2. Open `index.html` in any browser.
3. Start filling out the form and see the styles react in real-time.

```bash
git clone https://github.com/your-username/job-application-form.git
cd job-application-form
open index.html
````

## 💡 Customization

You can update the positions list, availability options, colors, or form layout to suit your project or brand.

## 📁 File Structure

```
job-application-form/
├── index.html
└── style.css
```

## ✅ Project Goals

This project was built to practice:

* Semantic HTML structure
* Form accessibility
* Pseudo-classes and form validation styling
* CSS selector specificity and order

## 📄 License

This project is open-source and available under the MIT License.

```

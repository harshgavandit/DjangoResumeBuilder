"# Django Resume Builder" 


# 📝 Django Resume Builder

A fully responsive, modern Resume Builder web application created using **Django**, featuring a stylish UI with **gradient backgrounds, glassmorphism cards, hover animations, resume preview**, and **PDF download support** using HTML-to-PDF conversion.

---

## 🚀 Features

### ✅ **1. Beautiful Modern UI**

* Gradient animated background
* Glassmorphism container design
* Attractive buttons with glow and shine effects
* Fully responsive layout for mobile, tablets, and desktops
* Smooth hover animations & section highlights

### ✅ **2. Resume Form Page**

Users can enter:

* Personal Details (Name, Age, Email, Phone)
* About Me / Summary
* Skills (up to 5 skills)
* Languages (up to 3 languages)
* Education (3 entries)
* Work Experience (2 entries)
* Projects (2 entries)
* Achievements (3 entries)

### ✅ **3. Resume Preview Page**

* Well-structured 2-column resume layout
* Auto-filled using Django Template Variables
* Clean typography and professional formatting
* Separate sections with colored accent lines
* Displays all fields in an organized format

### ✅ **4. PDF Download**

* Uses **html2pdf.js** to generate a high-quality A4 PDF
* Maintains layout, colors, spacing, and fonts
* One-click **Download PDF** button
* Fully client-side (no server load for PDF)

### ✅ **5. Django-Powered Backend**

* Django views render form and resume template
* CSRF protection built-in
* Clean URL routing
* Uses Django templates to manage all pages

---

## 📁 Project Structure

```
ResumeBuilder/
│
├── resumeapp/
│   ├── views.py          # Handles form submission & resume rendering
│   ├── urls.py           # App-level URL routes
│   ├── templates/
│   │      ├── index.html       # Resume form page
│   │      ├── resume.html      # Resume preview + PDF page
│   │
│   └── static/ (optional)
│
├── ResumeBuilder/
│   ├── settings.py       # Django project settings
│   ├── urls.py           # Project-level URL routes
│
├── manage.py
├── README.md
└── .gitignore
```

---

## 🔧 Technologies Used

| Technology                          | Purpose                                    |
| ----------------------------------- | ------------------------------------------ |
| **Python**                          | Backend logic                              |
| **Django**                          | Form handling, routing, template rendering |
| **HTML / CSS**                      | Frontend UI                                |
| **JavaScript**                      | PDF generation (html2pdf.js)               |
| **Bootstrap-like styling (custom)** | Responsive layout                          |
| **html2pdf.js**                     | Convert resume preview to PDF              |

---

## 🛠 Setup Instructions

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/resume-builder.git
cd resume-builder
```

### **2. Create a Virtual Environment**

```bash
python -m venv venv
```

Activate:

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### **3. Install Dependencies**

```bash
pip install django
```

### **4. Run the Server**

```bash
python manage.py runserver
```

Your Resume Builder will be live at:
➡️ [http://127.0.0.1:8000/]

---

## 🖼 Screenshots (Optional)

You can add screenshots like:

```
![Home Page](screenshots/home.png)
![Resume Preview](screenshots/resume.png)
```

---

## 🎯 How It Works

### **Step 1:** User fills the form

The form collects all resume information such as skills, education, experience, languages, achievements, etc.

### **Step 2:** Django processes data

The form data is sent to a Django view, which renders the preview template (`resume.html`).

### **Step 3:** Resume Preview

Data appears in a pre-designed resume format with modern styling.

### **Step 4:** Download as PDF

Users click **Download PDF**, which converts the resume section into a full PDF.

---

## 🧩 Customization Options

You can easily customize:

* Colors (accent gradients, glow effects)
* Fonts
* Resume structure & layout
* Custom sections (certifications, social links, portfolios)

---

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---



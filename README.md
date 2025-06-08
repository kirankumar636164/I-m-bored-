# 💤 I'm Bored – Activity Suggestion Web App

A fun, lightweight web application that fetches ideas from the **Bored API** and tells you what to do when you're bored. Filter by activity type and number of participants—or let fate decide with a random pick!

---

## 🚀 Live Preview

_This project isn’t deployed yet. Follow the steps below to run it locally._

---

## 🛠️ Features

- **Random activity** displayed on page load.
- **Filters**  
  - Activity **type** (education, recreational, DIY, etc.)  
  - **Participants** (1 – 4+)  
- Shows activity name, type, and participant count.
- Graceful error handling when no activities match.

---

## 📦 Tech Stack

| Layer           | Library / Service |
|-----------------|-------------------|
| **Backend**    | Node.js, Express |
| **Templating**  | EJS              |
| **HTTP Client** | Axios            |
| **Styling**     | Vanilla CSS      |
| **API**         | [Bored API by App Brewery](https://bored-api.appbrewery.com/) |

---

## 📁 Project Structure
├── public/
│ └── styles/
│ └── main.css
├── views/
│ └── solution.ejs
├── app.js
├── package.json
└── README.md


## 📥 Installation & Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/im-bored-app.git
   cd im-bored-app
Install dependencies

npm install
Run the server

node app.js
Open in browser

Navigate to http://localhost:3000

🧪 Usage
Landing page instantly suggests a random activity.

Adjust filters (type, participants) as desired.

Click Go to receive a personalized suggestion.

🐞 Error Handling
If no activities match your filters, a friendly error message appears.

📌 Roadmap / To-Do
Add price & accessibility filters.

Polish UI/UX (animations, dark mode).

Deploy on Render, Vercel, or Railway.

Integrate tests & GitHub Actions workflow.

👤 Author
Kiran Kumar B

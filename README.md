# Pedagogy App 🇺🇿

A modern educational web application designed for pedagogy students in Uzbekistan. The app provides a platform for competitions, article submissions, access to the latest books and methodologies, monthly tests, and AI-powered support—all in a fast, easy-to-use frontend.

---

## ✨ Features

- **User Registration:**  
  Register with your name, surname, educational institution, and field of study.

- **Competitions:**  
  Participate in author-created pedagogy competitions.

- **Books & Scientific Works:**  
  Browse the latest pedagogy books and scientific works.

- **Articles:**  
  Submit your own articles, vote for peers, and earn monthly rewards.

- **Translations:**  
  Access a curated list of the latest translated books.

- **Teaching Methodologies:**  
  Learn about the latest domestic and international teaching methodologies.

- **Monthly Book Club:**  
  Discover the book of the month, take end-of-month quizzes, and earn certificates.

- **AI Chatbot Support:**  
  Get guidance and support from an integrated AI chatbot.

---

## 🚀 Tech Stack

- **Frontend:** React (or Next.js), Vite
- **Styling:** Tailwind CSS / Material UI / Ant Design
- **State Management:** Context API / Zustand
- **Authentication:** Local/session storage (frontend only)
- **File Uploads & Voting:** Handled in-browser (localStorage for MVP)
- **AI Integration:** Embeddable AI chatbot (iframe or SDK; mock for MVP)

---

## 🏁 Getting Started

```bash
git clone https://github.com/cambobart/v0-educational-pedagogy-app.git
cd v0-educational-pedagogy-app
npm install
npm run dev
```

- Open [http://localhost:5173](http://localhost:5173) in your browser (or the port shown in your terminal).

---

## 📂 Project Structure

```
src/
├── assets/          # Images, icons, etc.
├── components/      # Reusable components (Auth, Books, Articles, etc.)
├── pages/           # Page-level components
├── hooks/           # Custom React hooks
├── utils/           # Helper functions
├── data/            # Local JSON/data mocks
├── styles/          # Global and component styles
├── App.tsx
└── main.tsx
```

---

## 🧑‍💻 Contributing

Contributions, suggestions, and bug reports are welcome!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 📣 Contact

Questions or feedback?  
Open an issue or contact [@cambobart](https://github.com/cambobart).

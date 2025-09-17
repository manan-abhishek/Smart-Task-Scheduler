Smart Task Scheduler 🗂️

A Role-Based Employee Task Management System built with React.js, Context API, and Tailwind CSS.
It allows Admins to create, assign, and track tasks, while Employees can view and update their task progress in real-time.

✨ Features
🔑 Authentication & Role Management

Role-based login (Admin / Employee)

Secure session handling with localStorage

📊 Admin Dashboard

Assign tasks to employees with title, due date, category, and description

Monitor task status: New, Active, Completed, Failed

Get an overview of employee performance in a structured table

👨‍💻 Employee Dashboard

View assigned tasks with real-time status updates

Track progress across different task categories

Update task completion status

⚡ Tech Stack

React.js (Vite) – Frontend framework

Context API – State management

Tailwind CSS – UI styling

LocalStorage – Session persistence

📸 Screenshots
Admin Dashboard

Employee Dashboard

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/Smart-Task-Scheduler.git
cd Smart-Task-Scheduler

2. Install Dependencies
npm install

3. Start the Development Server
npm run dev

👥 Roles

Admin

Email: admin@example.com

Password: 123

Employee

Credentials are pre-stored in context (AuthProvider.js).

📂 Folder Structure
Smart-Task-Scheduler/
│── public/              # Static assets
│── src/
│   ├── components/      # Reusable UI components
│   ├── context/         # AuthProvider & Context API
│   ├── pages/           # Dashboard pages
│   ├── App.js           # Main App entry
│── package.json
│── tailwind.config.js
│── vite.config.js

💡 Future Enhancements

🔐 JWT-based authentication (instead of localStorage)

🗄️ Backend integration with Node.js & MongoDB

📱 Mobile responsive enhancements

📊 Advanced analytics for task performance

🤝 Contributing

Contributions are welcome! Feel free to fork this repo and raise a pull request.

📜 License

This project is MIT Licensed – free to use and modify.

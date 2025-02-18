# OJT Program Front-End

Welcome to the **OJT Program Front-End** repository! This project is the front-end implementation for the **On-the-Job Training (OJT) Program** developed by **PyGenicArc**. It provides an interactive UI for trainees to engage with the training platform.

## 🚀 Features
- **User Authentication**: Secure login and registration system.
- **Dashboard**: Overview of tasks, progress tracking, and course materials.
- **Interactive Learning**: Modules, quizzes, and assignments.
- **Responsive Design**: Optimized for desktop and mobile use.
- **API Integration**: Communicates with the backend for data retrieval and updates.

## 📂 Project Structure
```
/ojt_program_front_end
│── public/             # Static assets
│── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Page-level components
│   ├── services/       # API calls and data fetching
│   ├── styles/         # CSS and styling
│   ├── App.js          # Main application component
│   ├── index.js        # Entry point
│── package.json        # Dependencies and scripts
│── README.md           # Documentation
```

## 🛠️ Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/pygenicarc/ojt_program_front_end.git
   ```
2. **Navigate to the project folder**:
   ```bash
   cd ojt_program_front_end
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Run the development server**:
   ```bash
   npm start
   ```
   The application will be available at `http://localhost:3000`

## 📡 API Configuration
Ensure the backend API is running and update the API base URL in the `services/api.js` file:
```javascript
const BASE_URL = 'http://localhost:5000/api';
```

## 📦 Build for Production
To create an optimized production build, run:
```bash
npm run build
```

## 🤝 Contributing
We welcome contributions! If you’d like to improve this project:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## 📜 License
This project is licensed under the **MIT License**.

## 📧 Contact
For queries, reach out to **PyGenicArc**:
- Website: [pygenicarc.com](https://pygenicarc.com)
- Email: support@pygenicarc.com


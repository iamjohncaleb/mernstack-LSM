# MERN LSM (Learning Management System)

A full-stack Learning Management System (LMS) built using the MERN (MongoDB, Express.js, React, Node.js) stack, designed to provide seamless online learning experiences.

## Features
- 🎓 **User Authentication** - Secure login & registration with JWT.
- 📚 **Course Management** - Create, update, and manage courses.
- 📖 **Lesson & Content Delivery** - Structured learning modules.
- 📊 **Progress Tracking** - Monitor student progress.
- 💬 **Interactive Discussions** - Engage students with Q&A.
- 🛠 **Admin Dashboard** - Manage users, courses, and content.

## Tech Stack
- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT, bcrypt
- **Deployment:** Docker, AWS, Vercel

## Getting Started

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [MongoDB](https://www.mongodb.com/)
- [Docker](https://www.docker.com/) (optional for containerization)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/iamjohncaleb/mernstack-LSM.git
   cd mern-lsm
   ```
2. Install dependencies:
   ```sh
   npm install
   cd client && npm install
   ```

### Running the Application
#### Backend
```sh
npm run dev
```

#### Frontend
```sh
cd client
npm start
```

#### Using Docker
```sh
docker-compose up --build
```

### API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | `/api/auth/register` | Register new user |
| POST | `/api/auth/login` | User login |
| GET | `/api/courses` | Fetch available courses |
| POST | `/api/courses` | Create a new course |

## Environment Variables
Create a `.env` file in both root and `client` directory:
```
PORT=5000
MONGO_URI=mongodb://localhost:27017/lsm
JWT_SECRET=your_secret_key
```

## Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Add feature"`)
4. Push to branch (`git push origin feature-name`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! 🚀

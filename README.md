# JARAS Assessment

Welcome aboard, fellow developer! 🌟

We're thrilled to have you join our team and can't wait to see the incredible things you'll achieve with us. This is the start of an exciting journey where you'll learn, grow, and make a real impact.

Remember, we're all here to support you every step of the way. Don’t hesitate to ask questions, share ideas, and dive into new challenges.

## 📚 Stack

- [Next.js](https://www.nextjs.org/) - The React Framework for the Web.
- [Django](https://www.djangoproject.com/) - Django makes it easier to build better web apps more quickly and with less code.
- [TypeScript](https://www.typescriptlang.org/) - JavaScript with syntax for types.
- [Docker](https://www.docker.com/) - A platform designed to help developers build, share, and run modern applications. We handle the tedious setup, so you can focus on the code.

## ✅ System Requirements

- [ ] Docker: [Install Docker](https://docs.docker.com/get-docker/)
- [ ] Node.js: [Install Node.js](https://nodejs.org/en/download/)
- [ ] Python: [Install Python](https://www.python.org/downloads/)
- [ ] TypeScript: [Install TypeScript](https://www.typescriptlang.org/download)
- [ ] Git: [Install Git](https://git-scm.com/downloads)
- [ ] VS Code: [Install VS Code](https://code.visualstudio.com/download)
- [ ] GitLab Account: [Create GitLab Account](https://git.ajjir.co/users/sign_in)

### Assessment Guidelines

The assessment is divided into backend and frontend tasks. While completing both is beneficial, it's not mandatory. We use a point system to evaluate the final result, allowing you to earn points for each completed task. If you prefer to focus on the frontend, you can simulate backend integration using state management tools like [Zustand](https://zustand-demo.pmnd.rs/) or API mocking libraries such as [MSW.js](https://mswjs.io/).

Focus on showcasing your skills, whether it's through API integration, frontend architecture, or using alternative approaches to simulate backend interactions.

### Backend Requirements

- [ ] After cloning the project, create a Python virtual environment and install dependencies from `requirements.txt`.
- [ ] Search the entire project for `TODO:` comments and complete them in order.
- [ ] After finishing each TODO, run the tests with pytest using:
  ```bash
  $ pytest
  ```
  Alternatively, if you are using VS Code, navigate to the testing tab and run them from there.

### Frontend Requirements

- [ ] **Customers List Page**: Display a list of customers.
- [ ] **Customer Form**: Create a form to add a new customer.
- [ ] **Reservations List**: Display a list of hotel reservations.
- [ ] **Reservation Form**: Create a form to book a room, selecting customer, room, and reservation details.
- [ ] **API Integration**: Integrate frontend components with backend API endpoints, or simulate the integration using state management (e.g., Zustand) or mocking (e.g., MSW.js).

## 📁 Project Structure

```
$PROJECT_ROOT
│
├── server  # Django Backend
│
├── client  # Next.js App
```

---

### 🏆 Getting Started:

- Fork the Repo
- Clone Your Forked Repo Locally
- Run the Project Using Docker

```docker
docker-compose up --build
```

_Open [Django Server](http://0.0.0.0:8000) in : [http://0.0.0.0:8000](http://0.0.0.0:8000)_ <br/>
_Open [Django Admin](http://0.0.0.0:8000/admin) in : [http://0.0.0.0:8000/admin](http://0.0.0.0:8000/admin)_ <br/>
_Open [Next.js Server](http://0.0.0.0) in : [http://0.0.0.0](http://0.0.0.0)_ <br/>

## Manual Setup:

### For Django:

1. Create a Virtual Environment for Python

```bash
cd server
pip install virtualenv
python -m venv .
```

2. Activate the Virtual Environment

```bash
source Scripts/activate
```

**Windows Users use: `.\Scripts\activate`**

3. Install Dependencies

```bash
pip install -r server/requirements.txt
```

4. Make Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### For Frontend

1. Install Dependencies

```bash
cd client
npm install
```

2. Run the Development Server

```bash
npm run dev
```

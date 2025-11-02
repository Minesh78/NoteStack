
# NoteStack - MERN Powered Notes App 🚀

Ever have a brilliant idea, write it on a sticky note, and then immediately lose it to the desk-abyss? Yeah, me too.

This project is the digital solution! It's a full-stack Notes Application built with the mighty **MERN** stack (MongoDB, Express.js, React.js, and Node.js). It lets you create, read, update, and delete notes, so your genius ideas are safe.



## ✨ Features (What it Does)

* ✍️ **Create:** Jot down new notes faster than you can find a working pen.
* 👀 **Read:** See all your brilliant (or not-so-brilliant) ideas in one clean list.
* ✏️ **Update:** Fix those embarrassing typos or add more genius to an existing note.
* 🗑️ **Delete:** Get rid of notes you no longer need. Marie Kondo would be proud.

## 🛠️ The Tech Stack (Our MERN-tastic Tools)

This app is built with four key technologies that play very nicely together.

### 🤖 The Backend (The "Engine Room")
* **[M]ongoDB:** Our cool, flexible NoSQL database. This is where all your notes are stored safely.
* **[E]xpress.js:** The fast, minimalist web framework that builds our API. It's the waiter that takes requests from the frontend and tells the database what to do.
* **[N]ode.js:** The JavaScript runtime that powers our server. It's the environment our Express.js waiter "lives" in.
* **Mongoose:** A neat library that makes talking to MongoDB from Node.js way less of a headache.

### 🎨 The Frontend (The "Pretty Face")
* **[R]eact.js:** The "R" in MERN! This JavaScript library builds our snappy, single-page user interface.
* **React Hooks:** We use `useState` and `useEffect` to manage the app's state without pulling our hair out.
* **Axios:** The friendly neighborhood messenger that delivers HTTP requests from our frontend to our backend API.
* **CSS / Styling:** Making it all look good! *(Feel free to specify if you used plain CSS, Tailwind, Material-UI, etc.)*

## 🚀 How to Get This Thing Running

Want to run this project locally? Let's do it.

### Prerequisites (The Shopping List)
* [Node.js](https://nodejs.org/) (Can't run JavaScript without it!)
* [MongoDB](https://www.mongodb.com/try/download/community) (Gotta have the database running.)
* A code editor (Like [VS Code](https://code.visualstudio.com/))
* A terminal (or command prompt)

### 1. Clone This Repo

First, grab the code from GitHub.

```bash
git clone https://github.com/Minesh78/NoteStack.git
cd NoteStack
````

### 2\. Fire up the Backend 🔥

In your terminal, navigate to the backend folder.

```bash
# Go into the backend directory
cd backend

# Install all the packages it needs
npm install

# Create a .env file in this 'backend' folder.
# Inside, add your MongoDB connection string like this:
MONGO_URI=your_mongodb_connection_string_goes_here
PORT=5000

# Start the backend server!
npm start
```

Your backend API should now be live and listening at `http://localhost:5000`.

### 3\. Launch the Frontend 🎨

Open a **new terminal** and navigate to the frontend folder.

```bash
# Go into the frontend directory
cd frontend

# Install its packages
npm install

# Start the React app
npm start
```

And... voilà\! Your browser should automatically open to `http://localhost:3000`, and you can start making notes.

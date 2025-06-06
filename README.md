

---

````markdown
# Python Chat Application Using Sockets

A real-time chat application built with Python, demonstrating client-server architecture, socket programming, and multithreading. The app supports user registration and login with password hashing, public and private messaging, chat history logging, and an optional GUI client built with Tkinter.

---

## Features

- **User Authentication**  
  Register new users and log in securely with SHA-256 password hashing.

- **Public & Private Messaging**  
  Send messages publicly to all connected users or privately using `/msg <username>`.

- **Chat History Logging**  
  All messages are saved to a log file, with the ability to retrieve full chat history via `/history`.

- **Multithreaded Server**  
  Handles multiple clients concurrently for real-time communication.

- **Optional GUI Client**  
  A Tkinter-based graphical client for an enhanced user experience.

---

## Getting Started

### Prerequisites

- Python 3.x installed on your system

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
````

2. Run the server:

   ```bash
   python server.py
   ```

3. Run one or more clients in separate terminals:

   ```bash
   python client.py
   ```

   Or, for the GUI client:

   ```bash
   python client_gui.py
   ```

---

## Usage

### Client Commands

* **Register/Login**: Follow prompts on startup.

* **Send Public Message**: Just type your message and hit Enter.

* **Send Private Message**:

  ```
  /msg <username> <message>
  ```

* **View Chat History**:

  ```
  /history
  ```

---

## Project Structure

```
chat-app/
├── server.py           # Server-side application
├── client.py           # Console client application
├── client_gui.py       # GUI client application (Tkinter)
├── users.txt           # Stores registered users and hashed passwords
├── chat_history.txt    # Stores chat logs
└── README.md           # This file
```

---

## Future Improvements

* Add end-to-end encryption for messages
* Implement file sharing between clients
* Display online users with a `/users` command
* Improve GUI with tabs, user list, and better styling

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

```

---

Let me know if you'd like me to generate a `LICENSE` file or include badges (e.g., Python version, license type, GitHub stars).
```

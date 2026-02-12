# WebRTC Video Calling Application

A real-time web application that enables peer-to-peer audio and video communication using WebRTC. This project demonstrates the core concepts of real-time communication, signaling, and media streaming in the browser.

---

## 🚀 Features

* Real-time peer-to-peer video calling
* Audio communication with low latency
* Browser-based (no plugins required)
* Simple and clean user interface
* Secure media streaming using WebRTC

---

## 🛠 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Real-time Communication:** WebRTC
* **Signaling Server:** Node.js, Express, Socket.IO
* **STUN/TURN:** Public STUN servers (for NAT traversal)

---

## 📂 Project Structure

```
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── server.js
├── package.json
└── README.md
```

---

## ⚙️ How It Works

1. Users join a room using a unique room ID
2. A signaling server exchanges offer, answer, and ICE candidates
3. WebRTC establishes a direct peer-to-peer connection
4. Audio and video streams are shared in real time

---

## ▶️ Getting Started

### Prerequisites

* Node.js installed
* A modern web browser (Chrome, Firefox, Edge)

### Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install
```

### Run the Project

```bash
node server.js
```

Open your browser and navigate to:

```
http://localhost:3000
```

---

## 🧪 Usage

* Open the app in two different browsers or devices
* Join the same room ID
* Allow camera and microphone access
* Start real-time video communication

---

## 📌 Learning Outcomes

* Understanding WebRTC core concepts
* Handling signaling with Socket.IO
* Managing media streams in the browser
* Implementing peer-to-peer communication

---

## 🔮 Future Improvements

* Screen sharing support
* Chat messaging
* Improved UI/UX
* TURN server integration for better connectivity

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

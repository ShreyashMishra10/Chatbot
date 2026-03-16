# 🤖 Chatbot

A clean, responsive chatbot interface built using **React** and **Babel** (via CDN). This project features a real-time message history, automated responses, and auto-scrolling functionality.

---

## 🚀 Features

* **Real-time Interaction:** Send messages and receive instant replies from the Chatbot logic.
* **Auto-Scroll:** The chat window automatically scrolls to the latest message using React `useRef` and `useEffect`.
* **Dynamic UI:** Uses conditional rendering to distinguish between User and Robot messages with unique styling and profile icons.
* **State Management:** Built with React Hooks (`useState`) to manage the conversation flow.

---

## 🛠️ Tech Stack

* **Frontend:** React.js
* **Compiler:** Babel (Browser-based)
* **Styling:** CSS3 (Flexbox for layout)
* **Backend Logic:** `supersimpledev/chatbot.js` (Mock Chatbot API)

---

## 📸 Preview

The app features a centered, mobile-friendly container (**max-width: 600px**) with:

* **Green "Send" button** styling.
* **Message bubbles** for both the user and the robot.
* **A scrollable message container** with a hidden scrollbar for a clean look.

---

## ⚙️ How to Run Locally

Since this project uses CDNs for React and Babel, you don't need to install Node.js dependencies or run `npm install`.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ShreyashMishra10/Chatbot.git]
   ```
2. **Open the folder:**

    ```bash
    cd YOUR_REPO_NAME
    ```
3. **Launch the App:**
    Simply open the index.html file in any modern web browser.

    Note: Ensure you have an internet connection so the browser can load the React and Chatbot scripts from unpkg.com.
   
## 📂 Project Structure
* **index.html:** Contains the HTML structure, CSS styles, and React components.

* **robot.png:** Profile icon for the chatbot.

* **user.png**: Profile icon for the user.

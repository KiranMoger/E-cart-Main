🛒 React E-Mart

GitHub Repository Description

React E-Mart is a medium-scale e-commerce frontend application built using React and Vite. The project demonstrates real-world React concepts such as component-based architecture, state management, reusable UI components, and dynamic data rendering. It is designed for learning, interview preparation, and showcasing frontend development skills.

--------------------------------------------------

🚀 Tech Stack

- React (Functional Components)
- Vite (Fast build tool)
- JavaScript (ES6+)
- HTML5 & CSS3
- npm for dependency management

--------------------------------------------------

📂 1️⃣ Project Folder Structure (Detailed Explanation)

React-E-Mart/
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── node_modules/
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── components/
    ├── pages/
    ├── assets/
    ├── styles/
    └── data/

Root Level Files

- index.html  
  Main HTML file where the React app is injected

- package.json  
  Contains project metadata, dependencies, and scripts

- vite.config.js  
  Configuration file for Vite

- node_modules/  
  Contains all installed npm packages (not written by the developer)

--------------------------------------------------

src Folder (Heart of the Project)

main.jsx  
- Entry point of the React application  
- Uses ReactDOM.createRoot() to render App into the DOM

App.jsx  
- Root React component  
- Acts as the main container for the entire application  
- Responsible for layout structure and rendering major components/pages

components/  
- Contains reusable UI components  
- Examples: Header, Product Card, Navbar, Buttons  
- Promotes reusability and clean architecture

pages/  
- Represents full screens/pages of the app  
- Examples: Home Page, Products Page, Cart Page  
- Each page combines multiple components

assets/  
- Stores static resources such as images and icons

styles/  
- Contains CSS files for styling components and pages

data/  
- Contains static or mock product data  
- Used to simulate backend data in frontend-only apps

--------------------------------------------------

🔄 2️⃣ Application Flow (What Happens When User Opens the App)

1. User opens the website in the browser
2. index.html loads first
3. main.jsx executes and mounts the React app
4. App component is rendered
5. App loads layout (Navbar / Header) and default page (Home / Product Listing)
6. User interacts by clicking products, navigating UI, and adding items to cart
7. React updates the UI dynamically using state changes without page reloads

This follows the Single Page Application (SPA) concept.

--------------------------------------------------

🧩 3️⃣ Core Feature Explanation – Product Listing & Cart Flow

Product Listing

- Product data is stored in the data folder or passed as props
- Products are displayed using reusable Product Card components
- Each card shows product image, name, price, and Add to Cart button

Cart Functionality (Conceptual Flow)

1. User clicks Add to Cart
2. Product data is passed to a handler function
3. Cart state is updated using useState
4. React re-renders cart-related components
5. Cart UI reflects added items, quantity, and total price

React Concepts Used

- useState for cart and UI state
- Props for data flow between components
- Component re-rendering on state updates

--------------------------------------------------

🎯 Key Learning Outcomes

- Clear understanding of React project structure
- Hands-on experience with component-based design
- Understanding data flow in React applications
- Practical exposure to real-world frontend architecture

--------------------------------------------------

💡 Future Improvements

- Integrate backend APIs
- Add user authentication
- Persist cart using localStorage
- Improve performance using memoization

--------------------------------------------------

▶️ How to Run the Project Locally

Prerequisites

- Node.js (v16 or above recommended)
- npm (comes with Node.js)

Steps to Run

1. Clone or download the project

git clone <repository-url>

OR download the ZIP and extract it

2. Navigate to project folder

cd React-E-Mart

3. Install dependencies

npm install

4. Start the development server

npm run dev

5. Open in browser

http://localhost:5173

--------------------------------------------------

👨‍💻 Author

Kiran Moger

This project is part of my learning journey in React and frontend development.

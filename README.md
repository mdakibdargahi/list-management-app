# 📋 List Management App – React + Redux Toolkit

A feature-rich practice app for managing multiple lists using **React**, **Redux Toolkit**, and **Tailwind CSS**. This project demonstrates core Redux concepts like slices, reducers, actions, selectors, and state management for arrays.

## 🚀 Live Demo

*(Add your deployed link here if applicable)*

## ✨ Features Implemented (v1.0)

### ✅ Completed Lists

| List | Functionality |
|------|----------------|
| 🛒 **Grocery List** | Add items, check/uncheck, delete items |
| 💝 **Wishlist** | Add items with name & price, remove items, view total cost |
| 📚 **Reading List** | Add books (title + author), mark as read/unread, filter by status (All/Read/Unread) |
| 🎯 **Bucket List** | Add life goals, mark completed, progress bar, remaining count |

### 🔜 Planned Features
- Contact List (search by name)
- Playlist Builder (reorder songs)
- Packing Checklist (progress %)
- Favorite Colors (hex swatches)
- Recipe Ingredients (scale amounts)
- Daily Tasks (priority & sorting)

## 🛠️ Tech Stack

- **React 19** – UI library
- **Redux Toolkit** – State management
- **React-Redux** – React bindings
- **Tailwind CSS** – Styling
- **Vite** – Build tool

## 📁 Project Structure (RTK Recommended)
src/
├── app/
│ └── store.js # Redux store configuration
├── features/
│ ├── grocery/
│ │ ├── grocerySlice.js # Slice: add/toggle/delete items
│ │ └── GroceryList.jsx # UI component
│ ├── wishlist/
│ │ ├── wishlistSlice.js # Slice: add/delete + total selector
│ │ └── Wishlist.jsx
│ ├── reading/
│ │ ├── readingSlice.js # Slice: add/toggle/delete + filter
│ │ └── ReadingList.jsx
│ ├── bucket/
│ │ ├── bucketSlice.js # Slice: add/toggle/delete + remaining count
│ │ └── BucketList.jsx
├── components/
│ └── Navbar.jsx # Navigation between lists
├── App.jsx
├── main.jsx
└── index.css

text

## 🧪 Getting Started

### Prerequisites
- Node.js (v14+)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/list-management-app.git
   cd list-management-app
Install dependencies

bash
npm install
Run the development server

bash
npm run dev
Open http://localhost:5173 in your browser.

🎯 How to Use
Navigation
Use the navbar at the top to switch between different list managers.

Grocery List
Type an item and click Add.

Check the box to mark as bought (strikethrough).

Click ✖ to delete an item.

Wishlist
Enter item name and price (numbers only).

Total cost updates automatically.

Delete items to remove them from the wishlist.

Reading List
Add a book with title and author.

Use Mark Read/Unread toggles.

Filter books by All, Read, or Unread.

View stats: total books, read count.

Bucket List
Add a life goal.

Check the box to mark as completed.

Watch the progress bar fill up.

See remaining goals count.

📸 Screenshots
(Add screenshots of each list here)

🧠 Redux Toolkit Concepts Demonstrated
Concept	Implementation
Slices	Each list has its own slice (createSlice)
Actions	Auto-generated actions (add, delete, toggle)
Reducers	Immutable updates using Immer
Prepare Callbacks	Used in addBook, addGoal to generate nanoid
Selectors	selectAllBooks, selectRemainingCount, etc.
Store Configuration	Multiple reducers combined in configureStore
🎨 Styling
All components use Tailwind CSS utility classes. The design is fully responsive and includes:

Gradient backgrounds

Hover effects

Progress bar animations

Responsive grid/flex layouts

🤝 Contributing
Feel free to fork this project and add the remaining list managers! Check the Planned Features section.

📄 License
MIT

👨‍💻 Author
Your Name – MD AKIB DARGAHI

Happy coding! 🚀

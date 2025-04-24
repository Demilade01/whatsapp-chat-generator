# React Quick Chat

React Quick Chat is a simple web application that allows users to quickly generate WhatsApp chat links for one or multiple phone numbers with a custom message. The app is built using React, Vite, TailwindCSS, and Recoil for state management.

## Features

- Generate WhatsApp chat links for single or multiple phone numbers.
- Add a custom message to the chat link.
- Copy individual or all generated links to the clipboard.
- Delete all generated links.
- Responsive design with TailwindCSS.
- Error handling for invalid input (e.g., special characters or letters in phone numbers).

## Tech Stack

- **React**: Frontend framework.
- **Vite**: Build tool for fast development.
- **TailwindCSS**: Utility-first CSS framework for styling.
- **Recoil**: State management library.
- **React Router**: For routing.
- **React Toastify**: For notifications.
- **React Icons**: For icons.

## Folder Structure

```
react-quick-chat/
├── public/
│   └── _redirects          # Netlify redirects configuration
├── src/
│   ├── components/         # Reusable components (e.g., Loading)
│   ├── layouts/            # Layout components (MainLayout, ContentLayout)
│   ├── views/              # Page components (Home, NotFound)
│   ├── router/             # App routing configuration
│   ├── store/              # Recoil state management setup
│   ├── Helper/             # Helper functions and constants
│   ├── App.jsx             # Main app component
│   ├── main.jsx            # Entry point
│   ├── index.css           # Global styles
├── index.html              # HTML template
├── tailwind.config.cjs     # TailwindCSS configuration
├── vite.config.js          # Vite configuration
├── package.json            # Project dependencies and scripts
├── postcss.config.cjs      # PostCSS configuration
└── .gitignore              # Git ignore file
```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-quick-chat.git
   cd react-quick-chat
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the app in your browser at `http://localhost:5173`.

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the app for production.
- `npm run preview`: Preview the production build.

## Configuration

### TailwindCSS
The TailwindCSS configuration is located in tailwind.config.cjs. You can customize the theme, colors, and fonts as needed.

### Vite
The Vite configuration is in vite.config.js. It includes an alias for the src directory (`@`).

### Redirects
The _redirects file in the public folder ensures proper routing for single-page applications when deployed on platforms like Netlify.

## Deployment

To deploy the app:

1. Build the app:

   ```bash
   npm run build
   ```

2. Deploy the `dist` folder to your hosting provider (e.g., Netlify, Vercel).

## License

This project is licensed under the MIT License.

## Acknowledgments

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [Recoil](https://recoiljs.org/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
- [React Icons](https://react-icons.github.io/react-icons/)

---

Feel free to contribute to this project by submitting issues or pull requests!
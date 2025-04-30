# Blog-React

A modern blogging platform built with **ReactJS** for the frontend and **Appwrite** for the backend. This application allows users to create, edit, and manage blog posts with a seamless and responsive user interface.

---

## Features

- User authentication and authorization.
- Create, edit, and delete blog posts.
- Rich text editor for content creation.
- Image upload and management.
- Responsive design for all devices.

---

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [Appwrite](https://appwrite.io/) backend configured
- A modern web browser

---

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/arafatDU/blog-react.git
cd blog-react
```

#### 2. Install Dependencies

Run the following command to install all required dependencies:

```bash
npm install
```

#### 3. Configure Environment Variables

Rename the `.env.example` file to `.env` and update the following variables with your Appwrite configuration:

```env
VITE_APPWRITE_URL="<Your Appwrite Endpoint>"
VITE_APPWRITE_PROJECT_ID="<Your Project ID>"
VITE_APPWRITE_DATABASE_ID="<Your Database ID>"
VITE_APPWRITE_COLLECTION_ID="<Your Collection ID>"
VITE_APPWRITE_BUCKET_ID="<Your Bucket ID>"
VITE_TINY_API_KEY="<Your TinyMCE API Key>"
```

---

### Running the Application

Start the development server with the following command:

```bash
npm run dev
```

The application will be available at `http://localhost:5173`.

---

## Project Structure

```
.
├── public/               # Static assets
├── src/                  # Source code
│   ├── appwrite/         # Appwrite service configurations
│   ├── components/       # Reusable React components
│   ├── pages/            # Application pages
│   ├── store/            # Redux store and slices
│   ├── conf/             # Configuration files
│   └── main.jsx          # Application entry point
├── .env.example          # Environment variable template
├── package.json          # Project metadata and dependencies
├── tailwind.config.js    # Tailwind CSS configuration
└── vite.config.js        # Vite configuration
```

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any feature additions or bug fixes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- [ReactJS](https://reactjs.org/)
- [Appwrite](https://appwrite.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TinyMCE](https://www.tiny.cloud/)
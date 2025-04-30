# Blog-React
A ReactJS Blog application with Appwrite.

## Running Locally

### 0. Requirements

This Blog application uses ReacJS for the frontend and Appwrite as Backend.
Make sure You have Node JS installed on your PC.


### 1. Initial setup

No surprise in the first step:

```bash
git clone https://github.com/arafatDU/blog-react.git
cd blog-react
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Setup MongoDB Database:

Rename ".env.example" file to .env and update 

```bash
VITE_APPWRITE_URL=""
VITE_APPWRITE_PROJECT_ID=""
VITE_APPWRITE_DATABASE_ID=""
VITE_APPWRITE_COLLECTION_ID=""
VITE_APPWRITE_BUCKET_ID=""
VITE_TINY_API_KEY=""
```

### 4. Running the IDE

```bash
npm run dev
```
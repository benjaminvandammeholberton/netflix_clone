# Netflix Clone

This repository is for learning purposes and contains a Netflix clone built with Next.js and Prisma.

## Features:

### User Actions:
- **Login and Register:** Users can log in to their accounts or register using email or OAuth providers (Google and GitHub).
- **Movie Selection:** Users can browse a selection of movies on the main screen.
- **Preview:** Users can preview movies before watching.
- **Launch Movie:** Users can launch selected movies for playback.

### Authentication:
- Handles authentication using email.
- Supports OAuth authentication with Google and GitHub.

## Technologies Used:

- Framework: Next.js
- Database: MongoDB (via Prisma)
- Styling: Tailwind CSS

## Usage:

1. **Clone the Repository:**

```
git clone https://github.com/your-username/netflix-clone.git
```

2. **Navigate to the Root Directory:**

```
cd netflix_clone
```

3. **Configure Environment Variables:**

- Modify the .env file in the root directory.
- Populate the .env file with the following variables:

```
DATABASE_URL=your-mongodb-connection-string
NEXTAUTH_JWT_SECRET=your-jwt-secret
NEXTAUTH_SECRET=your-secret-key
GITHUB_CLIENT_ID=your-github-client-id
GITHUB_SECRET=your-github-client-secret
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
```

Make sure to replace `your-mongodb-connection-string`, `your-secret-key`, `your-jwt-secret`, `your-github-client-id`, `your-github-client-secret`, `your-google-client-id`, and `your-google-client-secret` with your actual values.

4. **Install Project Packages:**

```
yarn install
```

5. **Launch the Server:**

```
yarn dev
```

6. **Access the Application:**

Open your web browser and navigate to the specified URL where the server is running (typically `http://localhost:3000`).

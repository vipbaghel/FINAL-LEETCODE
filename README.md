

# LeetCode Clone

A full-stack LeetCode clone built with Next.js, TypeScript, Tailwind CSS, and Firebase. Practice coding problems, track progress, and enjoy a modern UI inspired by LeetCode.

## Features

- User authentication (Firebase)
- Browse and solve coding problems
- Timer and workspace for coding
- Progress tracking
- Responsive design with Tailwind CSS
- Problem management and mock data
- vedio solution of each problem

## Folder Structure

```
LeetCode/
├── leetcode/
│   ├── public/                # Static assets (images, icons)
│   ├── src/
│   │   ├── atoms/             # Recoil atoms (state management)
│   │   ├── components/        # UI components (Navbar, ProblemsTable, Modals, etc.)
│   │   ├── firebase/          # Firebase config
│   │   ├── hooks/             # Custom React hooks
│   │   ├── mockProblems/      # Mock problems data
│   │   ├── pages/             # Next.js pages (routing)
│   │   ├── styles/            # Global styles
│   │   └── utils/             # Utility functions and types
│   ├── .env.local             # Environment variables
│   ├── package.json           # Project dependencies and scripts
│   ├── tailwind.config.js     # Tailwind CSS configuration
│   ├── tsconfig.json          # TypeScript configuration
│   └── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm or yarn
- Firebase project (for authentication)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/leetcode-clone.git
    cd leetcode/leetcode
    ```

2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

3. Set up environment variables:
    - Create a `.env.local` file with your Firebase config.

### Running the App

```sh
npm run dev
# or
yarn dev
```

- The app will be available at [http://localhost:3000](http://localhost:3000).

## Technologies Used

- Next.js
- TypeScript
- Tailwind CSS
- Firebase (authentication)
- Recoil (state management)

## License

This project is licensed under the MIT License.

---

Feel free to contribute or open issues

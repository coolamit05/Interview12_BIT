# AI Mocker Interview

This project is an AI-powered interview mocker tool built using Next.js, PostgreSQL with Drizzle ORM, and Gemini AI. Authentication is handled by Clerk.

## Table of Contents
1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Features

- **Performance-Based Scoring**: Receive scores based on your interview performance to track your progress.
- **Personalized Feedback**: Get detailed feedback tailored to your responses to help you refine your interview techniques.
- **Correct Answers Guidance**: Access correct answers with explanations to improve your understanding and tackle challenging questions effectively.
- **Video and Audio Support**: Seamless video and audio integration for realistic interview simulations.
- **AI-Driven Insights**: Advanced AI provides comprehensive insights into your interview performance.

## Technologies Used

- **Next.js**: A React framework for building fast and user-friendly web applications.
- **PostgreSQL**: A powerful, open-source relational database system.
- **Drizzle ORM**: TypeScript ORM for SQL databases, focused on making database operations easy and intuitive.
- **Gemini AI**: Advanced AI system for generating feedback and scoring interviews.
- **Clerk**: Authentication service for handling user sign-ups and logins.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/ai-mocker-interview.git
    cd ai-mocker-interview
    ```

2. **Install dependencies:**
    ```sh
    npm install
    ```

3. **Set up environment variables:**
    Create a `.env.local` file in the root of your project and add the following environment variables:
    ```env
    DATABASE_URL=your_postgresql_database_url
    CLERK_API_KEY=your_clerk_api_key
    GEMINI_API_KEY=your_gemini_api_key
    ```

4. **Run database migrations:**
    ```sh
    npm run migrate
    ```

5. **Start the development server:**
    ```sh
    npm run dev
    ```

## Usage

1. **Sign Up / Log In**: Use Clerk for secure authentication.
2. **Take a Mock Interview**: Experience a realistic mock interview with video and audio support.
3. **Receive Scores and Feedback**: Get detailed performance scores and personalized feedback from Gemini AI.
4. **Review Correct Answers**: Learn from provided correct answers and explanations to improve your skills.

## Contributing

We welcome contributions to enhance the AI Mocker Interview tool! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
#   I n t e r v i e w B u d d y A I  
 
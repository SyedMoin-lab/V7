# Full Stack Job Portal with React JS, Tailwind CSS, Supabase, Clerk, Shadcn UI Tutorial 🔥🔥


Welcome a full stack job portal application designed to connect recruiters and candidates seamlessly. This app provides features for job posting, application tracking, and authentication using Google and custom email/password.

## Features

- **Authentication**: Sign in using Google or custom email/password.
- **Job Posting**: Recruiters can post job openings.
- **Job Application**: Candidates can apply for jobs.
- **Application Tracking**: Track the status of your job applications.

## Tech Stack

- **Frontend**: React.js, JavaScript, ViteJS, Tailwind CSS, Shadcn UI
- **Backend**: Supabase
- **Authentication**: Clerk

## Installation

### Prerequisites

- Node.js (v14 or higher)
- npm or Yarn

### Setup

1. **Clone the Repository**

   ```bash
   git clone(https://github.com/SyedMoin-lab/Full-Stack-React-JS-Project.git)
   ```

2. **Install Dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Create a `.env` File**

   Copy the `.env.example` file to `.env` and fill in your environment variables.

   ```bash
   cp .env.example .env
   ```

### API Keys

You will need to obtain API keys for various services. Here’s how you can get them:

- **Supabase**
  1. Go to [Supabase](https://supabase.io/).
  2. Create a new project and get your API URL and Key from the project settings.

- **Clerk**
  1. Visit [Clerk](https://clerk.dev/).
  2. Create a new application to obtain your API keys.

- **Google Authentication**
  1. Go to the [Google Developer Console](https://console.developers.google.com/).
  2. Create a new project and set up OAuth 2.0 credentials.

Update your `.env` file with the following variables:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_KEY=your_supabase_key
VITE_CLERK_FRONTEND_API=your_clerk_frontend_api
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

## Usage

1. **Run the Development Server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

2. Open [http://localhost:3000](http://localhost:3000) in your browser to access the app.

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact:

- [Syed Moinuddin](mailto:syedmoinuddin106@gmail.com.com)

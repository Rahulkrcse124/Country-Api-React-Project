
# Code Alchemist

**Code Alchemist** is an AI-powered Next.js application designed to automate the software development process. By integrating with Jira, it transforms natural language feature descriptions into fully functional code changes and unit tests. This tool aims to enhance developer productivity by reducing manual coding efforts and ensuring consistency across codebases.

---

## 🚀 Features

- **Jira Integration**: Input a Jira ticket ID to fetch and process its description.
- **AI-Driven Code Generation**: Leverages Large Language Models (LLMs) to generate code changes and corresponding unit tests based on the ticket description.
- **Interactive Code Diff Viewer**: Presents generated code diffs and tests with syntax highlighting for easy review.
- **Seamless Developer Experience**: Streamlines the transition from feature description to implementation, reducing development time.

---

## 🛠️ Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/)
- **Backend**: Node.js, Express.js
- **AI Integration**: OpenAI's GPT models (e.g., GPT-4)
- **Version Control**: Git, GitHub

---

## 📦 Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Rahulkrcse124/4.-LLM-Driven-Feature.git
   cd 4.-LLM-Driven-Feature
   ```

2. **Install Dependencies**

   Ensure you have [Node.js](https://nodejs.org/) installed. Then, install the required packages:

   ```bash
   npm install
   ```

3. **Configure Environment Variables**

   Create a `.env.local` file in the root directory and add your OpenAI API key:

   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. **Run the Development Server**

   ```bash
   npm run dev
   ```

   Navigate to `http://localhost:3000` in your browser to access the application.

---

## 🧪 Usage

1. **Enter Jira Ticket ID**: On the homepage, input the Jira ticket ID you wish to process.
2. **Generate Code**: Click on the "Generate" button to fetch the ticket description and initiate code generation.
3. **Review Output**: The application will display the generated code changes and unit tests in a diff viewer for your review.

---

## 📁 Project Structure

```
4.-LLM-Driven-Feature/
├── components/        # Reusable UI components
├── pages/             # Next.js pages
├── public/            # Static assets
├── styles/            # Global styles and Tailwind configurations
├── utils/             # Utility functions and helpers
├── .env.local         # Environment variables
├── package.json       # Project metadata and scripts
└── README.md          # Project documentation
```

---

## 🤝 Contributing

Contributions are welcome! If you'd like to enhance the functionality or fix issues:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request.

Please ensure your code adheres to the project's coding standards and includes relevant tests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

For questions or feedback, please reach out to [Rahul Kumar](mailto:rahulkrcse124@example.com).

---

Feel free to customize this README further to align with your project's specifics or to add more detailed instructions and features. 

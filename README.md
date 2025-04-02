# Claude Clone Frontend

A modern chat interface inspired by Anthropic's Claude, built with Next.js and React. This project provides a clean, responsive user interface for interacting with AI models.

## Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/) - React framework for production
- **Language**: [TypeScript](https://www.typescriptlang.org/) - For type safety and better developer experience
- **UI Components**: Custom CSS with responsive design and dark mode support
- **Markdown Rendering**: [react-markdown](https://github.com/remarkjs/react-markdown) - For rendering markdown responses
- **Syntax Highlighting**: [react-syntax-highlighter](https://github.com/react-syntax-highlighter/react-syntax-highlighter) - For code block highlighting

## Features

- 🌓 Dark/Light mode support
- 💬 Real-time chat interface
- 📱 Responsive design
- ✨ Clean, modern UI
- 🎨 Custom CSS animations
- 📝 Markdown support
- 🖥️ Code syntax highlighting

## Getting Started

### Prerequisites

- Node.js 18+ 
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd frontend
```

2. Install dependencies:
```bash
pnpm install
```

3. Create a `.env.local` file in the root directory:
```env
NEXT_PUBLIC_API_URL=your_backend_url
```

4. Run the development server:
```bash
pnpm dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production

```bash
pnpm build
pnpm start
```

## Project Structure

```
frontend/
├── src/
│   ├── app/              # Next.js app directory
│   │   ├── layout.tsx    # Root layout
│   │   ├── page.tsx      # Home page
│   │   └── globals.css   # Global styles
│   ├── components/       # React components
│   └── types/           # TypeScript type definitions
├── public/              # Static files
└── package.json        # Project dependencies and scripts
```

## Environment Variables

- `NEXT_PUBLIC_API_URL`: The URL of your backend API server

## Deployment

This project is configured for easy deployment on Vercel:

```bash
pnpm build
pnpx vercel --prod
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by Anthropic's Claude chat interface
- Built with modern web technologies
- Focuses on clean, maintainable code

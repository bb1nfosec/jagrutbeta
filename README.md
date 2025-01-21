# Jagrut - Security Testing Platform

A comprehensive security testing and analysis platform built with React, Supabase, and multiple AI providers.

## Features

- 🔒 Multiple AI providers support (OpenAI, Anthropic, Google Gemini, HuggingFace, Ollama)
- 🛡️ Security analysis and vulnerability scanning
- 📊 Interactive dashboard with security findings
- 🔍 Knowledge base search
- 👤 User authentication with Supabase
- ⚙️ Configurable settings for API keys and preferences

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Supabase
- Vite
- Lucide Icons

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/jagrut.git
cd jagrut
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with your API keys:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Start the development server:
```bash
npm run dev
```

5. Build for production:
```bash
npm run build
```

## Setting Up AI Providers

1. Open the settings panel (gear icon)
2. Add your API keys for:
   - OpenAI
   - Anthropic
   - Google Gemini
   - HuggingFace

For local Ollama support:
1. Install Ollama on your machine
2. Configure the endpoint (default: http://localhost:11434)
3. Select your preferred model

## Database Setup

1. Create a new Supabase project
2. Run the migration files in the `supabase/migrations` directory
3. Update your environment variables with the new Supabase credentials

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
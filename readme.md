# Chrome Built-in AI Chat

A lightweight chat application built using Chrome's Built-in AI APIs.

This project demonstrates how to use the LanguageModel API directly in the browser without requiring external AI providers, API keys, backend servers, or cloud inference.

# Check live 👇
## https://chrome-nano-chat-bot.netlify.app

## Features

- Chrome Built-in AI (LanguageModel API)
- Persistent chat history using Local Storage
- Fixed bottom chat input
- Scrollable chat area
- AI typing indicator animation
- Blur and fade-in message animations
- Auto-scroll to latest messages
- Enter key support
- Responsive layout
- Single AI session initialization
- Error handling for unsupported browsers

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Chrome Built-in AI APIs

## How It Works

1. The application initializes a LanguageModel session when the page loads.
2. User messages are sent directly to Chrome's local AI model.
3. Responses are generated on-device.
4. Conversations are stored in Local Storage for persistence.
5. Previous chats are automatically restored when the page is reopened.

## Requirements

- Google Chrome with Built-in AI support enabled
- A supported device capable of running Gemini Nano locally

## Running Locally

Clone the repository:

```bash
git clone https://github.com/your-username/chrome-builtin-ai-chat.git
```

Navigate into the project:

```bash
cd chrome-builtin-ai-chat
```

Open the HTML file in Chrome:

```bash
index.html
```

Or use a local development server:

```bash
npx serve .
```

## Project Structure

```text
.
├── index.html
└── README.md
```

## Browser Support

This project currently works only in Chromium-based browsers that support the LanguageModel API.

## Future Improvements

- Streaming responses
- Multiple chat conversations
- Chat export functionality
- Dark mode
- Message timestamps
- Markdown rendering
- Voice input
- File attachments
- IndexedDB storage
- PWA support

## Why This Project?

Most AI applications rely on cloud providers and API keys.

This project explores a different approach by leveraging Chrome's on-device AI capabilities, enabling:

- Lower latency
- Improved privacy
- No API costs
- Offline-capable AI experiences

## License

MIT License

## Author

Ayush

Built with Chrome Built-in AI APIs.

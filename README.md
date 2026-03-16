# Bible Study Application

A comprehensive Bible study application with full Bible text, dictionary, concordance, theological commentary, exegesis, and advanced study tools for personal research.

## Features

### Core Features
- **Complete Bible**: All 66 books (Genesis to Revelation)
- **Multiple Translations**: Support for multiple Bible versions
- **Full Text Search**: Fast verse and word search across entire Bible

### Study Tools
- **Dictionary**: Biblical terms and definitions
- **Concordance**: Complete word index with verse references
- **Theological Commentary**: Detailed commentary on books and passages
- **Exegesis**: In-depth verse analysis and interpretation
- **Cross-References**: Related verses and passages
- **Bookmarks & Highlights**: Personal study notes
- **Reading Plans**: Structured study guides

## Project Structure

```
bible-app/
├── frontend/              # React UI application
│   ├── src/
│   │   ├── components/   # Reusable React components
│   │   ├── pages/        # Main application pages
│   │   ├── styles/       # CSS and styling
│   │   └── App.jsx
│   └── package.json
├── backend/              # Express.js API server
│   ├── routes/          # API endpoints
│   ├── controllers/      # Business logic
│   ├── database/         # Database configuration
│   ├── data/            # Bible data and resources
│   └── server.js
├── database/             # SQLite database files
└── docs/                # Documentation
```

## Technology Stack

- **Frontend**: React 18, Vite, Axios
- **Backend**: Node.js, Express.js
- **Database**: SQLite
- **Language**: JavaScript/JSX

## Installation

### Prerequisites
- Node.js (v16+)
- npm or yarn

### Setup

1. Clone the repository
```bash
git clone https://github.com/jontallo8-ui/bible-app-.git
cd bible-app-
```

2. Install dependencies
```bash
npm install
cd frontend && npm install
cd ../backend && npm install
```

3. Create environment variables
```bash
cp .env.example .env
```

4. Initialize database
```bash
npm run db:init
```

5. Start development servers
```bash
npm run dev
```

## Usage

- Open browser to `http://localhost:5173` for frontend
- API runs on `http://localhost:3001`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see LICENSE file for details

## Roadmap

- [ ] Desktop version (Electron)
- [ ] Mobile app (React Native)
- [ ] Offline support
- [ ] Multi-language support
- [ ] Community annotations
- [ ] Advanced filtering and search

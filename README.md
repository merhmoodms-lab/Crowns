# Crowns
Consistency 
# Legal Q&A Platform

A high-converting platform for answering legal questions using the IRAC method and discovering relevant case law.

## Features

✅ **Ask Legal Questions** - Get community answers formatted using IRAC method
✅ **Case Research** - Search and explore case law across jurisdictions  
✅ **AI-Powered IRAC** - Automatic structuring of legal analysis
✅ **Verified Lawyers** - Professional legal guidance from verified experts
✅ **Bookmarks & Search History** - Save and organize research
✅ **Practice Area Filters** - Narrow search by legal specialty
✅ **Citation Management** - Proper legal citations included

## Tech Stack

**Backend**: Node.js, Express, PostgreSQL, Redis, OpenAI API
**Frontend**: Next.js, React, Chakra UI
**Infrastructure**: Docker, AWS/GCP

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL 15+
- Redis 7+
- Docker & Docker Compose

### Installation

1. Clone repository:
```bash
git clone https://github.com/merhmoodms-lab/legal-qa-platform.git
cd legal-qa-platform
```

2. Setup environment:
```bash
cp .env.example .env
# Edit .env with your credentials
```

3. Start with Docker:
```bash
docker-compose up -d
```

4. Run migrations:
```bash
npm run migrate
```

5. Start development:
```bash
npm run dev
```

Visit `http://localhost:3000`

## API Documentation

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user

### Questions
- `GET /api/questions` - List questions
- `POST /api/questions` - Create question
- `GET /api/questions/:id` - Get question detail
- `GET /api/questions/search?q=...` - Search questions

### Answers
- `POST /api/answers` - Create IRAC answer
- `GET /api/answers/question/:id` - Get answers for question

### Cases
- `GET /api/cases/:id` - Get case detail
- `GET /api/cases/search?q=...` - Search cases

## Monetization

- **Free Tier**: 3 questions/month, limited search
- **Pro**: $9.99/mo - Unlimited questions, advanced search
- **Premium**: $19.99/mo - + Lawyer consultations
- **Enterprise**: Custom pricing

## Project Status

🚀 **Current Phase**: MVP Development

## Contributing

Contributions welcome! See CONTRIBUTING.md

## License

MIT License - See LICENSE file

## Contact

Email: support@legalqa.com

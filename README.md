# Project Coco

A Python-based application for repository analysis and management with GitHub integration and LLM capabilities.

## Features

- GitHub repository analysis and management
- AI-powered insights using LLM integration
- REST API endpoints for programmatic access
- Modular architecture for easy extension

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/coco.git
cd coco
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment variables (see Configuration section)

## Usage

Run the application:
```bash
python run.py
```

The API will be available at `http://localhost:5000`

### Example API Calls

```bash
# Get repository analysis
curl -X GET http://localhost:5000/api/repositories/analysis?repo=username/reponame
```

## Configuration

Create a `.env` file with these variables:

```ini
GITHUB_TOKEN=your_github_personal_access_token
OPENAI_API_KEY=your_openai_api_key
```

## Project Structure

```
app/
├── api/              # API routes and endpoints
├── models/           # Data models and schemas
├── services/         # Business logic and services
└── utils/            # Utility functions and helpers
```

## License

MIT License - see [LICENSE](LICENSE) for details.

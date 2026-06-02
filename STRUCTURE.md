# Project Structure Documentation

## Directory Organization

### Root Level Files
- `README.md` - Project overview and getting started guide
- `.gitignore` - Git ignore rules
- `STRUCTURE.md` - This file - project structure documentation
- `package.json` - (if Node.js) Dependencies and scripts
- `requirements.txt` - (if Python) Package dependencies

### `.agents/` Directory
Agent workflows and skills for automated processes

```
.agents/
├── workflows/
│   └── fbs-to-agy-export.md          # Export workflow documentation
├── skills/
│   └── fbs-to-agy-export/
│       ├── SKILL.md                  # Skill definition and usage
│       └── reference/                # Reference materials
└── README.md                         # Agents documentation
```

### `/src` Directory (To be created)
Main source code files

```
src/
├── controllers/        # Request handlers
├── models/            # Data models
├── services/          # Business logic
├── utils/             # Utility functions
├── middleware/        # Express/framework middleware
├── config/            # Configuration files
└── index.js           # Entry point
```

### `/tests` Directory (To be created)
Test suites and test data

```
tests/
├── unit/              # Unit tests
├── integration/       # Integration tests
├── e2e/              # End-to-end tests
└── fixtures/         # Test data
```

### `/docs` Directory (To be created)
Project documentation

```
docs/
├── API.md            # API documentation
├── ARCHITECTURE.md   # System architecture
├── CONTRIBUTING.md   # Contribution guidelines
└── DEPLOYMENT.md     # Deployment instructions
```

### `/config` Directory (To be created)
Configuration files

```
config/
├── database.js       # Database configuration
├── environment.js    # Environment setup
└── constants.js      # Application constants
```

## File Extraction Status

| File/Directory | Status | Notes |
|---|---|---|
| README.md | ✅ Created | Basic overview added |
| .gitignore | ✅ Created | Comprehensive ignore rules |
| STRUCTURE.md | ✅ Created | This file |
| .agents/workflows/ | 📋 From zip | To be extracted |
| .agents/skills/ | 📋 From zip | To be extracted |
| src/ | 📋 From zip | To be extracted |
| tests/ | 📋 From zip | To be extracted |
| docs/ | 📋 From zip | To be extracted |
| package.json | 📋 From zip | To be extracted if exists |
| config/ | 📋 From zip | To be extracted |

## Next Steps

1. **Extract project.zip contents** - Unzip and identify all files
2. **Create directory structure** - Organize files into proper folders
3. **Commit by type** - Group commits by file type:
   - Configuration files
   - Source code
   - Tests
   - Documentation
4. **Add missing files** - Create package.json, .env.example, etc.
5. **Setup CI/CD** - Add GitHub Actions workflows
6. **Create branch protection** - Protect main branch

## Technology Stack (TBD)

Need to confirm based on project.zip contents:
- **Runtime**: Node.js / Python / Java / Go
- **Framework**: Express / Django / Spring / FastAPI
- **Database**: MongoDB / PostgreSQL / MySQL
- **Frontend**: React / Vue / Angular (if included)
- **Testing**: Jest / Pytest / JUnit
- **Build Tool**: Webpack / Maven / Gradle

## Contributing Guidelines

See `/docs/CONTRIBUTING.md` (to be created)

## License

To be determined

---

**Last Updated**: 2026-06-02
**Current Commits**: 2 (README + .gitignore + this file)

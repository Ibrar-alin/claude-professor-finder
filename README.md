# Professor Finder - Claude Skill

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Ibrar-alin/claude-professor-finder)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-purple.svg)](https://claude.ai)

A powerful Claude skill that helps students identify professors for research opportunities by extracting publicly available faculty information from university websites, faculty profiles, and Google Scholar.

## ✨ Features

- 🔍 **Smart Search** - Find professors by research area, university, and country
- 📧 **Email Extraction** - Pulls publicly available contact information
- 📄 **Recent Papers** - Identifies matching recent publications
- 📊 **Clean Output** - Returns data in Excel (.xlsx) or markdown table format
- 🎯 **Priority Ordering** - Prefers official university sources over third-party sites
- 🌍 **Global Coverage** - Works with universities worldwide

## 🚀 Quick Start

### Installation

1. **Download** the `SKILL.md` file from this repository
2. **Upload** to Claude.ai or paste the content into your conversation
3. **Activate** by saying: *"Use the Professor Finder skill"*

### Usage Example

Provide your search query in this format:
Find 5 emails of professors at MIT in the USA working in the field of quantum computing.
or
Research Area: quantum computing
Number of Professors: 5
University: MIT
Country: USA


### Sample Output

| Professor Name | University | Department | Research Area | Email | Profile Link | Country | Recent Research Paper |
|----------------|------------|------------|---------------|-------|--------------|---------|----------------------|
| Dr. John Smith | MIT | EECS | Quantum Computing | smith@mit.edu | https://eecs.mit.edu/smith | USA | "Quantum Error Correction" (2024) |

## 📋 Input Parameters

| Parameter | Required | Description |
|-----------|----------|-------------|
| Research Area | ✅ Yes | The academic field or topic of interest |
| Number of Professors | ✅ Yes | How many professors to return (default: 5) |
| University | ❌ No | Specific university to search within |
| Country | ❌ No | Country to filter results |

## 🔧 How It Works

1. **Parses** your search criteria
2. **Searches** official university sources in priority order:
   - University faculty pages
   - Department websites
   - Research group pages
   - Google Scholar profiles
3. **Extracts** publicly available information
4. **Formats** results into a clean table or Excel file

## 📁 Repository Structure
claude-professor-finder/
├── SKILL.md # Main skill file
├── README.md # Documentation
├── CHANGELOG.md # Version history
├── LICENSE # MIT License
├── examples/ # Example queries and outputs
│ ├── machine-learning.md
│ ├── quantum-computing.md
│ └── bioinformatics.md
└── versions/ # Archived versions
└── v1.0.0/
└── SKILL.md


## 🛠️ Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | 2026-03-26 | Initial release |

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

### Development Guidelines

- Maintain backward compatibility when possible
- Update version numbers following SemVer
- Document all changes in CHANGELOG.md
- Test with multiple universities and research areas

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋‍♀️ Support

- **Issues**: Report bugs via [GitHub Issues](https://github.com/yourusername/claude-professor-finder/issues)
- **Questions**: Open a discussion thread
- **Feature Requests**: Submit via issues with the `enhancement` tag

## 🌟 Acknowledgments

- Built for [Claude.ai](https://claude.ai) by Anthropic
- Inspired by students seeking research opportunities

---

**Made with ❤️ for the academic community**

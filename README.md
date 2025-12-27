# 🐍 Python Utility Tools

<div align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" />
  <img alt="License" src="https://img.shields.io/badge/License-MIT-green" />
  <img alt="Status" src="https://img.shields.io/badge/Status-Active-brightgreen" />
</div>

---

## 📋 Overview

A comprehensive collection of Python utility tools designed to enhance productivity and simplify common programming tasks. This repository provides ready-to-use modules for file handling, data processing, system automation, and more.

## ✨ Features

- 📁 **File Management**: Utilities for file operations, batch processing, and directory management
- 🔄 **Data Processing**: Tools for data transformation, cleaning, and analysis
- 🤖 **System Automation**: Scripts for system tasks and scheduled operations
- 🔐 **Security Utilities**: Password generation, encryption, and validation tools
- 📊 **Data Visualization**: Helper functions for creating charts and graphs
- 🧹 **Code Utilities**: Formatters, linters, and code analysis tools
- 📝 **Logging & Monitoring**: Advanced logging and performance monitoring
- ⚡ **Performance Optimized**: Efficient implementations using best practices

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/Im044/python-utility-tools.git
cd python-utility-tools

# Install dependencies
pip install -r requirements.txt
```

### Basic Usage

```python
from utils import FileManager, DataProcessor

# File operations
fm = FileManager()
files = fm.get_files_by_extension('src/', '.py')

# Data processing
dp = DataProcessor()
data = dp.load_csv('data.csv')
cleaned_data = dp.clean_data(data)
```

## 📦 Module Structure

```
python-utility-tools/
├── utils/
│   ├── file_manager.py          # File operations
│   ├── data_processor.py        # Data handling
│   ├── system_tools.py          # System automation
│   ├── security.py              # Security utilities
│   ├── visualization.py         # Plotting & charts
│   └── __init__.py
├── examples/                    # Usage examples
├── tests/                       # Unit tests
├── requirements.txt             # Dependencies
├── README.md                    # Documentation
└── LICENSE                      # MIT License
```

## 📚 Modules

### File Manager
Handle file operations efficiently:
- Create, read, write, delete files
- Batch file processing
- Directory traversal and filtering
- File compression and archiving

### Data Processor
Process and analyze data:
- CSV/JSON/Excel file handling
- Data cleaning and validation
- Filtering and transformation
- Statistical analysis

### System Tools
Automate system tasks:
- Process management
- Network utilities
- System monitoring
- Scheduled tasks

### Security
Security-related utilities:
- Password generation
- Data encryption/decryption
- Hash functions
- Input validation

## 🔧 Configuration

Create a `config.yml` file in the root directory:

```yaml
logging:
  level: INFO
  format: '%(asctime)s - %(levelname)s - %(message)s'

data_processing:
  chunk_size: 1000
  encoding: 'utf-8'
```

## 📖 Documentation

Detailed documentation for each module is available in the `docs/` directory:

- [File Manager Guide](docs/file_manager.md)
- [Data Processor Guide](docs/data_processor.md)
- [System Tools Guide](docs/system_tools.md)
- [API Reference](docs/api_reference.md)

## 🧪 Testing

Run the test suite:

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov=utils

# Run specific test file
pytest tests/test_file_manager.py
```

## 📊 Performance

Benchmarks for common operations:

| Operation | Time | Memory |
|-----------|------|--------|
| Read 10K lines | 0.5s | 5MB |
| Process CSV | 1.2s | 8MB |
| Batch compress | 2.1s | 12MB |

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Mohd Muffasil**
- GitHub: [@Im044](https://github.com/Im044)
- Email: [mdmuffasil893@gmail.com](mailto:mdmuffasil893@gmail.com)
- LinkedIn: [mohd-muffasil](https://linkedin.com/in/mohd-muffasil-661191209/)

## 🙏 Acknowledgments

- Thanks to the Python community for inspiration
- Contributors and users for feedback

## 💬 Support

For support, open an issue or contact the author directly.

---

<div align="center">
  <strong>⭐ Star this repository if you find it helpful!</strong>
</div>

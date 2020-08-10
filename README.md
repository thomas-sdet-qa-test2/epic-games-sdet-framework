## Epic Games SDET Testing Framework  

This repository provides a structured framework for automated testing in video games, specifically tailored for Epic Games environments. The framework integrates end-to-end testing capabilities for UI, API, and performance validation.  

### Features  
- Automated UI testing with Selenium WebDriver  
- API testing using REST Assured  
- Performance benchmarking and load testing  
- Modular test structure for easy expansion  
- CI/CD pipeline integration for automated execution  

### Technologies Used  
- Python  
- Selenium WebDriver  
- pytest  
- REST Assured  
- Docker & Jenkins  

### Project Structure  
```
epic-games-sdet-framework/
│── tests/              # Test scripts for UI, API, and performance
│── configs/            # Configuration files for different test environments
│── logs/               # Execution logs and test reports
│── requirements.txt    # Python dependencies
│── README.md           # Project documentation
```

### Installation & Setup  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/thomas-sdet-qa-test2/epic-games-sdet-framework.git  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run tests:  
   ```bash  
   pytest tests/  
   ```  

### CI/CD Integration  
The framework is designed for seamless integration into CI/CD pipelines using Jenkins and GitHub Actions. The test suite can be triggered automatically based on build deployments, ensuring continuous validation.  

### Contributing  
Contributions are welcome. Please submit a pull request with detailed descriptions of changes.

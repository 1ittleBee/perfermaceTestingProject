# Performance Testing Project

## Project Overview
This project focuses on performance testing using Apache JMeter to evaluate the robustness, scalability, and efficiency of web applications. It includes load testing scenarios and test scripts designed to identify bottlenecks and ensure optimal performance under varying conditions.

## Features
- **Load Testing**: Simulate concurrent users and measure system performance.
- **Stress Testing**: Evaluate system behavior under extreme load.
- **API Performance Testing**: Test API responsiveness and throughput.
- **Reporting**: Generate detailed performance analysis reports.

## Tools and Technologies Used
- **Apache JMeter**: For load and stress testing.

## Project Structure
```
ProjectRoot
├── JMeter
│   ├── TestPlans
│   ├── Reports
│   └── Scripts
└── Documentation
    └── README.md
```

## Getting Started

### Prerequisites
Ensure you have the following installed on your system:
- [Apache JMeter](https://jmeter.apache.org/)

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/1ittleBee/PerformanceTestingProject.git
   cd PerformanceTestingProject
   ```
2. Navigate to the `JMeter` folder.
3. Ensure the `restful-bookerPerformanceTesting_100.jmx` file is in the `TestPlans` directory.

## How to Run Tests

### Using JMeter
1. Run the test plan in non-GUI mode:
   ```bash
   jmeter -n -t JMeter/TestPlans/restful-bookerPerformanceTesting_100.jmx -l JMeter/Reports/restful-bookerPerformanceTesting_100.jtl
   ```
2. Generate the HTML report:
   ```bash
   jmeter -g JMeter/Reports/restful-bookerPerformanceTesting_100.jtl -o JMeter/Reports/restful-bookerPerformanceTesting_100.html
   ```
3. Open the generated HTML report in a web browser to view the test results.

## Results and Reporting
- Test reports are available in the `JMeter/Reports` folder.
- Use the generated HTML report for detailed performance analysis.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork this repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push them to your forked repository.
4. Submit a pull request for review.

## License
This project is licensed under the [MIT License](LICENSE).

---
For any issues or inquiries, please contact [Khaled Hasan](mailto:hasankhaled226@gmail.com).

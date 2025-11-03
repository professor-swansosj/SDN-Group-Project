# SDN Network Automation Group Project

Florida State College at Jacksonville - Software Defined Networking Course

**Project Value:** 100 Points  
**Group Size:** 2-4 Students  
**Due Date:** [Insert Date Here]

## :triangular_flag_on_post: Learning Goals

- Demonstrate proficiency in network automation using industry-standard protocols (RESTCONF, NETCONF, or Netmiko)
- Integrate AI services to enhance network automation capabilities
- Apply object-oriented programming principles in a network automation context
- Create production-quality Python code with proper documentation and structure
- Collaborate effectively in a team environment to deliver a complete solution

## :globe_with_meridians: Overview

This capstone group project challenges you to synthesize everything you've learned about network automation throughout this course. You will create an original Python application that combines network device interaction with artificial intelligence to solve a real-world networking problem.

Your solution must demonstrate mastery of network automation protocols while leveraging AI services to add intelligent functionality. This project represents the culmination of your learning and should showcase industry-standard development practices.

### Core Requirements

**Network Automation Component:**

- Interact with network devices using one or more of the following:
  - **RESTCONF** - RESTful API for network configuration and monitoring
  - **NETCONF** - Network Configuration Protocol for device management
  - **Netmiko** - Multi-vendor library for SSH-based device interaction

**AI Integration Component:**

- Incorporate AI services such as:
  - OpenAI ChatGPT/GPT-4
  - Google AI (Gemini/Bard)
  - Azure OpenAI
  - Anthropic Claude
  - Or other approved AI services

**Technical Requirements:**

- Object-oriented Python design with classes and methods
- Proper error handling and logging
- Configuration management
- Code documentation and comments
- Professional README and setup instructions

### Project Ideas (Choose One or Create Your Own)

1. **Intelligent Network Troubleshooter**: Create a tool that gathers network device information and uses AI to analyze symptoms and suggest solutions
2. **Configuration Assistant**: Build an AI-powered system that helps generate and validate network configurations based on natural language requirements
3. **Network Health Monitor**: Develop a monitoring system that uses AI to interpret network metrics and predict potential issues
4. **Automated Documentation Generator**: Create a system that discovers network topologies and uses AI to generate comprehensive network documentation
5. **Security Analyzer**: Build a tool that collects security-related information from devices and uses AI to assess vulnerabilities

---

## :card_file_box: Required File Structure

Your project repository must include:

```text
project-root/
├── README.md                    # Project documentation
├── main.py                     # Application entry point
├── requirements.txt             # Python dependencies
├── config/
│   ├── __init__.py
│   ├── settings.py             # Configuration management
│   └── device_inventory.yaml   # Network device information
├── src/
│   ├── __init__.py
│   ├── network/
│   │   ├── __init__.py
│   │   ├── device_manager.py   # Network device interaction
│   │   └── protocols.py        # Protocol-specific implementations
│   ├── ai/
│   │   ├── __init__.py
│   │   ├── ai_client.py        # AI service integration
│   │   └── prompts.py          # AI prompt management
│   └── utils/
│       ├── __init__.py
│       ├── logger.py           # Logging configuration
│       └── helpers.py          # Utility functions
├── tests/
│   ├── __init__.py
│   └── test_main.py           # Unit tests
├── docs/
│   ├── setup.md               # Installation guide
│   ├── usage.md               # User manual
│   └── architecture.md        # System design documentation
└── .env.example               # Environment variables template
```

---

## :memo: Detailed Instructions

### Phase 1: Planning and Design (Week 1)

1. **Form your group** and select a project concept
2. **Research and document** your chosen network automation protocol
3. **Select your AI service** and obtain necessary API credentials
4. **Create a project plan** with timeline and task distribution
5. **Set up your development environment** and version control

### Phase 2: Core Development (Weeks 2-3)

1. **Implement network device connectivity** using your chosen protocol
2. **Develop core classes and methods** following OOP principles
3. **Integrate AI service** with proper API handling
4. **Create basic functionality** connecting network data with AI processing
5. **Implement error handling** and logging throughout your application

### Phase 3: Enhancement and Documentation (Week 4)

1. **Refine and optimize** your code implementation
2. **Add comprehensive documentation** including Docstrings and comments
3. **Create user documentation** with setup and usage instructions
4. **Implement unit tests** for critical functionality
5. **Prepare demonstration** of your working solution

### Technical Specifications

**Network Protocols:**

- Demonstrate proper authentication and connection handling
- Implement appropriate error handling for network failures
- Show understanding of protocol-specific features and limitations

**AI Integration:**

- Secure API key management (never commit keys to version control)
- Proper API request/response handling
- Rate limiting and error handling for AI service calls
- Meaningful integration that adds value to the network automation task

**Code Quality:**

- Follow PEP 8 Python style guidelines
- Use descriptive variable and function names
- Implement appropriate design patterns
- Include comprehensive error handling

## :page_facing_up: Documentation and Logging

Your project must include:

- **README.md**: Clear project description, setup instructions, and usage examples
- **Code Comments**: Inline comments explaining complex logic and decisions
- **Docstrings**: Function and class documentation following Python conventions
- **User Documentation**: Step-by-step guides for installation and operation
- **Logging**: Appropriate logging levels (DEBUG, INFO, WARNING, ERROR) throughout the application

## :green_checkmark: Grading Rubric (100 Points Total)

### Exceptional (95-100 points) - Industry Standard Excellence

- **Network Automation (25 pts)**: Sophisticated implementation with advanced features, excellent error handling, and optimal protocol usage
- **AI Integration (25 pts)**: Creative and meaningful AI integration that significantly enhances functionality with robust error handling
- **Code Quality (25 pts)**: Professional-grade code with excellent OOP design, comprehensive error handling, and optimal performance
- **Documentation (25 pts)**: Comprehensive, professional documentation including detailed setup guides, API documentation, and architectural diagrams

### Proficient (85-94 points) - High Professional Standard

- **Network Automation (22 pts)**: Solid implementation with good error handling and proper protocol usage
- **AI Integration (22 pts)**: Well-integrated AI functionality that adds clear value to the solution
- **Code Quality (22 pts)**: Clean, well-structured code with good OOP principles and adequate error handling
- **Documentation (19 pts)**: Complete documentation with clear setup instructions, usage guides, and code comments

### Developing (75-84 points) - Good Foundation

- **Network Automation (20 pts)**: Working network connectivity with basic functionality and some error handling
- **AI Integration (20 pts)**: Functional AI integration that works but may be basic in implementation
- **Code Quality (20 pts)**: Functional code with classes and methods, adequate structure
- **Documentation (15 pts)**: Basic documentation covering essential setup and usage

### Beginning (50-74 points) - Basic Implementation

- **Network Automation (15 pts)**: Basic network connectivity with minimal functionality
- **AI Integration (15 pts)**: Simple AI integration with limited functionality
- **Code Quality (15 pts)**: Code works with some object-oriented elements but lacks sophistication
- **Documentation (5 pts)**: Minimal documentation, basic README

### Needs Improvement (10-49 points) - Incomplete Attempt

- **Network Automation (5 pts)**: Attempted network functionality but non-functional or severely limited
- **AI Integration (3 pts)**: Attempted AI integration with limited success
- **Code Quality (2 pts)**: Code structure present but significant functionality missing
- **Documentation (0 pts)**: Little to no documentation

### No Submission (0 points)

- No project submitted or completely non-functional code

---

## :warning: Important Notes

- **Academic Integrity**: While you may reference online resources and documentation, your implementation must be original work
- **API Credentials**: Never commit API keys or credentials to your repository. Use environment variables and provide a `.env.example` file
- **Testing**: Test your solution thoroughly with actual network devices (use simulators if physical devices unavailable)
- **Collaboration**: All group members must contribute meaningfully to the project. Include a contribution breakdown in your documentation
- **Presentation**: Be prepared to demonstrate your working solution and explain your design decisions

## :rocket: Getting Started

1. Clone this repository to your development environment
2. Review the `requirements.txt` file and install dependencies
3. Examine the project structure and begin planning your implementation
4. Set up your development environment with necessary tools and credentials
5. Begin with a simple proof-of-concept connecting to a network device
6. Incrementally add AI functionality and enhance your solution

**Good luck, and create something amazing!** 🚀

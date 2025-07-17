Basic Operations
Number Input: Click digit buttons (0-9) to enter values

Decimal Point: Use . button for floating-point numbers

Operations: Select desired operation (+, -, ×, ÷)

Calculate: Press = or Enter to display result

Clear:

C: Clear current input

AC: Reset all values and memory

Advanced Functions
plaintext
Example: Calculate (5² + √16) × 25%

Steps:
1. 5 → x² → = (25)
2. √ → 16 → = (4)
3. + → = (29)
4. × → 25 → % → = (7.25)
Keyboard Shortcuts
Key	Function	Key	Function
0-9	Digits 0-9	.	Decimal
+	Addition	-	Subtraction
*	Multiplication	/	Division
%	Percentage	^	Power
r	Square root	Enter	Calculate
c	Clear	a	All Clear
m	Memory store	s	Sign change
Technical Architecture
File Structure
markdown
calculator/
├── index.html          # Main application structure
├── styles/
│   ├── main.css        # Core styling
│   ├── themes.css      # Light/dark mode
│   └── responsive.css  # Media queries
├── scripts/
│   ├── calculator.js   # Core logic
│   ├── history.js      # Calculation history
│   └── keyboard.js     # Keyboard support
├── assets/             # Images/icons
└── tests/              # Unit tests
    └── calculator.test.js
Technology Stack
Frontend: HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+)

Architecture: MVC pattern

Dependencies: None (vanilla JS)

Testing: Jest framework

Development Setup
Environment Configuration
Install Node.js (v16+ recommended)

Install dependencies:

bash
npm install
Development Workflow
bash
# Start live development server
npm run dev

# Run unit tests
npm test

# Build production version
npm run build
Testing Procedures
Comprehensive test coverage including:

Arithmetic operation validation

Edge case handling (division by zero, max digits)

Memory function tests

UI responsiveness checks

Cross-browser compatibility

Deployment Options
Static Hosting
Deploy to any static hosting service:

GitHub Pages

Netlify

Vercel

Firebase Hosting

Netlify Deployment
https://www.netlify.com/img/deploy/button.svg

Roadmap
Upcoming Features
Scientific calculator mode

Unit conversion

Currency converter

Graphing capabilities

Equation solver

Programmer mode (binary/hex operations)

Voice command support

Version History
v1.0 (Current): Basic operations with memory functions

v1.1 (Q3 2025): History export and themes

v2.0 (Q4 2025): Scientific mode implementation

Contributing
We welcome contributions! Please follow these steps:

Fork the repository

Create a feature branch (git checkout -b feature/your-feature)

Commit changes with descriptive messages

Push to your branch (git push origin feature/your-feature)

Open a pull request

Contribution Guidelines
Follow existing code style

Include unit tests for new features

Update documentation accordingly

Use conventional commit messages

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Maintainer: Your Name (@chelsea-lexa)
Support: calculator-support@example.com
Issue Tracker: https://github.com/chelsea-lexa/calculator/


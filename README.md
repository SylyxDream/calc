# 🔢 Modern Calculator with History

A sleek, responsive calculator built with vanilla JavaScript, featuring a calculation history and modern UI design. This calculator allows you to perform basic arithmetic operations and continue calculations with previous results seamlessly.

## ✨ Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, division, and percentage calculations
- **Chain Calculations**: Continue calculating with the result of the previous operation
- **Calculation History**: View and reuse past calculations
- **Keyboard Support**: Full keyboard and mouse support for enhanced usability
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Dark Mode**: Automatic dark mode support based on system preferences
- **Error Handling**: Robust error handling with user-friendly error messages
- **Accessible**: Built with accessibility in mind, including ARIA labels and keyboard navigation

## 🚀 Quick Start

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/modern-calculator.git
```

2. Navigate to the project directory:
```bash
cd modern-calculator
```

3. Open `index.html` in your preferred browser or serve it using a local server.

### Usage

**Basic Operations:**
- Click numbers and operators or use your keyboard
- Press `=` or `Enter` to calculate
- Use `C` or `Escape` to clear the display
- Press `Backspace` to delete the last character

**Chain Calculations:**
1. Calculate: `10 + 10 = 20`
2. Continue: `+ 10 = 30` (automatically uses 20)
3. Continue: `× 2 = 60` (automatically uses 30)

**History:**
- Click on any history entry to use its result
- Clear history with the trash icon
- Use `Ctrl + H` to clear history via keyboard

## 📁 Project Structure

```
modern-calculator/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
└── README.md          # Project documentation
```

## 🎯 Key Features Explained

### 1. Chain Calculations
The calculator remembers your last result and allows you to continue calculations without needing to re-enter values:

```javascript
// Example flow:
// 10 + 10 = 20
// + 10 = 30 (uses 20 automatically)
// × 2 = 60 (uses 30 automatically)
```

### 2. Calculation History
- Automatically stores up to 50 calculations
- Displays timestamps for each calculation
- Click to reuse results in new calculations
- Scrollable list for easy browsing

### 3. Enhanced Error Handling
```javascript
// Features built-in validation for:
- Division by zero protection
- Invalid mathematical expressions
- Input validation (multiple operators, decimal points)
- Graceful error recovery
```

### 4. Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `0-9` | Number input |
| `+`, `-`, `*`, `/` | Operations |
| `.` | Decimal point |
| `Enter` or `=` | Calculate |
| `Escape` or `C` | Clear |
| `Backspace` | Delete last character |
| `Ctrl + H` | Clear history |

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with Flexbox/Grid, animations, and transitions
- **Vanilla JavaScript**: No frameworks, pure JavaScript for all functionality
- **Responsive Design**: Works on all devices with media queries
- **ARIA**: Accessibility attributes for screen readers

## 🎨 Design Features

- **Modern UI**: Clean interface with subtle animations
- **Color Scheme**: Carefully chosen colors for readability
- **Hover Effects**: Interactive button feedback
- **Smooth Transitions**: Elegant animations for better UX
- **Custom Scrollbar**: Styled scrollbars for consistent look
- **Dark Mode**: Automatic theme switching

## 🔄 Version History

- **1.0.0** - Initial release
  - Basic calculator functionality
  - Responsive design
  - Calculation history
  - Chain calculations
  - Full keyboard support

## 🙏 Acknowledgments

- Inspired by modern calculator designs
- Built with accessibility in mind
- Community feedback and contributions

---

Made with ❤️ by [Sylyx]
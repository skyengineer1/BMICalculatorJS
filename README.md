# ⚖️ BMI Calculator

## 📌 About
This JavaScript script calculates the Body Mass Index (BMI) for two individuals and determines if Mark is taller than John.

## 📝 Code
```javascript
const massMark = 95;
const heightMark = 1.88;
const massJohn = 85;
const heightJohn = 1.76;

const BMIMark = massMark / (heightMark * heightMark);
const BMIJohn = massJohn / (heightJohn * heightJohn);

console.log(BMIMark);
console.log(BMIJohn);

const markHigherBMI = heightMark > heightJohn;
console.log(markHigherBMI);
```

## 📂 Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repo-name
   ```
3. Run the script in the browser console or using Node.js:
   ```sh
   node script.js
   ```

## 🔥 Output Example
```
26.87  // Mark's BMI
27.44  // John's BMI
true    // Mark is taller than John
```

## 💡 Features
- Calculates BMI using the standard formula: `BMI = mass / height²`
- Compares two BMIs
- Checks which person is taller
- Uses `const` for variable declarations

## 🎯 Author
**Goga Gabelia** - Software Developer

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

#  Investment Calculator — React

![React](https://img.shields.io/badge/React-18+-61DAFB?style=flat-square&logo=react&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

> A minimalist investment calculator built with React — visualize the power of compound interest over time.

---


##  Features

-  Year-by-year projection table
-  Compound interest calculation
-  4 interactive parameters
-  Fully responsive design
-  Real-time updates on input change

---

##  Parameters

| Parameter | Description |
|---|---|
| `initialInvestment` | Starting capital (one-time deposit) |
| `annualInvestment` | Amount added every year |
| `expectedReturn` | Annual return rate (%) |
| `duration` | Investment horizon (in years) |

---

##  Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | UI framework |
| JSX | Component syntax |
| CSS Modules | Styling |

---

##  Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v16+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/TON_USERNAME/investment-calculator-react.git

# Navigate to the project folder
cd investment-calculator-react

# Install dependencies
npm install
```

### Run locally

```bash
npm start
```

The app will be available at `http://localhost:3000`.

### Build for production

```bash
npm run build
```

---

##  Calculation Logic

The projection is based on **annual compound interest**:

```
Balance(year) = (Balance(year-1) + annualInvestment) × (1 + expectedReturn / 100)
```

Starting from `initialInvestment` at year 0.

---

##  Roadmap

-  Chart visualization (Recharts / Chart.js)
-  Monthly contribution mode
-  Inflation adjustment
-  Export results as CSV / PDF
-  Currency selector

---

##  Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

```bash
# Create a feature branch
git checkout -b feature/your-feature-name

# Commit your changes
git commit -m "feat: add your feature"

# Push and open a PR
git push origin feature/your-feature-name
```

---

## License

This project is licensed under the [MIT License](./LICENSE).

---




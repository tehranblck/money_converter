# Currency Converter Application

This project is a currency conversion application that allows users to convert a specific amount of money from one currency to another. The project is developed with React.js and utilizes the Free Currency API to fetch exchange rates (Axios library is used).

## Features

- User-friendly and simple interface
- Conversion from one currency to another
- Real-time exchange rates

## Getting Started

These instructions provide the necessary steps to run the project on your local machine.

### Prerequisites

Before running this project, ensure the following software is installed:

- [Node.js](https://nodejs.org/) (Preferably the LTS version)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/kullaniciadi/projeadi.git
   ```

2. Navigate to the project directory:
   ```sh
   cd projeadi
   ```

3. Install dependencies:
   ```sh
   npm install
   ```

4. Install Axios:
   Axios is used to fetch exchange rates from the Free Currency API. To install Axios:
   ```sh
   npm install axios
   ```

### Usage

To start the project:
```sh
npm start
```
This command will start the project in development mode. You can view the project by opening http://localhost:3000 in your browser.

### Conversion Process

1. Enter the amount.
2. Select the base currency.
3. Select the target currency.
4. Click the "Convert" button.
5. The result will be displayed in the respective field.

### API Key

This project uses the Free Currency API. To change the API key, update the `token` variable:
```javascript
let token = "fca_live_FXhn90pUyFbfVTdrOWM2D7FM3b9wcfnXrzIYN0tO";
```

Please review the above README text and let me know if there are any errors or if anything else needs attention.

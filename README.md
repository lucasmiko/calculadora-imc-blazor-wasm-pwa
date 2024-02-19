# IMC Calculator Progressive Web App with Blazor

Welcome to the IMC Calculator Progressive Web App (PWA) built with Blazor WebAssembly. This project serves as a simple and educational example to demonstrate the integration of Blazor with PWA features, including the use of a manifest file for offline access and GitHub Actions for automatic deployment to GitHub Pages.

## Body Mass Index (IMC) Calculator

The main functionality of this project is an IMC calculator. IMC, or Body Mass Index, is a measure of body fat based on height and weight. It is commonly used to assess whether an individual has a healthy body weight.

### How the IMC Calculator Works

1. **Input Data:** Users provide their height and weight.
2. **Calculation:** The application then calculates the BMI using the formula: BMI = weight (kg) / (height (m))^2.
3. **Result:** The calculated BMI is then interpreted and categorized into different ranges, such as underweight, normal weight, overweight, and obesity.

## Project Goals

The primary objectives of this project are:

1. **Learn Blazor with PWA Features:** Understand and implement Progressive Web App features using Blazor, such as offline access through a manifest file.
2. **GitHub Actions for Deployment:** Utilize GitHub Actions to automate the deployment process to GitHub Pages.

## Project Structure

- `/`: Contains the source code for the Blazor WebAssembly project.
- `wwwroot/manifest.webmanifest`: The manifest file for the PWA.
- `.github/workflows/main.yml`: GitHub Actions workflow for automatic deployment to GitHub Pages.

## How to Run Locally

To run the project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/lucasmiko/calculadora-imc-blazor-wasm-pwa.git
    ```

3. Run the application:

    ```bash
    dotnet watch run
    ```

4. Open your browser and go to `https://localhost:5145` (or other default set port) to access the IMC Calculator.

## Demo

Check out the live demo of the IMC Calculator PWA: [IMC Calculator Demo](https://lucasmiko.github.io/calculadora-imc-blazor-wasm-pwa/)

## Screenshots

![image](https://github.com/lucasmiko/calculadora-imc-blazor-wasm-pwa/assets/63825231/c3d1d96a-7f47-4f1b-9ff3-c1d48dcb31c3)
![image](https://github.com/lucasmiko/calculadora-imc-blazor-wasm-pwa/assets/63825231/7fd4bf2f-8c4b-4e7a-b7c0-6a6790323938)
![image](https://github.com/lucasmiko/calculadora-imc-blazor-wasm-pwa/assets/63825231/4bdfe2fc-6cf5-4aa5-818f-5dbd694c8e75)
![image](https://github.com/lucasmiko/calculadora-imc-blazor-wasm-pwa/assets/63825231/840320ea-13fc-45c0-92e2-ab58e6671651)

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create an issue or submit a pull request.

## Credits

This project was made in a Masterclass from [Balta.io](https://balta.io/)

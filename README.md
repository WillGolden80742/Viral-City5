# Viral-City5

Viral-City5 is a project aimed at analyzing dengue test results and generating insightful reports. The system tracks and manages patient information, test results, and disease outcomes, providing valuable information for epidemiological studies.

## Features

- **Patient Management**: Add, edit, and delete patient information, including name, date of birth, gender, and city.
- **Test Results**: Record and analyze dengue test results, allowing healthcare professionals to monitor disease prevalence.
- **City-wise Analysis**: Generate reports based on cities, providing insights into the spread of the disease in different regions.
- **Outcome Analysis**: Track disease outcomes, including positive and negative results, and mortality rates.
- **Random Test Data Generation**: Utilize the `RandonCasos` class to generate random test data for testing and development purposes.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Viral-City5.git
   cd Viral-City5
   ```

2. **Database Setup:**
   - Set up a MySQL database and configure the connection details in `Connection/ConnectionFactory.java`.
   - Run the SQL scripts provided in the `database_scripts` folder to create the necessary tables.

3. **Run the Application:**
   - Open the project in your preferred Java IDE.
   - Run the main application file.

4. **Generate Random Test Data:**
   - If needed, run the `RandonCasos` class to populate the database with random test data.

## Usage

1. **Patient Management:**
   - Use the `PacienteDAO` class to manage patient information, including creation, updating, and deletion.

2. **Test Results:**
   - Utilize the `ExameDAO` and `ResultadoDAO` classes to record and analyze dengue test results.

3. **City-wise Analysis:**
   - Leverage the `RelatorioDAO` class to generate reports based on cities and population data.

4. **Outcome Analysis:**
   - Use the `ResultadoDAO` class to analyze disease outcomes, including positive and negative results, and mortality rates.

## Contributors

- [Your Name](https://github.com/your-username)

## License

This project is licensed under the [MIT License](LICENSE).

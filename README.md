# Automated-Email-Sender-for-Job-Applications

This project is a Python script designed to automate the process of sending customized job application emails to multiple recipients. The script reads input data from a CSV file containing recruiter details and generates personalized emails for each recipient using a predefined message template. The emails are then sent through an SMTP server.

### Features

- Reads recruiter information from a CSV file
- Generates personalized email messages based on a template
- Creates `mailto` links for each recipient
- Sends emails using an SMTP server
- Logs sent emails to a text file

### Prerequisites

- Python 3.x
- CSV file with recruiter details
- SMTP server credentials and an app-specific password

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/automated-email-sender.git
   cd automated-email-sender
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Prepare your CSV file with the following columns:
   - `companyname`: Name of the company
   - `name`: Recruiter's name
   - `mailid`: Recruiter's email address

2. Update the `input_file` and `output_file` paths in the script:

   ```python
   input_file = 'path/to/your/input.csv'
   output_file = 'path/to/your/output.csv'
   ```

3. Update your SMTP server details, app-specific password, and LinkedIn profile URL in the script:

   ```python
   smtp_server = 'your_smtp_server'
   smtp_port = your_smtp_port
   smtp_username = 'your_email@example.com'
   smtp_app_password = 'your_app_specific_password'
   LinkedIn_Profile_URL = 'https://www.linkedin.com/in/yourprofile/'
   ```

4. Run the script:

   ```bash
   python mailtoo.ipynb
   ```

### Example

Here's a sample input CSV file:

```csv
companyname,name,mailid
CompanyA,John Doe,john.doe@example.com
CompanyB,Jane Smith,jane.smith@example.com
```

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README provides an overview of the project's purpose, features, installation instructions, usage details, and contribution guidelines. You can customize it further based on your specific needs and preferences.

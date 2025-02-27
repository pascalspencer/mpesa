# M-Pesa Integration

This repository provides a Python-based web application that integrates with Safaricom's M-Pesa API, enabling seamless payment processing for businesses and developers.

## Features

- **Payment Processing**: Initiate and manage M-Pesa payment transactions directly from the application.
- **Transaction Status**: Monitor and retrieve the status of payment transactions.
- **User-Friendly Interface**: Web-based interface for easy interaction with the M-Pesa services.

## Prerequisites

- **Python 3.x**: Ensure Python is installed on your system.
- **Flask**: Web framework used for the application.
- **Safaricom Developer Account**: Register at the [Safaricom Developer Portal](https://developer.safaricom.co.ke/) to obtain API credentials.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/pascalspencer/mpesa.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd mpesa
   ```

3. **Create a Virtual Environment**:

   ```bash
   python3 -m venv venv
   ```

4. **Activate the Virtual Environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

5. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

6. **Set Up Environment Variables**:

   Create a `.env` file in the root directory and add the following:

   ```env
   CONSUMER_KEY=your_consumer_key
   CONSUMER_SECRET=your_consumer_secret
   SHORTCODE=your_shortcode
   PASSKEY=your_lipa_na_mpesa_online_passkey
   CALLBACK_URL=your_callback_url
   ```

   Replace placeholders with your actual credentials and URLs.

7. **Run the Application**:

   ```bash
   python app.py
   ```

   The application should now be running locally.

## Usage

- **Home Page**: Access the main interface to initiate and manage M-Pesa transactions.
- **Payment Processing**: Use the provided forms to initiate payment requests.
- **Transaction Status**: View and monitor the status of your transactions.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

Special thanks to the open-source community and the contributors of the libraries and frameworks used in this project.

---

For any questions or support, please contact [spencerinc.dev@gmail.com](mailto:spencerinc.dev@gmail.com). 

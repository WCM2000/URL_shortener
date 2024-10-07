# URL Shortener

## Description
A simple and efficient URL Shortener application built using Flask. This web application allows users to shorten long URLs into more manageable links and also offers file upload functionality to generate shortened links for uploaded files. The application features a clean and user-friendly interface.

## Features
- Shorten URLs with a custom short name.
- Generate short links for file uploads.
- Display all created short links.
- Error handling for duplicate short names.
- User-friendly interface with Bootstrap.

## Technologies Used
- **Backend**: Flask
- **Frontend**: HTML, CSS, JavaScript (Bootstrap)
- **Database**: (Optional) Use a database like SQLite or any other of your choice for storing URLs if needed.
- **Environment**: Python 3.x

## Installation

### Prerequisites
Make sure you have Python 3.x installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Clone the Repository
```bash
git clone https://github.com/yourusername/url-shortener.git
cd url-shortener
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Set Up Environment Variables
You may need to set up a `.env` file for your environment variables. Make sure to include:
```
SECRET_KEY=your_secret_key
```

## Running the Application
To run the application, execute the following command:

```bash
flask run
```

You can access the application by visiting `http://127.0.0.1:5000` in your web browser.

## Usage
1. **Shorten a URL**: Enter the long URL and a custom short name, then click "Shorten URL".
2. **Upload a File**: Enter a custom short name and upload a file, then click "Shorten File URL".
3. **View Created Links**: All your created short links will be displayed below the forms.

## Error Handling
If you try to use a short name that has already been taken, an error message will be displayed, prompting you to choose another name.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to [Flask](https://flask.palletsprojects.com/) for the web framework.
- Thanks to [Bootstrap](https://getbootstrap.com/) for the front-end styling.

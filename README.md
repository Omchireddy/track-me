# IP & Phone Tracker

This Python application provides multiple tools for tracking various types of information such as IP addresses, phone numbers, and usernames. It allows users to perform several tracking functions, such as:

- **IP Address Tracker:**  Get the geographical location of an IP address, including latitude and longitude.
- **Phone Number Tracker:** Look up the details of a phone number, such as the country, operator, and timezone. It also includes an approximate location (city or region).
- **Username Tracker:** Check the availability of a username across several social media platforms like Facebook, Twitter, and Instagram.
- **Show Your IP:** Show the public IP address of the user.

## Features

1. **IP Address Tracker**
   - Enter an IP address to find the country, city, latitude, longitude, and a link to the location on Google Maps.
  
2. **Phone Number Tracker**
   - Input a phone number to retrieve details such as the country, operator, timezone, and validity of the number.
  
3. **Username Tracker**
   - Check if a username is available on popular social media platforms like Facebook, Twitter, and Instagram.
  
4. **Show Your IP**
   - Display the public IP address of the machine running the script.
## Requirements

- Python 3.x
- `requests` library
- `phonenumbers` library

You can install the required libraries using `pip`:

```bash
pip install requests phonenumbers
```
# Installation and Usage

### Clone the repository:
```bash
git clone https://github.com/yourusername/ip-phone-username-tracker.git
cd ip-phone-username-tracker
```
### Run the main script:
In the main directory, simply run the script using Python:
```bash
python main.py
```
**Menu Options:**  When you run the script, you will see a menu with the following options:

- **IP Tracker:** Track information about an IP address.
- **Show Your IP:**  Display your public IP address.
- **Phone Number Tracker:**  Track phone number details.
- **Username Tracker:**  Check username availability on popular platforms.
- **Exit:**  Close the program.

Simply choose the option you want by entering the corresponding number.

# Disclaimer

This project is intended for educational purposes and should not be used for malicious activities. The accuracy of the data provided is subject to the reliability of external APIs used.

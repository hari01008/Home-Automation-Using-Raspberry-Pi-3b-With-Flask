# Raspberry Pi Home Automation with Flask Server

This project enables home automation using a Raspberry Pi and a 4-channel relay module. The control interface is powered by a Flask server, allowing you to interact with the connected devices via a web browser.

## Installation

1. **Setup Raspberry Pi:**
   - Install Python and required dependencies.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/rpi-home-automation.git
   cd rpi-home-automation
   ```

3. **Install Flask:**
   Install Flask using pip:
   ```bash
   pip install flask
   ```

## Usage

1. **Run the Flask Server:**
   ```bash
   python home_automation.py
   ```

2. **Access the Web Interface:**
   Open your web browser and navigate to `http://<raspberry_pi_ip>:5000/` to access the home automation control panel.

## Project Structure

- `home_automation.py`: The Flask server script. Run this to start the server.
- `templates/`: Folder containing HTML templates for the web interface.
- `static/`: Directory for static files (CSS, JavaScript, images, etc.).

**Note**: Ensure that `home_automation.py` is located outside the `templates` folder, while `index.html` should be placed inside the `templates` folder.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to create pull requests or report issues.

---

**Note**: This project assumes you have a basic understanding of working with Raspberry Pi, Python, and Flask. Please ensure that your Raspberry Pi is properly set up and connected to the relay module before proceeding.

For detailed setup instructions and troubleshooting, refer to the project (https://github.com/hari01008/Home-Automation-Using-Raspberry-Pi-3b-With-Flask).

```

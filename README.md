## BLE Communication Console

This **BLE Communication Console** is a web-based application designed for seamless interaction with Bluetooth Low Energy (BLE) devices. The console allows users to discover nearby BLE devices, establish a connection, and facilitate bidirectional communication through a user-friendly interface.

### Features
- **Device Scanning**: Automatically scans for all nearby BLE devices and displays them for user selection.
- **Service and Characteristic Detection**: Automatically detects service and characteristic UUIDs of the selected device.
- **Bidirectional Communication**: Send commands and receive responses from the connected device in real time.
- **File Transfer Protocol (FTP)**: Supports file transfer to BLE devices with built-in checksum and error handling.
- **Responsive Design**: Designed for optimal viewing on various devices, ensuring a smooth user experience.

### Technologies Used
- HTML
- CSS
- JavaScript
- Web Bluetooth API

### How to Use
1. **Connect to a BLE Device**: Select a device from the scanned list and establish a connection.
2. **Send Commands**: Type your command in the input box and click the send button.
3. **Transfer Files**: Click the upload button to send files to the connected device using the FTP protocol.
4. **Monitor Responses**: View responses from the device in the log area.

### Getting Started
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/ble-console.git
   ```
2. Open the `index.html` file in your web browser to launch the console.

### Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

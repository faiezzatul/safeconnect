[2408-CS251] 2021829898 (06) FAIEZZATUL HUDA BINTI ABDUL FAIRUZ
DEVELOPING SAFECONNECT MONITOR DEVICE MONITORING AND ALERT SECURITY SYSTEM IN LOCAL AREA NETWORK (LAN) USING SNMP

!!! THIS IS ONLY THE FRONT-END SIDE. THIS PREVIEW IS CONVERTED FROM PHP FILE, LARAVEL FRAMEWORK!!!

# SAFECONNECT MONITOR #

## Overview
The Device Monitoring System is a web-based application designed to monitor and manage devices connected to a network. The system provides a comprehensive dashboard, displays network information, lists connected devices, and includes a profile page for user management.

## Features
- Dashboard: An overview of network status, including number of connected devices and alerts.
- Network Information: Detailed information about the network, such as IP addresses, subnet masks, and gateway details.
- Connected Devices: A list of all devices currently connected to the network, with relevant details like IP address, MAC address, and device name.
- Profile Page: Allows users to manage their profile settings.

## Setup and Installation

### Prerequisites
- Web Server: Laragon
- Database: MySQL
- Programming Languages: PHP, JavaScript, HTML, CSS.
- Libraries/Frameworks: 
  - Frontend: Laravel
  - Backend: Net-SNMP, SQLyog
  
## Usage

### Accessing the Application
1. Open your web browser and go to `http://localhost/`.
2. Log in using your credentials (you may need to create a user in the database if none exists).
3. Navigate through the dashboard to monitor the network and manage connected devices.

### Dashboard
- Overview: Displays real-time statistics about the network and connected devices.
- Alerts: Notifications regarding unusual activities or errors in the network.

### Network Information
- IP Address: View the IP address of your network device
- MAC Address: View the MAC address of your network device
- Type: Details about the type of yur network device
- Speed: View the current speed of your network in Mbps.

### Connected Devices
- Lists all devices currently connected to the network.
- Includes information such as IP address, MAC address, device name, and status.
- Allow users to disconnect the unwanted devices.

### Profile Page
- Allows users to update their personal information.

## Prototyping
If you want to experiment or make changes to the system, follow these steps:

1. **Local Development**
   - Clone the repository to your local machine.
   - Set up a local server environment using tools like XAMPP or MAMP.
   - Edit the code and test changes locally before deploying to a live server.

2. **Testing**
   - Use tools like Postman for API testing.
   - Implement unit tests using PHPUnit for backend validation.

## Database Structure

### Tables
- **Users**: Stores user information (username, password, email, etc.).
- **Devices**: Stores details of connected devices (IP address, MAC address, name, etc.).
- **Network_Information**: Stores network configuration details.
- **Alert**: Stores logs for monitoring activities and alerts.

### Raw Data
- **Devices**: Raw data for each connected device is collected through SNMP (Simple Network Management Protocol) and stored in the `Devices` table.
- **Network Information**: Data about the network is collected using SNMP and stored in the `Network_Information` table.

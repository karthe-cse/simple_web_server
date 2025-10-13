# EX01 Developing a Simple Webserver

# Date:20-09-2025
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.


# PROGRAM:```
from http.server import HTTPServer,BaseHTTPRequestHandler
content ='''
<!DOCTYPE html>
<html>f
<head>
  <title>TCP/IP Protocol Table</title>
  <style>
    table {
      width: 80%;
      border-collapse: collapse;
      margin: 20px auto;
      font-family: Arial, sans-serif;
    }
    th, td {
      border: 1px solid #444;
      padding: 10px;
      text-align: center;
    }
    th {
      background-color: #2980b9;
      color: white;
    }
    caption {
      font-size: 1.5em;
      margin-bottom: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <table>
    <caption>TCP/IP Protocol Suite</caption>
    <tr>
      <th>Layer</th>
      <th>Function</th>
      <th>Common Protocols</th>
    </tr>
    <tr>
      <td>Application</td>
      <td>Provides services to user applications</td>
      <td>HTTP, FTP, SMTP, DNS, DHCP, SNMP</td>
    </tr>
    <tr>
      <td>Transport</td>
      <td>Reliable or fast data transmission</td>
      <td>TCP, UDP</td>
    </tr>
    <tr>
      <td>Internet</td>
      <td>Routing and logical addressing</td>
      <td>IP, ICMP, ARP, RARP</td>
    </tr>
    <tr>
      <td>Network Access</td>
      <td>Physical data transmission</td>
      <td>Ethernet, Wi-Fi, PPP</td>
    </tr>
  </table>
</body>
</html>
'''
# OUTPUT:
![alt text](<Screenshot 2025-09-19 161548.png>)

![alt text](<Screenshot 2025-09-19 161747.png>)


# RESULT:
The program for implementing simple webserver is executed successfully.

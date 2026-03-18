
# Network Port Scanner GUI

##  Project Description

The **Network Port Scanner GUI** is a Python-based desktop application that allows users to scan open ports on a target system using a simple and user-friendly interface.

It uses **multi-threading** for fast scanning and provides real-time updates of open ports, progress, and elapsed time.

---

## Features

*  Scan any IP address or hostname
*  Fast multi-threaded scanning (up to 500 threads)
* Real-time progress tracking
* Detects common services (HTTP, SSH, FTP, etc.)
*  Displays elapsed scan time
*  Stop scan anytime
*  Save results to a text file
* 🧹Clear results easily
*  Simple Tkinter GUI interface

---

## Technologies Used

* Python 
* Tkinter (GUI)
* Socket Programming
* Multithreading
* Queue (for thread communication)

---

##  Project Structure

```
Network-Port-Scanner-GUI/
│
├── portscanergui.py   # Main application file
├── README.md          # Project documentation
```

---

##  Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/network-port-scanner-gui.git
cd network-port-scanner-gui
```

### 2️⃣ Run the application

```bash
python portscanergui.py
```

> ✅ Make sure Python is installed (Python 3.x recommended)

---

##  How It Works

1. Enter:

   * Target IP / Hostname
   * Start Port
   * End Port

2. Click **Start Scan**

3. The scanner:

   * Resolves the hostname
   * Scans ports using multiple threads
   * Displays open ports in real-time

4. Results include:

   * Port number
   * Service name (if known)

---

##  GUI Overview

* **Input Section**

  * Target
  * Start Port
  * End Port

* **Status Section**

  * Scan progress
  * Elapsed time

* **Results Section**

  * List of open ports

* **Controls**

  * Start Scan
  * Stop Scan
  * Clear
  * Save Results

---

## 📌 Example Output

```
Target: google.com (142.250.183.14)
Range: 1-1024

[+] Port 80 (HTTP) is open
[+] Port 443 (HTTPS) is open

Scan complete.
Open ports found: 2
```

---

## ⚠️ Disclaimer

This tool is for **educational purposes only**.
Do not scan networks or systems without proper authorization.

---

##  Future Improvements

* Add UDP scanning
* Export results in CSV/JSON
* Add dark mode UI
* Show closed/filtered ports
* Add OS detection

---

##  Author

**Sanjana**
BCA Student | Python & ML Enthusiast

---

## ⭐ Support

If you like this project:

  Star the repository
  Fork it
  Improve it


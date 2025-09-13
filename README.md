# Forensic Guard: Evidence Management System Using Blockchain

## Project Description
**Forensic Guard** is a blockchain-based evidence management system designed to ensure **data integrity, transparency, and security** in forensic investigations.  
Traditional systems rely on centralized databases, which are vulnerable to tampering. This project uses **Ethereum blockchain**, **smart contracts**, and **immutable timestamps** to securely store and manage forensic evidence.  

Key goals:  
- Prevent tampering of evidence  
- Provide traceability and accountability  
- Enable secure sharing of evidence between users  

---

## Key Features
- Smart contracts for evidence and user management  
- Immutable timestamps for all records  
- Encryption of sensitive data  
- Web interface built with **Flask**  
- Local blockchain simulation using **Ganache**  
- Integration with **MetaMask** for Ethereum wallet management  

---

## Tech Stack
- **Backend:** Python (Flask)  
- **Blockchain:** Ethereum, Solidity, Truffle, Ganache  
- **Frontend:** HTML templates (Flask)  
- **Wallet Integration:** MetaMask  
- **Blockchain interaction:** Web3.py  

---

## Project Structure
forensic-guard/

│── contracts/ # Solidity smart contracts

│── migrations/ # Truffle deployment scripts

│── templates/ # HTML pages (Flask)

│── static/files/ # Uploaded evidence files

│── app.py # Flask backend

│── truffle-config.js # Truffle config

│── requirements.txt # Python dependencies

│── README.md # Project info

│── .gitignore


---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Madhavan0731/ForensicGuard.git
cd ForensicGuard 
```
### 2. Install Python dependencies
```bash
pip install -r requirements.txt
```
### 3. Set up Truffle & Ganache
a. Open Ganache (or run a local blockchain).
b. Compile contracts:
```bash
truffle compile
```
### 3. Deploy contracts:
```bash
truffle migrate
```
### 4. Run Flask Application
```bash
python app.py
```
-> Open your browser and go to http://127.0.0.1:5000

-> You can now use the web interface to add users, upload evidence, and check evidence.

### Usage

->AddUser: Register new users.

->UserLoginAction: Login with existing users.

->AddEvidence: Upload evidence files to blockchain.

->CheckEvidence: Verify and download stored evidence.



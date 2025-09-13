# Forensic Guard: Evidence Management System Using Blockchain

## Project Description
**Forensic Guard** Secure Evidence System using Block Chain Technology is a blockchain-based solution designed to enhance the management of digital evidence. By leveraging decentralized storage and cryptographic techniques, EPS ensures that evidence is secure, tamper-proof, and verifiable throughout its lifecycle.

The system is built with a user-friendly interface, simplifying adoption and usage across organizations. Its modular architecture allows for scalability without adding complexity, while enhanced security measures automate evidence handling to maintain data integrity.

EPS addresses the challenges of traditional evidence management systems, including risks of tampering, legal uncertainties, and scalability issues. Comprehensive training resources support effective use, and ongoing development focuses on creating a transparent, secure, and efficient environment for digital evidence management. 

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

Make sure you have **Python 3.7.0** and **pip 24.0** installed. Then run:
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



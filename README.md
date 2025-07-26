# Secure Blockchain File System

---

### 🚀 Project Overview

The **Secure Blockchain File System** is an innovative platform designed to revolutionize digital trust by ensuring the **integrity, authenticity, and non-repudiation** of digital files. It leverages cutting-edge **Ethereum blockchain technology** to provide a tamper-proof, transparent, and verifiable mechanism for managing and auditing crucial digital assets.

In today's digital landscape, where files are constantly shared and stored online, traditional systems often fall short in preventing unauthorized tampering, accidental modifications, or malicious rollback attacks. This project directly addresses these critical challenges, offering a robust and verifiable solution essential for sectors where data integrity is paramount, such as healthcare, legal, finance, and government.

This project was conceived and developed by **Team Vulnhunt** during a hackathon, driven by the shared goal to **eliminate file tampering and ensure digital trust through decentralized verification.**

**Current Development Status:** The Frontend UI is active and fully navigable. Core backend logic for user login and blockchain interactions (including audit trail processing) is currently **under development**.

---

### ✨ Key Features

* **Secure File Upload:** Encrypt files and securely upload them to off-chain storage, generating cryptographic hashes.
* **Immutable Hash Storage on Ethereum:** Store unique SHA-256 hashes of files directly on the **Ethereum blockchain** using Smart Contracts. This forms a permanent, tamper-proof, and time-stamped record, negating the need for a separate traditional database for core file integrity data.
* **Independent File Verification:** Easily verify the integrity and authenticity of any file by re-hashing it and comparing the result against the blockchain's immutable record on Ethereum.
* **Transparent Audit Trail on Ethereum:** Access a public and unchangeable history of all file submissions, updates, and verification events logged directly onto the Ethereum blockchain.
* **Privacy-Preserving:** No actual file content is stored directly on the blockchain; only cryptographic hashes are recorded, preserving privacy while ensuring integrity and decentralization.
* **Intuitive UI/UX:** A clean, modern, and user-friendly interface built with React.js for seamless user interaction.
* **Authentication & Access Control (Under Development):** Secure user login and management to control access to file operations.

---

### 🛠️ Technology Stack

* **Frontend:**
    * React.js
    * React Router DOM
    * Pure CSS (with CSS Variables)
* **Backend (Under Development):**
    * Node.js (Express.js) / Python (Flask/Django) / Go
    * *Note: No separate traditional database (e.g., MongoDB / PostgreSQL) is planned for core file integrity data, as this is handled by Ethereum.*
* **Blockchain:**
    * **Ethereum**
    * Solidity (for Smart Contract development)
* **Decentralized Storage (Planned):**
    * IPFS (InterPlanetary File System) / Filecoin
    * *Alternatively: Traditional Cloud Storage like AWS S3*

---

### 🚀 Getting Started

Currently, the primary focus for local setup is the **Frontend application**.

#### Prerequisites

Ensure you have the following installed on your system:
* **Node.js (LTS Version):** [Download and Install](https://nodejs.org/en/) (includes npm).
* **npm:** Node Package Manager (comes bundled with Node.js).

#### Installation

1.  **Clone the repository:**
    ```bash
    git clone [YOUR_REPOSITORY_URL]
    ```
    Replace `[YOUR_REPOSITORY_URL]` with the actual URL of your Git repository.
2.  **Navigate into the project directory:**
    ```bash
    cd blockchain-file-system-ui
    ```
3.  **Install Frontend dependencies:**
    ```bash
    npm install
    ```
    *(Note: Backend and Smart Contract setup instructions will be added here as those components are developed.)*

#### Running the Application (Frontend)

1.  **Start the development server:**
    ```bash
    npm start
    ```
    This will open the application in your default web browser at `http://localhost:3000`.

---

### 📖 Usage

Once the frontend application is running, you can:

* **Explore the Landing Page:** Understand the project's core purpose and features.
* **Navigate to Login:** Access the authentication page. (Currently uses **mock login: `username: user`, `password: password`** for testing the UI flow, as backend login logic is under development).
* **Browse Information Pages:** Visit "About Us," "Contact Us," and "Privacy Policy" via the header or footer links.
* **Interact with Core Functionalities (UI Mockups):** The UI for the Dashboard, File Upload, File Verification, and Audit Trail is present and ready for integration with the backend and blockchain logic (which is under development).

—

### 📂 Project Structure


---

### 👨‍💻 Built By Team Vulnhunt

This project was conceived and developed during a hackathon by **Team Vulnhunt**:

* **Kanak Soni** – UI/UX Designer
* **Sakshi Chandravanshi** – Frontend Developer
* **Ravi Kant Mishra** – Backend & Blockchain Integration
* **Arya Kulkarni** – Smart Contract Developer

---

### 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---


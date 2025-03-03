# Project Setup Guide

## Prerequisites

Ensure you have the following installed on your system before proceeding:

- **Node.js (LTS version)**
- **Visual Studio 2022**
- **Azure Cosmos DB**

## Installation Steps

### 1. Clone the Repository

Clone the project to your local machine using:

```sh
git clone <repository-url>
```

### 2. Open in Visual Studio

1. Open **Visual Studio 2022**.
2. Click **Open Project**.
3. Locate the cloned project and open it.
4. A popup will appear listing required dependencies—click **Install**.
5. The **Visual Studio Installer** will open with pre-selected software—click **Install** at the bottom.
6. Wait for the installation to complete.
7. Restart **Visual Studio**.
8. Open the previously loaded project.

### 3. Setting up **DocumentSummaryFlaskBackend**

1. Right-click on the **DocumentSummaryFlaskBackend** project.
2. Click **Open in Terminal**.
3. Run the following command to install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. After installation, start the backend server:
   ```sh
   python app.py
   ```

### 4. Setting up **TextSummarizer** Frontend Application

1. Right-click on the **TextSummarizer** project.
2. Click **Open in Terminal**.
3. Install the required dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

### 5. Running the **.NET MVC Server**

- Run the **.NET MVC Server** directly over **HTTPS** through the **Visual Studio Ribbon**.

Once all services are up and running, you are ready to go!


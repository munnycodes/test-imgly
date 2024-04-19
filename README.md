## Imgly CE SDK Photo Editor

This project demonstrates a simple web application for photo editing using the Imgly Creative Editor SDK (CE SDK). It leverages the power of Next.js.

### Prerequisites

Node.js and npm (or yarn) installed on your system.
Getting Started

### Clone the Repository:

Use Git to clone this repository to your local machine:

Bash
git clone https://github.com/munnycodes/test-imgly

Install Dependencies:

Navigate to the project directory:

Bash
cd test-imgly

Install the required dependencies:

Bash
npm install

(If you use yarn, the command would be yarn install.)

### Setting Up Your Imgly License Key

Create a .env.local File:

Create a file named .env.local in your project's root directory. This file will store your license key securely and is not version-controlled.

Add Your License Key:

In the .env.local file, add the following line, replacing YOUR_LICENSE_KEY with your actual Imgly license key:

NEXT_PUBLIC_LICENSE=YOUR_LICENSE_KEY
Running the Development Server:

Start the Server:

Run the following command to start a local development server:

Bash
npm run dev
(If you use yarn, the command would be yarn dev.)

Open in Browser:

Open http://localhost:3000 in your web browser to view the photo editing app.

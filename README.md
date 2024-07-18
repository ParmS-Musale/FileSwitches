# FileSwitch

FileSwitches is a web application that allows users to convert Word documents (.doc, .docx) to PDF format. The application uses a React frontend and an Express backend to handle file uploads and conversions.

## Features

- Upload Word documents (.doc, .docx) from your local machine.
- Convert Word documents to PDF format.
- Download the converted PDF file.

## Installation

### Prerequisites

- Node.js
- npm or yarn

### Backend Setup

1. Clone the repository:

    ```sh
    git clone https://github.com/ParmS-Musale/FileSwitches.git
    cd FileSwitches/Backend
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Start the backend server:

    ```sh
    node app.js
    ```

### Frontend Setup

1. Navigate to the frontend directory:

    ```sh
    cd ../Frontend
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Start the frontend development server:

    ```sh
    npm run dev
    ```

## Usage

1. Open your browser and navigate to `http://localhost:5173`.
2. Click on the "Choose File" button and select a Word document (.doc, .docx) from your local machine.
3. Click on the "Convert File" button.
4. After the conversion is complete, a download link will be generated for the converted PDF file.


## Technologies Used

- **Frontend:**
  - React
  - Vite
  - Tailwind CSS
  - Axios

- **Backend:**
  - Node.js
  - Express
  - Multer
  - docx-pdf
  - Cors

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

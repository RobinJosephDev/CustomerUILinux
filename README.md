# CustomerUI

CustomerUI is a React + TypeScript web application built with Vite. It serves as the frontend for customers to view shipments created by carriers and send emails with quotes to carriers. The backend is powered by Laravel, with PostgreSQL as the database.

## Features
- **Customer Authentication**: Customers can log in securely.
- **View Shipments**: Customers can see shipments created by carriers.
- **Send Quotes via Email**: Customers can send quotes related to shipments to carriers.

## Tech Stack
- **Frontend**: React (with TypeScript) + Vite
- **Backend**: Laravel
- **Database**: PostgreSQL

## Installation

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (LTS recommended)
- [Yarn](https://yarnpkg.com/) or npm

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/CustomerUI.git
   cd CustomerUI
   ```
2. Install dependencies:
   ```sh
   yarn install
   # or
   npm install
   ```
3. Start the development server:
   ```sh
   yarn dev
   # or
   npm run dev
   ```

## Environment Variables
Create a `.env` file in the root directory and configure the API base URL:
```
VITE_API_BASE_URL=http://127.0.0.1:8000/api
```

## Build for Production
To create an optimized production build:
```sh
yarn build
# or
npm run build
```

## Linting and Formatting
Run ESLint to check for issues:
```sh
yarn lint
# or
npm run lint
```

## Contributing
If you want to contribute, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.


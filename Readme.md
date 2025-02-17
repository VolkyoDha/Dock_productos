# Productos 


This application allows you to enter product information (name and price) into a MongoDB database.

made by Carlos Lobo and Paola Solano

## Technologies Used

- Node.js
- Express
- Mongoose
- Docker


## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/VolkyoDha/Dock_productos
   cd Dock_productos
   ```

## Install dependencies:
```bash
npm install
```

## Create a .env file in the root directory with the following content:
```bash
const uri = "mongodb+srv://admin:<password>@data3apps.owzveqi.mongodb.net/?appName=Data3apps";
```

## Start the application:
   ```bash
   npm start
   ```
## Using Docker:
1. **Build the Docker image::**
   ```bash
   docker build -t Dock_productos .
   ```

2. **Build the Docker image::**
   ```bash
   docker run -p 3001:3001 --env-file .env Dock_productos
   ```

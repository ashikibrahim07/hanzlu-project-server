# Backend README

This directory contains the **Node.js and Express.js-based backend** for the project.

## **Setup Instructions**

### **Install Dependencies**

```bash
npm install
```

### **Environment Variables**

Create a `.env` file in the `server` directory and configure it with the following variables:

```env
MONGODB_URI=<your-mongodb-uri>
PORT=5000
```

### **Run the Backend Locally**

```bash
npm start
```

The server will run on [http://localhost:5000](http://localhost:5000).

### **API Endpoints**

- `GET /api/items`: Fetch all items
- `POST /api/items`: Add a new item

# License

This project is licensed under the [MIT License](./LICENSE).

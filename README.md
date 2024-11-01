# Text-to-Image Generation using OpenAI API

Welcome to the **Text-to-Image Generation** project! This is a mini-project focused on creating a text-to-image generator using the OpenAI API, with MongoDB as the database for storing generated images, similar to Pinterest. This app is built with React for the frontend and Node.js for the backend.

## 🌟 Features
- Real-time text-to-image generation using OpenAI API
- Secure storage of generated images in MongoDB
- Intuitive, Pinterest-style UI for image display and interaction
- Built with a full-stack architecture: React + Node.js + MongoDB

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/) (or MongoDB Atlas for cloud-based database)
- [OpenAI API Key](https://platform.openai.com/signup)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/jayeshpandey01/text_to_image.git
   cd text_to_image
   ```

2. **Install Dependencies**

   For backend (in the root folder):
   ```bash
   npm install
   ```

   For frontend (in the `client` folder):
   ```bash
   cd client
   npm install
   ```

3. **Set Up Environment Variables**

   Create a `.env` file in the root directory and add the following variables:

   ```plaintext
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   OPENAI_API_KEY=your_openai_api_key
   ```

### Running the Application

- **Backend**: Run the following command in the root directory:

  ```bash
  npm start
  ```

- **Frontend**: In the `client` directory, run:

  ```bash
  npm start
  ```

The backend will run on `http://localhost:5000`, and the frontend on `http://localhost:3000` by default.

## 📂 Folder Structure

```
text_to_image
├── client          # React frontend
├── server.js       # Node.js backend entry
├── models          # MongoDB models
├── routes          # API routes
├── .env.example    # Environment variable example
└── README.md       # Project README file
```

## 🖼️ Demo

Once running, enter a text prompt in the app to generate an image. The image will be displayed in the UI and stored in the MongoDB database for later retrieval.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

1. Fork the project
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🛠️ Built With

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [OpenAI API](https://platform.openai.com/)


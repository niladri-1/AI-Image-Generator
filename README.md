# MERN AI Image Generator

A full stack MERN application that uses the OpenAI API to generate images. Features include image generation, user profiles, and social sharing, with Cloudinary for image storage.

## Features

- AI Image Generation
- User Profiles
- Social Sharing

## Technologies Used

- **Frontend:** React
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **API Integrations:** OpenAI, Cloudinary
- **Deployment:** Heroku, Vercel

## Setup

### Requerd

- Node.js
- MongoDB
- OpenAI API Key
- Cloudinary Account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/niladri-1/AI-Image-Generator.git
   cd AI-Image-Generator
   ```

2. Install dependencies:
   ```bash
   cd client
   npm install
   
   cd ../server
   npm install
   ```

3. Create a `.env` file in the server directory with:
   ```
   OPENAI_API_KEY="<GET_OPENAI_API>"

   MONGODB_URL="<GET_MONGODB_URL>"
   ```

## Run the Project

1. **Frontend**: Set up React, build UI, integrate OpenAI API.
   ```bash
   cd client
   npm start dev
   ```

2. **Backend**: Set up Express server, MongoDB schemas, API routes.
   ```bash
   cd server
   npm start
   ```

## Deployment

1. Prepare the app for production.
2. Deploy to Heroku or Vercel.

## Notes

- Use a clear folder structure.
- Follow best practices for debugging and troubleshooting.

## Conclusion

This app demonstrates the process of building a MERN stack application with AI image generation capabilities.

Happy coding!
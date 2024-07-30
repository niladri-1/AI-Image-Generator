# MERN AI Image Generator

A full stack MERN application that uses the OpenAI API to generate images. Features include image generation, user profiles, and social sharing, with Cloudinary for image storage.

## Technologies Used

- **Frontend:** React
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **API Integrations:** OpenAI, Cloudinary
- **Deployment:** Vercel, Netlify

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

3. Create a `server/.env` file in the server directory with:
   ```
    OPENAI_API_KEY="<GET_THE_OPENAI_KEY>"
    MONGODB_URL="<GET_MONGODB_URL>"

    CLOUDINARY_CLOUD_NAME="<GET_CLOUD_NAME>"
    CLOUDINARY_API_KEY="<GET_API_KRY>"
    CLOUDINARY_API_SECRET="<GET_SECRET_API_KEY>"
   ```

## Run The Project

1. **`Frontend`**: Set up React, build UI, integrate OpenAI API.
   ```bash
   cd client
   npm run dev
   ```

2. **`Backend`**: Set up Express server, MongoDB schemas, API routes.
   ```bash
   cd server
   npm start
   ```

## Deployment

1. Prepare the app for production.
2. Deploy to Vercel or Netlify.

## Notes

- Use a clear folder structure.
- Follow best practices for debugging and troubleshooting.

## Conclusion

This app demonstrates the process of building a MERN stack application with AI image generation capabilities.

Happy coding! `^_^`
# DevTube 

An open-source **video streaming platform** similar to YouTube, built using **free technologies** to provide seamless video uploading, sharing, and real-time interactions.  

## Technology Stack & Tools  
- **Node.js** – Backend server  
- **Express.js** – Web framework  
- **MongoDB** – Database for storing videos & user data  
- **Mongoose** – ODM for MongoDB  
- **EJS** – Templating engine for dynamic UI  
- **Multer** – File upload handling  
- **ImageKit** – Image & video optimization  
- **Bunny.net** – Content delivery network (CDN) for fast video streaming  
- **Socket.io** – Real-time chat & notifications  
- **Tailwind CSS** – Modern UI styling  

## Features  
**Upload & Stream Videos** – Users can upload videos and watch them instantly.  
**User Authentication** – Google OAuth & Local Login system for secure access.  
**Real-Time Chat** – Connect with other users while watching videos.  
**Like, Comment & Share** – Engage with video content.  
**Optimized Video Delivery** – Fast & efficient playback with **Bunny.net CDN**.  

## Requirements For Initial Setup  
- Install [Node.js](https://nodejs.org/)  
- Install [MongoDB](https://www.mongodb.com/)  
- Create an account on [Bunny.net](https://bunny.net/)  

## How It Works
- **Users Sign Up/Login** – Using Google OAuth or local authentication.
- **Upload Videos** – Videos are uploaded and optimized with Bunny.net CDN.
- **Watch & Interact** – Users can like, comment, and chat in real-time.
- **Smooth Streaming** – Bunny.net ensures buffer-free, high-speed playback.

## Project Structure

```bash
 /devtube
│── /public        # Static assets (CSS, JS, images)
│── /views         # EJS templates
│── /models        # Mongoose models (User, Video)
│── /routes        # Express routes
│── /controllers   # Business logic
│── app.js         # Main server file
│── package.json   # Dependencies & scripts
│── .env           # Environment variables
```

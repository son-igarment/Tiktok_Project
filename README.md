# TikTok Clone - Phạm Lê Ngọc Sơn

A feature-rich social media platform designed to replicate the core functionalities of TikTok, allowing users to create, share, and discover short-form video content.

## Project Overview

This TikTok clone application is built using Next.js, React, and TypeScript, with Tailwind CSS for styling. The backend is powered by Sanity.io for content management, providing a full-stack solution for video sharing.

## Features

- **User Authentication**: Sign in with Google using OAuth
- **Video Upload**: Create and share short videos with the community
- **User Profiles**: Customizable user profiles with uploaded videos
- **Social Interactions**: Like, comment, and share functionality
- **Content Discovery**: Explore trending videos and suggested accounts
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Search Functionality**: Find videos and users with the search feature

## Tech Stack

- **Frontend**:
  - Next.js 12
  - React 18
  - TypeScript
  - Tailwind CSS
  - Zustand (State Management)
  - React Icons

- **Backend & Data**:
  - Sanity.io (Headless CMS)
  - Next.js API Routes

## Project Structure

- **/components**: Reusable UI components
  - Navbar, Sidebar, VideoCard, Comments, etc.
- **/pages**: Application routes and pages
  - Main feed, video detail, user profiles, upload page
- **/styles**: Global and component-specific styles
- **/utils**: Helper functions and utilities
- **/store**: State management with Zustand
- **/sanitybackend**: Sanity.io schema and configuration
- **/public**: Static assets and resources

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- Yarn or npm

### Installation

1. Clone the repository
   ```
   git clone <repository-url>
   ```

2. Install dependencies
   ```
   yarn install
   # or
   npm install
   ```

3. Set up environment variables
   Create a `.env.local` file with the necessary API keys and configuration

4. Run the development server
   ```
   yarn dev
   # or
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

This application can be deployed using Vercel for the frontend and Sanity.io for the backend.

## License

This project is owned and maintained by Phạm Lê Ngọc Sơn.

---

Developed with ❤️ by Phạm Lê Ngọc Sơn

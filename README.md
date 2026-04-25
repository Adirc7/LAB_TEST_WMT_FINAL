# MERN Item Manager – Lab Test

## Student Information
- **Student ID:** IT24103675
- **Name:** Bandara H. M. T. A.
- **Course:** SE2020 – Web and Mobile Technologies

## Project Overview
Full‑stack MERN application that manages items.  
Each item contains:
- **Name** (required)
- **Description** (required)  
- **Price** (required, added as the new field for this lab test)

Features: add, view, delete, and update items.

## Live URLs (Deployed)
| Service | URL |
|---------|-----|
| GitHub Repository | `https://github.com/your-username/mern-item-manager` |
| Backend (Railway / Render) | `https://your-backend.up.railway.app` |
| Frontend (Netlify / Vercel) | `https://your-frontend.netlify.app` |

## Technology Stack
- **Backend:** Node.js, Express, MongoDB, Mongoose, CORS, dotenv
- **Frontend:** React, Vite, Axios
- **Deployment:** Railway (backend), Netlify (frontend)
- **Version Control:** Git + GitHub (public repository)

## New Field Added – Price
- **Model** (`backend/models/Item.js`): added `price: { type: Number, required: true, min: 0 }`
- **Frontend** (`ItemForm.jsx`): added number input field
- **Display** (`ItemList.jsx`): shows `Price: $...`

## Local Development Setup

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas account
- Git

### 1. Clone the repository
```bash
git clone https://github.com/your-username/mern-item-manager.git
cd mern-item-manager

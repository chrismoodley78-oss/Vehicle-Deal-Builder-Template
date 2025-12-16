# 🚗 Vehicle Deal Builder Pro

A complete web-based vehicle deal management system with approval workflow.

## ✨ Features
- ✅ **User Authentication** with roles (Salesman, Manager, Admin)
- ✅ **Deal Builder** with comprehensive calculations
- ✅ **Manager Approval Workflow**
- ✅ **PDF & Excel Export**
- ✅ **Customer Portal**
- ✅ **Database Storage** (SQLite)
- ✅ **Mobile Responsive Design**

## 🚀 Quick Deployment

### **Option 1: Railway.app (Recommended - 2 minutes)**
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/yourusername/vehicle-deal-builder)

1. Click the Railway button above
2. Connect your GitHub account
3. Click "Deploy Now"
4. Your app is live!

### **Option 2: Render.com (Free)**
1. Go to [render.com](https://render.com)
2. Create new "Web Service"
3. Connect this repository
4. Set: **Build Command** `npm install`
5. Set: **Start Command** `node src/server.js`
6. Click "Create Web Service"

### **Option 3: Vercel + Railway**
- Frontend on Vercel: `vercel --prod`
- Backend on Railway: Drag and drop `src/` folder

### **Option 4: Local Development**
```bash
# Clone repository
git clone https://github.com/yourusername/vehicle-deal-builder.git
cd vehicle-deal-builder

# Install dependencies
npm install

# Start application
npm start

# Open http://localhost:3000
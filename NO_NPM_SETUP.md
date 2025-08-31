# 🚀 **HR DataMatrix - No npm Required Setup**

This guide shows you how to run your HR DataMatrix application **WITHOUT** using `npm install`. Perfect for corporate environments where npm is restricted.

## ✅ **What You Get Without npm:**

- **Login System** - Full authentication with your HR users
- **Dashboard** - Basic user interface
- **CDN Libraries** - All React, Tailwind CSS, and other libraries loaded from CDN
- **No Corporate Firewall Issues** - Bypasses npm registry restrictions

## 🐍 **Backend Setup (Python Required)**

### **1. Navigate to Backend Directory**
```bash
cd backend
```

### **2. Create Virtual Environment**
```bash
python3 -m venv venv
# On Windows:
python -m venv venv
```

### **3. Activate Virtual Environment**
```bash
# On macOS/Linux:
source venv/bin/activate

# On Windows:
venv\Scripts\activate
```

### **4. Install Python Dependencies**
```bash
pip install -r requirements.txt
```

### **5. Start Backend Server**
```bash
python3 app.py
# On Windows:
python app.py
```

**Backend will run on**: http://localhost:5001

---

## 🌐 **Frontend Setup (No npm Required)**

### **Option 1: Python HTTP Server (Recommended)**

#### **On Windows:**
```bash
cd frontend
serve.bat
```

#### **On macOS/Linux:**
```bash
cd frontend
python3 serve.py
```

### **Option 2: Manual Browser Opening**

1. **Navigate to frontend directory**
2. **Double-click on `index.html`** - Opens in default browser
3. **Or drag `index.html` to browser**

### **Option 3: Built-in Python Server**
```bash
cd frontend
python3 -m http.server 3000
# On Windows:
python -m http.server 3000
```

**Frontend will run on**: http://localhost:3000

---

## 🎯 **Quick Start Commands**

### **Terminal 1 - Backend:**
```bash
cd backend
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python3 app.py
```

### **Terminal 2 - Frontend:**
```bash
cd frontend
python3 serve.py  # On Windows: serve.bat
```

---

## 🔐 **Login Credentials**

Use any of these pre-configured HR users:

| Department | Email | Password | Role |
|------------|-------|----------|------|
| CCR | priya.sharma@ccr.com | Priya@123 | HR Manager |
| I2R | rohan.mehta@i2r.com | Rohan@123 | HR Business Partner |
| MKD | anjali.verma@mkd.com | Anjali@123 | Recruitment Specialist |
| Bacardi | vikram.rao@bacardi.com | Vikram@123 | Talent Acquisition Manager |
| Xone | sneha.kapoor@xone.com | Sneha@123 | Learning & Development Specialist |

---

## 📁 **File Structure (No npm)**

```
frontend/
├── index.html          # Main application (CDN-based)
├── serve.py            # Python HTTP server
├── serve.bat           # Windows batch file
└── public/             # Static assets
```

---

## 🌟 **Features Available Without npm:**

- ✅ **User Authentication** - Login/logout system
- ✅ **Role-Based Access** - Different user roles
- ✅ **Department Management** - User department tracking
- ✅ **Modern UI** - Tailwind CSS styling
- ✅ **Responsive Design** - Works on all devices
- ✅ **Toast Notifications** - User feedback system

---

## 🚨 **Limitations (No npm Version):**

- ❌ **No Advanced Components** - Basic dashboard only
- ❌ **No File Upload** - Excel import not available
- ❌ **No Advanced Routing** - Single page application
- ❌ **No State Management** - Basic React hooks only

---

## 🔧 **Troubleshooting**

### **Port Already in Use:**
```bash
# Check what's using port 3000
lsof -i :3000  # On macOS/Linux
netstat -an | findstr :3000  # On Windows

# Kill process or use different port
```

### **Python Not Found:**
```bash
# Check Python installation
python3 --version
python --version

# Install Python from python.org if needed
```

### **Backend Connection Failed:**
- Ensure backend is running on port 5001
- Check firewall settings
- Verify CORS headers in backend

---

## 🎉 **Success Indicators**

1. **Backend**: http://localhost:5001 shows Flask welcome page
2. **Frontend**: http://localhost:3000 shows login form
3. **Login**: Can authenticate with HR user credentials
4. **Dashboard**: Shows user information after login

---

## 🔄 **Upgrade to Full Version Later**

When you have access to npm:
```bash
cd frontend
npm install
npm start
```

This will give you the full application with all features.

---

## 📞 **Support**

If you encounter issues:
1. Check both backend and frontend are running
2. Verify ports 5001 and 3000 are available
3. Check browser console for JavaScript errors
4. Ensure Python dependencies are installed correctly

**Your HR DataMatrix system is now running without npm!** 🎯

# CHROMABELLE - Art Gallery Website

A beautiful art gallery website featuring famous artworks with Go Live functionality.

## 🚀 Go Live Setup

### Option 1: VS Code Live Server Extension (Recommended)
1. Install the **Live Server** extension in VS Code
   - Press `Ctrl+Shift+X` (or `Cmd+Shift+X` on Mac)
   - Search for "Live Server" by Ritwick Dey
   - Click Install

2. Start Go Live:
   - Right-click on `index.html` in VS Code
   - Select "Open with Live Server"
   - Or click "Go Live" in the bottom status bar

### Option 2: Command Line
```bash
# Start live server
npm run live

# Or use the global installation
live-server --port=5500 --host=localhost --open=/index.html
```

### Option 3: Direct live-server command
```bash
live-server
```

## 🌐 Access Your Site
Once Go Live is running, your site will be available at:
- **Local**: http://localhost:5500
- **Network**: http://[your-ip]:5500

## 📁 Project Structure
```
CHROMABELLE/
├── index.html              # Main gallery page
├── artwork-*.html          # Individual artwork pages
├── login.html              # Login page
├── signup.html             # Signup page
├── images/                 # Artwork images
├── .vscode/                # VS Code configuration
│   ├── settings.json       # Live Server settings
│   └── extensions.json     # Recommended extensions
└── package.json            # Project configuration
```

## ✨ Features
- **Live Reload**: Automatically refreshes when you make changes
- **Hot Reload**: Updates without full page refresh
- **Cross-browser Support**: Works in all modern browsers
- **Network Access**: Accessible from other devices on your network

## 🔧 Configuration
The Live Server is configured to:
- Run on port 5500
- Open `index.html` by default
- Use localhost as the host
- Enable network access for mobile testing

## 🚀 Quick Start
1. Open the project in VS Code
2. Install the Live Server extension
3. Right-click `index.html` → "Open with Live Server"
4. Your site is now live! 🎉

## 📝 Notes
- The server will automatically reload when you save changes to HTML, CSS, or JavaScript files
- You can access your site from other devices on the same network
- To stop the server, click the "Port: 5500" button in VS Code's status bar
# chromabelleart

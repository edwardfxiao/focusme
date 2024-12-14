# focusme

🎯 A simple AppleScript utility that hides all inactive windows, leaving only your currently active window (the last application you clicked) visible. Perfect for minimizing distractions and maintaining focus during work sessions.

## Features
- Single-click window management
- Instantly hide all background windows
- Keep focus on your active window
- Lightweight and easy to use
- Native macOS integration

## How to Use

### Method 1: Script Editor (Recommended for first-time users)
1. Open Script Editor (found in Applications > Utilities)
2. Copy and paste the script code
3. Click the ▶️ (Play) button to run
4. Grant necessary permissions when prompted

### Method 2: Export as Application
#### Option A: Using Script Editor
1. Open Script Editor
2. Copy and paste the script code
3. Go to File > Export
4. Choose "Application" as File Format
5. Save your app
   
⚠️ **Important Note about Permissions:**

**The exported app will likely encounter this error:**
```
System Events got an error: "" is not allowed assistive access. (-1719)assistive access).
```

This is a common macOS security limitation for unsigned applications that try to control other applications.

To resolve this:
- You'll need to code sign the app using your Apple Developer certificate
- If you don't have a Developer certificate, it's recommended to use Method 1 or Option B below

#### Option B: Using Script Debugger (Alternative)
1. [Script Debugger](https://latenightsw.com/) (third-party app)
2. Copy and paste the script code
3. Save as application
4. Run directly without code signing issues

Perfect for developers, writers, and anyone seeking a cleaner workspace on macOS.

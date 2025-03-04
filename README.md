# Copilot Desktop

Copilot Desktop is an unofficial wrapper for Microsoft's Copilot AI Companion, providing a native Linux desktop experince.

Based on Tanmoy Ganguly [notion-desktop](https://github.com/xanmoy/notion-desktop) work.

## Disclaimer

This project and its contributors are not affiliated with Microsoft. This is simply an Electron wrapper that loads the offical Microsoft Copilot web application.

![Image](https://github.com/levicm/copilot-desktop/blob/main/screenshots/copilot-desktop.png)

---

![Image](https://github.com/levicm/copilot-desktop/blob/main/screenshots/image1.png)

## 📦 **Installation**

### Requirements

You will need to install npm, the Node.js package manager. On most distributions, the package is simply called npm.

### Build From Source

1. **Clone the repository**:

```bash
git clone https://github.com/levicm/copilot-desktop.git
cd copilot-desktop
```

2. **Install dependencies**: Ensure that you have all the necessary dependencies installed.

```bash
   npm install
```

3. Start the application:

```bash
npm start
```

4. **Build the application**: Run the following command to create a AppImage package of the application.

```bash
npm run dist
```

5. **Change to the dist directory**: Navigate to the dist directory where the AppImage package is located.

```bash
cd dist
```

6. **Make it executable**: Use the following command to make it executable.

```bash
chmod +x ./Copilot-desktop_1.0.3_amd64.AppImage 
```

### AppImage Launcher

You can integrate the AppImage through AppImage Launcher (as [Gear Lever](https://github.com/mijorus/gearlever)).

![Image](https://github.com/levicm/copilot-desktop/blob/main/screenshots/gear-lever.png)


## ↩️ **Uninstallation Steps**

Since the software is never installed, there is no need to ‘uninstall’ it. Just delete the associated AppImage file and your software is removed from the system.

If you integrated the AppImage through AppImage Launcher (as [Gear Lever](https://github.com/mijorus/gearlever)), you can right-click on the application and select Remove AppImage from the system option.

## 📖 **Usage Instructions**

### **Launching the App**:

   Once you have made the AppImage file executable, just double-click on it to run it, or execute :

```bash
   ./Copilot-desktop_0.1.0_amd64.AppImage
```

## 🤝 **Contributing**

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Acknowledgments

- **Electron** - Framework used to build the application.
- **MS Copilot** - A new tool that blends your everyday work apps into one. It's the all-in-one workspace for you and your team.

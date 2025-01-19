# QuickSites
A Chrome extension that lets you quickly access your favorite websites.

### Deploying a Chrome Extension in Developer Mode

- Ensure you have a Google account.
- Download all the files present in this repo.
- You can add your favorite website links in the <b><i>"popup.html"</i></b> file.

### Steps to Deploy

1. **Open Chrome**: Launch the Google Chrome browser on your computer.
2. **Enter Developer Mode**: Open a new tab and type `chrome://extensions` in the address bar, then press Enter. This will open the Extensions page.
3. **Enable Developer Mode**: On the Extensions page, toggle the switch in the top-right corner to "Developer mode".
4. **Load Unpacked Extension**: Click on the "Load unpacked" button that appears under the "Developer mode" section.
5. **Select Extension Folder**: A file selection dialog will appear. Navigate to the folder containing your extension files and select it.
6. **Extension Loaded**: Your extension should now appear in the list of installed extensions on the Extensions page.

### Additional Tips
- **Update Manifest**: Ensure your `manifest.json` file is correctly configured with the necessary fields such as `name`, `version`, `permissions`, etc.
- **Debugging**: Use the "Inspect views" link under your extension in the Extensions page to open the Developer Tools and debug your extension.


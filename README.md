# Outer Wilds Save Analyzer

A web-based tool to analyze your Outer Wilds save files and track your exploration progress through the solar system.

🔗 **[Try it now!](https://simonb97.github.io/outerwilds-helper/)**

![Outer Wilds Save Analyzer Interface](https://github.com/user-attachments/assets/6f5ada44-7782-4963-8fac-76f9ffc8e419)

## 🚀 Features

- **Save File Analysis**: Upload your `.owsave` file to see detailed progress information
- **Progress Tracking**: View your exploration progress across all planets and locations
- **Ship Log Summary**: See which ship log entries you've discovered
- **Story Conditions**: Track key story milestones and character interactions
- **Major Locations**: Monitor which important locations you've visited
- **Spoiler Protection**: Built-in spoiler warnings to protect your discovery experience
- **Cross-Platform**: Works on Windows, Steam, and Linux (Steam Play)

## 🎮 How to Use

1. **Find Your Save File**: Your Outer Wilds save file is typically located at:
   
   **Microsoft Store:**
   ```
   %LOCALAPPDATA%\Packages\AnnapurnaInteractive.OuterWilds_c96c51jf6wkvm\SystemAppData\wgs\
   ```
   
   **Windows (General):**
   ```
   %USERPROFILE%\AppData\LocalLow\Mobius Digital\Outer Wilds\Saves\
   ```
   
   **Steam:**
   ```
   %USERPROFILE%\AppData\LocalLow\Mobius Digital\Outer Wilds\SteamSaves\
   ```
   
   **Steam Play (Linux):**
   ```
   /steamapps/compatdata/753640/pfx/
   ```

2. **Upload Your Save**: Click the upload area or drag and drop your `.owsave` file

3. **Explore Your Progress**: Review your exploration progress, ship log entries, and story milestones

4. **Spoiler Control**: Use the "Reveal All Spoilers" toggle to control what information is visible

## 🌟 What You'll See

After uploading your save file, the analyzer will show:

- **Game Progress**: Overall completion statistics
- **Ship Logs Summary**: Progress on discovering ship log entries by location
- **Key Conditions**: Important story events and character interactions
- **Major Locations**: Which significant locations you've discovered
- **Detailed Ship Log**: Complete breakdown of all ship log entries with spoiler protection

## 🛠️ Development

This is a client-side web application built with:
- Pure HTML/CSS/JavaScript
- Tailwind CSS for styling
- No build process required

### Running Locally

1. Clone the repository
2. Open `index.html` in your web browser, or
3. Serve with any HTTP server:
   ```bash
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   ```

### Contributing

Feel free to open issues or submit pull requests to improve the analyzer!

## 🔒 Privacy

Your save files are processed entirely in your browser. No data is uploaded to any server - everything happens locally on your device.

## 🎯 About Outer Wilds

[Outer Wilds](https://www.mobiusdigitalgames.com/outer-wilds.html) is an award-winning exploration game developed by Mobius Digital. This tool is created by fans for fans to help track exploration progress.

## 📄 License

This project is not affiliated with Mobius Digital or Annapurna Interactive. Outer Wilds is a trademark of Mobius Digital.
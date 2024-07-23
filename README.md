**Json Waypoint Extractor - Akebi to Unicore v1.2.1 Changelog**

![Capture d’écran 2024-07-23 155002](https://github.com/user-attachments/assets/042101dc-1413-4b0a-8aff-27cb9a4e1c20)

**New Features :sparkles:**

- **Handles Multiple JSON Structures:** The extractor now correctly handles JSON files where waypoints are either directly in the main dictionary or within a list, providing more flexibility with the input format.

**Improvements :tools:**

- **Enhanced Error Handling:** Improved error handling for invalid JSON files and waypoints missing the required keys. Error messages are now more specific and displayed in the console output.
- **Empty Waypoint List Handling:** If no waypoints are found, an empty `waypoints.json` file is still created to prevent potential errors.
- **Accurate Color Extraction:** The extractor now correctly extracts the `Color` value from the input JSON files.

### How to Use 📝

1. Download the `extract.exe` file from the [latest release](https://github.com/Chinoontw/waypoints/releases/tag/upd)
2. Install the necessary JSON files from the [GitHub repository](https://github.com/Thafoxes/Json_Integration/tree/upstream/eng-translate).
3. Launch the application.
4. Log in with your credentials (if saved). - Username:Reimu Password:Reimu
5. Select the folder(s) containing your JSON files.
6. Click the "Extract Waypoints" button.

**Note:** This tool is designed to work with JSON files that have a "position" key containing three numerical values (x, y, z).

---

[![Discord - Reimu](https://img.shields.io/discord/1237907213411160114?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/XdN7GkGmZW)

---

**Changelog 1.2 (Reminder)**

* **Issue : Fixed Crash for importing in Unicore**

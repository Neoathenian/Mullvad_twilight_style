# Mullvad Browser - Twilight Style Dark UI Mod

A simple mod that gives **Mullvad Browser** a **Twilight-style dark gray theme** for the **tab bar** and **navigation bar**, keeping everything else unchanged. It enhances visibility, provides subtle contrast, and maintains a clean, modern look.

## Features

- **Twilight-style dark gray color** for the tab bar and navigation bar.
- **Clear text and icons** (white for visibility).
- **Slightly darker inactive tabs** for contrast.
- **Subtle rounded corners** for a smoother look.
- **Thin border effect** to separate the UI from the page.

---

## Installation

### Step 1: Enable Custom Stylesheets in Mullvad Browser

1. Open **Mullvad Browser**.
2. Type `about:config` in the address bar and press **Enter**.
3. Search for:
   ```
   toolkit.legacyUserProfileCustomizations.stylesheets
   ```
4. Double-click it to set it to **true**.

### Step 2: Locate Your Profile Folder

1. Type `about:support` in the address bar and press **Enter**.
2. Find the **Profile Folder** section.
3. Click **"Open Folder"**.
4. Inside your profile folder, check if there is a folder named **chrome**:
   - If it **doesn’t exist**, create a folder named **chrome**.

### Step 3: Create/Edit `userChrome.css`

1. Inside the **chrome** folder, create a new file called **userChrome.css** (or edit it if it already exists).
2. Open the file in a text editor and paste the userChrome.css provided.
   

### Step 4: Restart Mullvad Browser

- Close and reopen the browser to apply the changes.

---

## Screenshots

(You can add screenshots here for reference.)

---

## Notes

- If you ever want to **disable the changes**, simply delete the `userChrome.css` file or rename it.
- This tweak **only affects the UI styling** and does not change any privacy or security features of Mullvad Browser.

---

## License

This project is open-source and can be freely modified and distributed.

---

## Future Enhancements

- Add variations with different **accent colors**.
- Include a **toggle script** to enable/disable the theme easily.

Enjoy your Twilight-style dark UI on Mullvad Browser! 🚀


## Disable Automatic Windows Update Reboots

Follow these steps to disable automatic Windows update reboots:

### Step 1: Open Registry Editor
1. Search for "Registry Editor" in your Windows search bar and open it.

### Step 2: Create WindowsUpdate Key
2. In the Registry Editor, navigate to:
   - `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows`
   - Right-click on the "Windows" folder and select "New" > "Key."
   - Name the new key "WindowsUpdate."

### Step 3: Create AU Key
3. Right-click on the "WindowsUpdate" folder, select "New" > "Key," and name the new key "AU."

### Step 4: Set Windows Version
4. In the "AU" folder, right-click in the right-hand pane and select "New" > "DWORD (32-bit) Value."
5. Name the new value according to your Windows version.

### Step 5: Set Value
6. Right-click the new value and select "Modify."
7. Set the value data to your desired option.

### Step 6: Update NoAutoRebootWithLoggedOnUser
8. In the "AU" folder, locate "NoAutoRebootWithLoggedOnUser."
9. Double-click on "NoAutoRebootWithLoggedOnUser."
10. Change the value data from 0 to 1 and click "OK."

### Step 7: Close Registry Editor
11. Close the Registry Editor.
12. Your changes are now in effect, and automatic Windows update reboots should be disabled.

Your Windows should no longer automatically reboot after updates, helping you avoid interruptions during your work or usage.

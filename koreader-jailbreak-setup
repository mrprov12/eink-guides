# Jailbreaking your Kindle

As of November 2024, there are two main methods to jailbreak your Kindle:

---

## LanguageBreak (Firmware version ≤ 5.16.2.1.1)

The definitive guide for this method is provided by [marek on MobileRead](https://www.mobileread.com/forums/showthread.php?t=356872).

- ### LanguageBreak Options
  - **[One-click-testing](https://github.com/notmarek/LanguageBreak/tree/one-click-testing)**
    - This experimental branch aims to provide a one-click jailbreak method.
    - Results may vary, and it's relatively unreliable. However, it can be worth a try due to its simplicity compared to traditional methods.
  
  - **[Normal LanguageBreak](https://github.com/notmarek/LanguageBreak/)**
    - This is the recommended method for most users, though it involves some complex steps.
    - **Important**: Carefully read all instructions, as the process includes a time-sensitive step. Missing this step will require restarting the process.

---

## WatchThis (Firmware version ≤ 5.14.2)

The comprehensive guide for this method is posted by [katadelos on MobileRead](https://www.mobileread.com/forums/showthread.php?t=346037&highlight=WatchThis).

- ### General Steps
  - Follow the initial post for step-by-step instructions, suitable for Kindles at version 5.14.3 or lower. (This method was successfully used on a Kindle Voyage at v5.13.6.)
  - This method requires Kindle model-specific files, making it a more stable option.

- ### Troubleshooting Post-Jailbreak Setup
  - **Issue**: If the "Update Your Kindle" button does not appear after adding `Update_hotfix_watchthis_custom.bun` to your Kindle root storage:
    - Restarting might cause the update to fail.
    - **Solution for Jailbreak Updates** (by user mgrimace): 
      - Ensure mrpackages is updated.
      - Place the update hotfix file in the `/mrpackages` folder.
      - Use `;log mrpi` to install it.
      - Afterward, update KUAL and complete the installation.
    - **Solution for Fresh Jailbreak**
      - Install MRPI (see below)
      - Place the update hotfix file in the `/mrpackages` folder.
      - Use `;log mrpi` to install it.
      - Afterward, install KUAL and complete the installation.

---

# Installing KOreader

## Step 1: Install MobileRead Package Installer (MRPI)
- **Guide**: [MobileReads MRPI Installation Guide](https://www.mobileread.com/forums/showthread.php?t=251143)
- Recommended to install MRPI *first*, especially if needed for completing the WatchThis Jailbreak.

## Step 2: Install KUAL
- **Guide**: [MobileReads KUAL Installation Guide](https://www.mobileread.com/forums/showthread.php?t=203326)
- With MRPI installed, installing KUAL is straightforward. Choose the appropriate version, place it in the `/mrinstaller` folder, and run `;log mrpi`.

## Step 3: Install KOreader
- **Guide**: [KOreader GitHub Installation Guide](https://github.com/koreader/koreader/wiki/Installation-on-Kindle-devices)
  - Skip to Step 3 in the guide.
  - **Download** the desired version from the [KOreader Releases](https://github.com/koreader/koreader/releases) page, sideload it into the `/mrinstaller` folder.
  - Run `;log mrpi` to install KOreader.
  - **Launching**: Follow the "Launching - via KUAL" section to open KOreader.

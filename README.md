# Support My Work ❤️

Gyuz, if you like my work, please consider donating a little bit. It helps me a lot and allows me to continue creating and sharing content. 🙏🙏🙏 

### Donate (UPI, PayPal, Ko-fi):

- **UPI**: [abhayprjapati@axl](upi://abhayprjapati@axl)
- **PayPal**: [https://www.paypal.me/PrajapatiAbhay917](https://www.paypal.me/PrajapatiAbhay917)
- **Ko-fi**: [https://ko-fi.com/thereache](https://ko-fi.com/thereache)

![Donate Screenshot](https://dummyimage.com/600x200/000/fff&text=Share+Screenshot)

Thank you so much for your support! Every little bit helps and means the world to me. ❤️

---

# ROM Installation Guide for Poco X5 Pro 5G (Redwood)

📌 **Flash ROM with AOSP Recovery**

Follow these steps to install a custom ROM on your Poco X5 Pro 5G using AOSP Recovery.

## Step 1: Download Required Files
- `boot.img`
- `dtbo.img`
- `vendor_boot.img`

## Step 2: Connect to PC
- Use a USB cable to connect your phone to the PC.

## Step 3: Reboot to Fastboot Mode
- Press and hold **Power Button + Volume Down Button** to enter Fastboot mode.

## Step 4: Flash the Images
Run the following commands in your terminal (ensure you are in the directory with the downloaded files):

```bash
fastboot flash vendor_boot vendor_boot.img
fastboot flash dtbo dtbo.img
fastboot flash boot boot.img
```

## Step 5: Reboot to Recovery
```bash
fastboot reboot
```

## Step 6: Wipe Data/Factory Reset
- In recovery mode, select **Wipe Data/Factory Reset** and confirm.

## Step 7: Apply Update via ADB
- Select **Apply Update** from ADB and run the following command on your PC:

```bash
adb sideload Rom_Name.zip
```

## Step 8: Final Steps
- After installation, select **Wipe Data/Factory Reset** again and confirm.
- Reboot the system.

## Optional: Install Add-ons
- Reboot to recovery and sideload additional add-ons like **Magisk**, **firmware**, **gapps**, etc.

---

Thank you for following this guide! If you have any questions or need further assistance, feel free to reach out. Enjoy your custom ROM experience!

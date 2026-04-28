# WhatsApp Share TDL for Tally Prime

This repository contains a customized TDL script for Tally Prime that allows users to instantly share Vouchers and other Statements with their parties via WhatsApp. 

It seamlessly integrates into the Tally UI, adding quick-access buttons and automatically generating formatted WhatsApp messages containing transaction details, running balances, and inventory breakdowns.

## 🚀 Features

* **One-Click Sharing:** Directly open WhatsApp Web with a pre-filled, nicely formatted message containing the Tally data[cite: 28].
* **Voucher Sharing:** Sends complete voucher details including Voucher Number, Date, Party Name, Itemized Inventory (Name, Qty, Rate, Amount), and Total Amount[cite: 36, 37, 38].
* **Automatic Mobile Number Fetching:** Pulls the mobile number directly from the Party's Ledger Master (`LedgerMobile` or `MobileNo`)[cite: 16].
* **Smart Greetings:** Includes a friendly, personalized greeting using the Current Company Name and emojis[cite: 14].

## ⌨️ Shortcuts & Usage

Once loaded into Tally Prime, navigate to the respective forms to use the shortcuts:

| Feature | Screen | Shortcut Key |
| :--- | :--- | :--- |
| **WhatsApp Share Voucher** | Voucher Alteration/Display Screen | `Alt + W` |
| **WhatsApp Share Recipt** | Recipt | `Alt + W` |
| **whatsApp share Payment** | Payment | `Alt + W` |
| **whatsApp share Journal** | Journal | `Alt + W` |
s
## 📥 Installation Steps

1. Download the `WhatsApp_Share_Tally.tdl` file.
2. Open **Tally Prime**.
3. Press `F1` (Help) > **TDLs & Add-Ons**.
4. Press `F4` (Manage Local TDLs).
5. Set **Load selected TDL files on startup** to `Yes`.
6. Enter the local path where you saved `WhatsApp_Share_Tally.tdl` and accept the screen.
7. Open a Voucher or a Ledger Report to test the newly added buttons.

## 📝 Notes
* Ensure you are logged into WhatsApp Web on your default browser, or have the WhatsApp Desktop app installed.
* If a party does not have a mobile number saved in their Ledger Master, the script will still generate the message but will leave the phone number field blank, allowing you to manually select the contact in WhatsApp.

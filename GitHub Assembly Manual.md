# **🧮 The Self-Reliance Budget Kit (v3.7)**

A perfect budget starter kit designed for easy self-reliance. This tool is built for those on fixed incomes, side hustles, or anyone using a "jar as a bank" who wants a professional system without the privacy risks of big-bank apps.

[View Repository on GitHub](https://github.com/hitchabout/Self-Reliance-Budget)

## **🧩 Two Paths to Independence**

1. **The Spreadsheet Master (Fast & Easy):** A fully automated Google Sheet that does all the math. Great for desktop use or basic mobile tracking.  
2. **The Mobile Remote (Optional Power Upgrade):** Connects your sheet to a custom mobile app for pocket control. *Warning: This path requires setting up GitHub and API keys, which can be a bit of a climb\!*

## **🛠️ Step 1: Use the Wizard**

Open budget\_setup\_tool.html. This is the "Abacus Edition" that handles all the coding for you.

* **Fill in the Blanks:** Enter your bank balance and bills.  
* **Manage Categories:** Add custom sections with icons (like 🔧 REPAIRS).  
* **Generate Blueprint:** The Wizard calculates every row and the auto-filling formulas for people who don't know Sheets.

## **📋 Step 2: Build Your Brain (Google Sheets)**

This is where the magic happens. Even without the app, this sheet is a professional-grade tool.

1. **Copy Master Blueprint:** Click the big button in the Wizard.  
2. **Paste:** Click **Cell A7** in a fresh Google Sheet and paste.  
3. **Checkboxes:** Highlight **Column C** (the "FALSE" column) and go to **Insert \> Checkbox**.  
4. **Wiring Formulas:**  
   * Copy the **A4 Formula** from the Wizard into cell **A4**.  
   * Copy the **G3 Formula** from the Wizard into cell **G3**.  
   * Enter your bank balance (or jar amount) in cell **D3**.

**Congratulations\!** You now have a fully functional, self-correcting budget.

## **🚀 Step 3: Optional Mobile Remote Upgrade**

*Only if you want the pocket remote experience\!*

1. **GitHub:** Fork this repository to your own account.  
2. **Python Snippets:** Update streamlit\_app.py with the specific range snippets provided by the Wizard.  
3. **Secrets:** Connect Streamlit Cloud to your GitHub and paste your Google JSON Key into **Settings \> Secrets**.

*Note: The Remote App is a great convenience, but the Spreadsheet is your foundation. Don't sweat the app until your sheet is rock solid\!*

## **⚠️ The "No-Gremlins" Guarantee**

* **Auto-Filling:** The Wizard writes the formulas so you don't have to.  
* **Privacy:** Your data stays between Google and your phone. No third parties.  
* **Self-Reliance:** You own the code. You own the data.

*Blueprint for Independence • Christopher M Kollar • Coos Bay, Oregon*
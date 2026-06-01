# Uploading steps for database AdventureWorks2022 into SSMS (SQL Server Management Studio)

This file contains the step-by-step instructions to download and restore the **AdventureWorks2022** database into SQL Server Management Studio (SSMS).

---

## 🔗 Useful links

| Description | Link |
|---|---|
| Official restore instructions from Microsoft | [AdventureWorks install and configure](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms) |
| Direct download page for AdventureWorks backup files | [Download backup files](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms#download-backup-files) |

---

## 📥 Step 1 — Download the backup file

1. Go to the Microsoft download page using the link above
2. Under the **OLTP** section, download the file named **`AdventureWorks2022.bak`**

---

## 📁 Step 2 — Move the file to your SQL Server backup folder

Move the downloaded `.bak` file from your **Downloads** folder to your SQL Server backup location.

For example:
```
C:\SQL Server Management Studio
```

> **Note:** If you cannot see the file later inside the SSMS wizard, it means SQL Server does not have permission to access that folder. In that case, move the file to a different folder and try again.

---

## 🖥️ Step 3 — Open SSMS and connect to your SQL Server instance

Open **SQL Server Management Studio (SSMS)** and connect to your local SQL Server instance.

---

## 🔄 Step 4 — Launch the Restore Database wizard

In the **Object Explorer** panel on the left:

1. Right-click on **Databases**
2. Select **Restore Database...**

---

## ⚙️ Step 5 — Select your backup file

Inside the Restore Database wizard:

1. Select **Device** as the source
2. Click the **`...`** (ellipsis) button to choose a device
3. Click **Add**
4. Navigate to the folder where you saved the `.bak` file
5. Select **`AdventureWorks2022.bak`**
6. Click **OK** to close the "Select backup devices" window

---

## ✅ Step 6 — Verify the file locations

1. Click the **Files** tab inside the wizard
2. Confirm that the **Restore as** location and file names match your intended folder
3. Adjust the paths if needed

---

## 🚀 Step 7 — Restore the database

Click **OK** to start the restore process.

When complete, you will see a confirmation message and the database **AdventureWorks2022** will appear under **Databases** in your Object Explorer.

---

## 🔗 Back to repository

[← Back to SQL_SERVER-Database-AdventureWorks2022-for-SSMS](https://github.com/arieferencz/SQL_SERVER-Database-AdventureWorks2022-for-SSMS)

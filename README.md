# Personal Expense Tracker (Python + Tkinter + SQLite)

A clean and beginner-friendly **Personal Expense Tracker** desktop application built using **Python**, with a graphical interface powered by **Tkinter**, a local **SQLite3 database**, and category-wise **bar charts using Matplotlib**.

This app allows users to **record daily expenses**, view them in a **scrollable table**, and **visualize their spending habits** with just one click — all offline, no internet required!

---

## Features

-  **Add Expense**: Input amount, category, date, and description  
-  **View Expenses**: Scrollable table using `ttk.Treeview`  
-  **Visualize Expenses**: Category-wise bar chart (via `matplotlib`)  
-  **Local Storage**: Uses `SQLite` to store all data in a `.db` file  
-  **Tabbed UI**: Clean interface with `ttk.Notebook` tabs  
-  **Safe Input Handling**: Shows alerts for invalid or incomplete inputs  
-  **Lightweight & Offline**: No login, no setup, just run the file!

---

##  Screenshots

- Add Expense Tab
   ![Screenshot 2025-07-10 103542](https://github.com/user-attachments/assets/fc0893f7-bcb0-4540-92fa-4795f0bad56e)

- View Table Tab
  ![Screenshot 2025-07-10 103553](https://github.com/user-attachments/assets/56e06d93-1fd4-4d3d-a546-4236ff8d5b47)
 
- Chart Visualization Tab
  ![Screenshot 2025-07-10 103604](https://github.com/user-attachments/assets/e012aa2a-abfa-433b-bade-3a88b930af18)
 

---

## Technologies Used

| Tool/Library      | Purpose                        |
|-------------------|--------------------------------|
| Python 3          | Core programming language      |
| Tkinter           | GUI elements                   |
| ttk (Themed Tk)   | Stylish widgets like tabs, table |
| SQLite3           | Local database for expense data |
| Matplotlib        | Drawing expense bar charts     |

---

## How to Run

### 1 Clone this repository:
```bash
git clone https://github.com/your-username/expense-tracker.git
cd expense-tracker

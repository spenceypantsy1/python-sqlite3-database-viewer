
For me to come back to this when I do more research and projects and inevitably lose track of my tables and what they mean.


# 📌 **SQLite Database Viewer**  

This notebook helps you **view your SQLite database**, its tables, and assign descriptions so you can keep track of them easily. **Very fly like a G6!**

🔹 **Instructions:**  
- **Modify** the variable **`db`** in **line 3** of the following cell to specify your database.  
- Run the first code cell. 
- Run the following cells below as needed.   
  
## ⚙️ **Functions Overview**
| Function | Description |
|----------|------------|
| `create_metadata_table()` | Creates a metadata table in your SQLite database to store table descriptions. |
| `get_tables()` | Retrieves all tables from the database to be passed into `add_tables_to_metadata()` |
| `add_tables_to_metadata()` | Inserts retrieved tables into the metadata table if they don’t already exist. |
| `update_table_description('table_name', 'new_description')` | Updates the description of a specific table. Replace `'table_name'` and `'new_description'` accordingly. |
| `view_tables_with_descriptions()` | Displays all tables along with their descriptions. |


📞 Contact github.com/spenceypantsy1 or theogspencerlin@gmail.com if broken 

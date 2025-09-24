**Objective:** Filter and display data based on user input.  
- **Task:** Implement a search box for filtering names.  
- **Pseudo Code:**  
Step 1: const [search, setSearch] = useState("")
Step 2: const items = ["Apple", "Banana", "Orange", "Mango"]
Step 3: Add input → onChange={e => setSearch(e.target.value)}
Step 4: Filter → items.filter(item => item.includes(search))
Step 5: Display filtered items using map()
<img width="842" height="567" alt="Screenshot 2025-09-24 140149" src="https://github.com/user-attachments/assets/706e36c4-b1dc-4ecf-bbed-67b2b831a832" />

# employee-equality-analysis

📊 This project analyzes employee compensation fairness using an **Equality Score**.

## Dataset
The dataset contains 3 main columns:
- **Factory**
- **Job Role**
- **Equality Score** (ranging from -100 to +100, where 0 is ideal)

I added a **4th column: Equality Class** based on rules:

- **Fair** → Score between -10 and +10  
- **Unfair** → Score less than -10 or greater than +10  
- **Highly Discriminative** → Score less than -20 or greater than +20  

## Example Classification
- Score = `10` → Fair  
- Score = `-9` → Fair  
- Score = `-15` → Unfair  
- Score = `30` → Highly Discriminative  

## Tools Used
- **Excel** (for data processing)  
- **Tableau** (for visualization)  
- *(Optional)* Python for automation  

## Results
The final dataset highlights where pay is fair and where discrimination exists, enabling HR teams to take corrective action.

## Preview (Screenshot)

Here’s a sample of the processed dataset with the new **Equality Class** column:

![Equality Table Sample](equality-table-sample.png)

---
✨ Project Completed and Accepted ✔


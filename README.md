# Restaurant & Consumer Data Analysis using SQL  

**A complete end-to-end SQL project** that transforms raw restaurant and consumer CSV data into actionable business insights using advanced SQL techniques.

**I am Buddepu Vivek from Innomatics Research Labs, with strong interest in SQL, EDA, and data-driven decision-making.
**I enjoy working with structured datasets, writing optimized queries, and extracting meaningful insights from relational databases.

Live Demo / Presentation: [SQL_Project PPT.pptx](SQL_Project%20PPT.pptx) (included in repo)

---

## Project Overview  

This project analyzes real-world restaurant and consumer behavior data collected from multiple cities in Mexico.  
We built a fully normalized relational database and used **pure SQL** (MySQL / PostgreSQL) to answer real business questions that restaurant owners care about:

- Who are my best customers?  
- Which cuisine performs best in which city?  
- Where are we getting bad ratings and why?  
- What should we improve to earn more?

---

## Key Features & SQL Concepts Covered  

- Complete Database Design (5+ tables, proper PK-FK relationships)  
- ER Diagram & Data Dictionary  
- 50+ Real-world SQL queries ranging from basic to advanced  
- Joins, Subqueries, Nested Queries  
- Common Table Expressions (CTEs)  
- Window Functions (RANK, ROW_NUMBER, AVG() OVER)  
- Views for reusable reports  
- Stored Procedures (ready for automation)  
- Complex filtering & business logic implementation  

### Tables Created  
| Table Name              | Description                              |
|-------------------------|------------------------------------------|
| `consumers`             | Customer demographics & preferences      |
| `restaurants`           | Restaurant details (name, city, price, parking, etc.) |
| `restaurant_cuisines`   | Cuisines offered (many-to-many)          |
| `consumer_preferences`  | Preferred cuisines of each consumer      |
| `ratings`               | Food, Service & Overall ratings          |

---

## Business Insights Discovered  

- Students are the most active reviewers and love **Mexican** & **Pizzeria**  
- **Cuernavaca** gives the highest ratings → Medium price + Wine-Beer combo wins  
- **Mexican cuisine dominates** satisfaction across all cities  
- Franchise/Chain restaurants get significantly higher ratings  
- **Ciudad Victoria** has serious food quality issues (many 0 Food_Rating)  
- Italian cuisine is rarely tried → low awareness or availability  
- Young social drinkers don’t care about parking if vibe & price are good  

**Recommendations**  
- Open more franchise locations  
- Offer student discounts on Mexican & Pizzeria items  
- Focus quality improvements in Ciudad Victoria  
- Promote Italian cuisine with special campaigns  

---


### Important Rules
- **No AI Tools:** The use of AI assistants (ChatGPT, Copilot, Gemini, Claude, etc.) is strictly prohibited.
- **Allowed Resources:** You may use the course slides, lab scripts, official R documentation, and the R Graph Gallery.
- **Academic Integrity:** Write your own code. All submissions will be checked for authenticity.

---

### 1. Data Setup
Run this code in R to prepare your environment:

```r
sales_data <- data.frame(
  department = c(rep("Electronics", 4), rep("Home & Living", 3), rep("Apparel", 3)),
  category   = c("Smartphones", "Laptops", "Accessories", "Audio",
                 "Furniture", "Kitchenware", "Decor",
                 "Men's Wear", "Women's Wear", "Footwear"),
  units_sold = c(420, 210, 310, 140, 190, 260, 95, 280, 350, 180)
)
```

2. Instructions
A retail company wants to understand its sales performance across different segments of the business.

Using the principles discussed in class, select and implement the most appropriate plot to visualize sales_data effectively for stakeholders.

3. Submission Steps
Save your final plot as a .png file using `ggsave()`:

```r
ggsave("firstname_lastname_task.png", width = 8, height = 6, dpi = 300)
```

Commit both your .png file to your working branch.

Open a Pull Request to this repository with your Full Name in the title.

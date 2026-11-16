Important Rules
No AI Tools: The use of AI assistants (ChatGPT, Copilot, Gemini, Claude, etc.) is strictly prohibited.
Allowed Resources: You may use the course slides, lab scripts (specifically Lab 6), official R documentation, and the R Graph Gallery.
Academic Integrity: Write your own code. All submissions will be checked for authenticity.

1. Data Setup
Run this code in R to prepare your environment:

# Prepare the dataset
```r
vehicle_perf <- data.frame(
  engine_cc   = c(1200, 1400, 1600, 1800, 2000, 2200, 2500, 3000, 1300, 1500, 1700, 2400),
  fuel_consum = c(5.2, 5.8, 6.4, 7.1, 7.8, 8.5, 9.4, 11.2, 5.0, 5.5, 6.1, 8.9),
  curb_weight = c(1050, 1120, 1210, 1300, 1420, 1510, 1650, 1820, 1080, 1150, 1240, 1580),
  fuel_type   = c(0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 1, 1) # 0 = Gasoline, 1 = Diesel
)
```

2. Instructions
An automotive R&D team wants to examine how engine displacement (`engine_cc`) relates to fuel consumption (`fuel_consum`) and whether this relationship differs across fuel types (`fuel_type`).

Draw a plot to answer the question in this examination.

3. Submission Steps
Save your primary comparison plot as a .png file using ggsave():

```r
ggsave("firstname_lastname_task.png", width = 8, height = 6, dpi = 300)
```

Commit your .png file.
Open a Pull Request to this repository with your Full Name in the title.

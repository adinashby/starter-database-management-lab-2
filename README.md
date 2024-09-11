# Database Management - Lab 2

This template repository is the starter project for Database Management Lab 2. Written in Access.

### Question(s)

### Microsoft Access Lab: Creating Forms and Generating Reports

#### Objective:
By the end of this lab, students will be able to create a simple form in Microsoft Access to enter and view data, and they will understand what a report is and how to generate it from their database.

---

### Part 1: Creating a Simple Form

#### Step 1: Open Your Database
1. Open the **StudentRecords.accdb** database you created in the previous lab, or create a new one with similar data.

#### Step 2: Create a Form
1. Select the **Students** table (or any other table in your database).
2. Go to the **Create** tab on the ribbon and click on **Form** in the **Forms** group. Access will automatically generate a form based on the selected table.
3. The form will display all fields from the table as input fields.
4. Click on **Form View** to see the form in action. You can use this form to:
   - Add new records
   - View and edit existing records

#### Step 3: Modify the Form (Optional)
1. Switch to **Layout View** or **Design View** to modify the form's appearance.
2. In **Design View**, you can change field sizes, move fields around, or delete fields you don’t want displayed.
3. Save the form as **StudentForm**.

#### Questions:
1. What is the advantage of using forms for data entry?
2. How does a form simplify the process of viewing or editing records?

---

### Part 2: What is a Report?

A report is a formatted presentation of data from your database. It allows you to create printable summaries, detailed listings, or statistics based on the data.

#### Step 1: Create a Simple Report
1. Go to the **Create** tab and click **Report Wizard**.
2. In the **Report Wizard**, select the **Students** table.
3. Choose the fields you want to include in your report (e.g., **FirstName**, **LastName**, **DateOfBirth**, **Email**).
4. Follow the wizard steps to group by **LastName** if you’d like, or skip grouping.
5. You can sort the data by **LastName** or another field.
6. Click **Finish** to generate the report.

#### Step 2: Modify the Report (Optional)
1. Switch to **Layout View** or **Design View** to modify the appearance of the report. You can adjust field sizes, add headers, footers, and modify text formatting.
2. Save the report as **StudentReport**.

#### Step 3: View and Print the Report
1. Switch to **Report View** or **Print Preview** to see how the report will look when printed.
2. Use the **Print** option if you'd like to print the report.

#### Questions:
1. What are the differences between a report and a query in Access?
2. Why is it beneficial to generate reports from a database?

---

### Part 3: Conclusion
- **Discussion**: Summarize the role of forms in easing data entry and navigation, and discuss how reports provide a professional way to present data for analysis, printing, or sharing.
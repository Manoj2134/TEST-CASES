# TEST-CASES
Writing test cases


### 1. Add Student Details
- **Input**: Student ID = 101, Name = "Alice", Class = "10th", Roll No = 25
- **Expected Output**: "Student record added successfully."
- **Actual Result**: (Verify when running the system)

### 2. Add Marks for Student
- **Input**: Student ID = 101, Subjects = {Math: 88, Science: 92, English: 85}
- **Expected Output**: "Marks saved successfully for Student ID 101."

### 3. Generate Result
- **Input**: Student ID = 101
- **Expected Output**: A report showing:
  - Name: Alice
  - Class: 10th
  - Marks: Math=88, Science=92, English=85
  - Total = 265
  - Percentage = 88.33%
  - Grade = A

### 4. Search Student by ID
- **Input**: Student ID = 101
- **Expected Output**: Shows full student details and marks.

### 5. Search for Non-Existent Student
- **Input**: Student ID = 999
- **Expected Output**: "No record found for Student ID 999."

### 6. Update Marks
- **Input**: Update Science marks for Student ID = 101 → 95
- **Expected Output**: "Marks updated successfully."
- **Verify**: When generating result again, Science marks should be 95.

### 7. Delete Student Record
- **Input**: Student ID = 101
- **Expected Output**: "Student record deleted successfully."
- **Verify**: Searching Student ID = 101 should show "No record found."

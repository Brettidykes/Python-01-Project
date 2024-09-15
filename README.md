# Python-01-Project

# EC2 Random Name Generator

**Overview**  
This Python script generates a specified number of random EC2 instance names based on the department provided by the user. It ensures that only predefined departments (`FinOps`, `Marketing`, or `Accounting`) are allowed, and appends a random string of characters to the department name to form unique EC2 instance names.

**Features**  
- **Department Validation**: Only allows valid department names: `FinOps`, `Marketing`, or `Accounting`.
- **Random Name Generation**: Creates unique instance names by appending a random alphanumeric string (including symbols) to the department name.
- **Customizable Number of Names**: Users can specify how many instance names they need, and the script will generate that number.

**Usage**  
1. Run the script.
2. Enter your department name when prompted (must be `FinOps`, `Marketing`, or `Accounting`).
3. Specify how many EC2 instance names you need.
4. The script will output the generated EC2 instance names, each with a random string attached to the department name.

**Example Output:**

What is your department name? FinOps  
How many EC2 instance names do you need? 3  
Here are your generated EC2 names:  
   FinOpsA1b2C3d4!  
   FinOpsX9y8Z7p$  
   FinOpsK6l5M2n&

**Why Is This Useful?**  
For businesses running multiple **EC2 instances**, assigning unique and meaningful names to instances is important for organization, tracking, and resource management. This script:
- **Ensures consistency**: The naming convention includes department identifiers, helping with instance categorization.
- **Generates unique names**: Reduces manual effort in creating unique names, avoiding potential name conflicts.

**Requirements**  
- Python 3.x
- No external dependencies (uses built-in libraries `random` and `string`)

**How to Run**  
1. Clone or download this script.
2. Open a terminal/command prompt and navigate to the script directory.
3. Run the script:
   `python ec2_namegen.py`

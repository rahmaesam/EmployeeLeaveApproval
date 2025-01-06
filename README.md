# Leave Request Automation  

This repository contains an RPA workflow built using UiPath to automate the employee leave request approval process. The project leverages UiPath's REFramework for scalability and error handling, ensuring a reliable and efficient automation solution.  

## Features  
- **Automated Email Processing**: Fetches leave requests from emails and extracts relevant data.  
- **Excel File Handling**: Processes leave request data stored in Excel files for validation and approval.  
- **Approval Status Update**: Updates the leave request status in a central repository after processing.  
- **Scalability**: Designed using the REFramework to handle varying workloads and ensure error recovery.  

## Process Overview  
1. **Email Data Fetching**  
   - Connect to the employee inbox.  
   - Extract emails containing leave requests and parse the data.  

2. **Data Validation**  
   - Load and validate data from the Excel file to ensure completeness and accuracy.  

3. **Approval Process**  
   - Match leave requests against predefined rules or policies.  
   - Update the status of approved or rejected requests.  

4. **Output Generation**  
   - Save the processed leave request data with updated statuses to an output file or database.  

## Requirements  
- UiPath Studio with REFramework template.  
- Access to an email account containing leave requests.  
- Input file: Leave request data in Excel format.  

## Setup and Execution  
1. Clone this repository to your local system.  
2. Open the project in UiPath Studio.  
3. Configure email settings and Excel file paths in the project configuration file.  
4. Run the automation.  

## Output  
- An updated Excel file with the leave request statuses (Approved/Rejected).  
- Log files for monitoring and troubleshooting.  

## Benefits  
- Reduces manual effort in processing leave requests.  
- Ensures consistency and accuracy in approvals.  
- Scales efficiently with the REFramework design.  

## Contact  
For any questions or support, feel free to raise an issue in this repository or contact the author.  

---

This project demonstrates efficient use of UiPath for automating routine business processes, making it an ideal solution for HR operations.

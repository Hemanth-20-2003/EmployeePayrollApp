# EmployeePayrollApp
## UC1: Employee Registration
This use case allows a new employee to register in the payroll system by entering validated personal and salary information. The system performs input validation using regular expressions for fields like email, phone number, and employee ID, then creates an Employee object with securely stored credentials. This demonstrates encapsulation, constructor overloading, and object composition while ensuring data integrity and structured employee management.

## UC2: Employee Authentication & Login
This use case authenticates registered employees using secure credential verification. The system validates the username and hashed password, creates a session on successful login, and grants access to the appropriate dashboard based on user role. It demonstrates inheritance, polymorphism, and secure authentication practices while ensuring role-based access control.

## UC3: Payslip Generation
This use case generates a detailed monthly payslip for an employee by calculating salary components such as earnings, deductions, and net payable amount. The system uses object composition and aggregation to structure payroll data and applies calculation logic to produce a formatted payslip. It demonstrates dynamic salary processing and reusable payroll component modeling.

## UC4: Payslip Print / Download
This use case allows employees to generate a downloadable or printable copy of their payslip. The system creates a safe copy of the payslip object using cloning, generates a unique file name, and saves it using file operations without modifying the original data. This demonstrates object comparison, immutability concepts, and file handling for secure document generation.

## UC5: Dashboard Display
This use case displays a personalized payroll dashboard for authenticated employees. The dashboard presents key information such as recent payslips and year-to-date earnings by processing payroll data through collections and interfaces. It demonstrates interface implementation, runtime type handling, and structured data presentation.

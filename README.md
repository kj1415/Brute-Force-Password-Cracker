This is a simple Python script that allows users to attempt to gain access to a password-protected file. It supports Word documents (.docx) and Excel spreadsheets (.xlsx). Users need to provide the directory path of the file they want to crack and the path to a text file containing a list of passwords to try.

Prerequisites:
   To run this script, ensure you have the following:

      Python 3.x installed on your system.
      The docx and openpyxl Python libraries installed.
      
Usage:
  1. Clone this repository or download the script file to your local machine.
  2. Open a terminal or command prompt.
  3. Navigate to the directory where the script file is located.
  4. Run the following command:
                
          python file_password_cracker.py
          
  5. You will be prompted to enter the path to the file you want to crack and the path to the text file containing the password list.
  6. The script will attempt to decrypt the file using each password in the list. If a correct password is found, it will display "Access granted" along with the password. If the password is not found, it will display "Access denied".

Supported File Formats:

  Word documents (.docx)
  Excel spreadsheets (.xlsx)

Note:

  This script is intended for educational purposes only to understand the concept of brute force attacks on password-protected files.
  Attempting to crack passwords without proper authorization is illegal and unethical.
  Use this script responsibly and respect the privacy and security of others. Always obtain proper consent before attempting to access someone else's files.

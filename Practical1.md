1. Shell Script to Print System Information
-> (a)Create a file named system_info.sh:
   ![Screenshot 2025-03-18 225232](https://github.com/user-attachments/assets/49335da0-4d54-4a88-944c-539c21a82e46)

 
   (b)Make the script executable:
      chmod +x system_info.sh

   (c)Run the script:
      ./system_info.sh

3. Shell Script to Perform Basic Mathematical Calculation
-> (a)Create a file named calc.sh:

(b)Make the script executable:
chmod +x calc.sh

(c)Run the script:
./calc.sh

3. Use Redirection Operators to Store Output of Commands
-> (a)Redirect stdout to a file:
      ls > output.txt

   (b)Append output to an existing file:
      date >> output.txt

   (c)Redirect stderr to a file:
      ls nonexistentfile 2> error.txt

   (d)Redirect both stdout and stderr to a file:
      ls . nonexistentfile &> all_output.txt

   (e)Pipe output to another command:
      cat file.txt | grep "keyword"

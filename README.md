FILE COMPRESSION SCRIPT

This Python script allows users to compress files and folders into various compressed file formats such as zip, tar, and tgz. It provides a user-friendly interface to select the folder to compress and the desired compression format.

How the Script Works:
1. The script imports the os, shutil, and tarfile modules. os is used for interacting with the operating system, shutil for file operations and archiving, and tarfile for creating tar archives.
2. It defines a function called compress_folder that takes two parameters: folder_path (the path of the folder to compress) and compression_format (the desired compression format, including 'zip', 'tar', and 'tgz').
3. Inside the function, it generates the current date and constructs the output file name based on the folder name and the current date if the compression format is 'tgz'.
4. It then compresses the folder based on the selected compression format using appropriate methods from shutil or tarfile.
5. If the compression format is not supported, it prints a message indicating that the compression format is unsupported.
6. The script prompts the user to input the path of the folder to compress and choose the desired compression format.
7. It then calls the compress_folder function with the provided inputs.

How to Run the Script:
1. Clone the repository or download the script file (compress.py).
2. Ensure you have Python installed on your system.
3. Run the script by executing the "python compress.py" command in your terminal or command prompt.
4. Follow the on-screen instructions to select the folder to compress and choose the compression format.

Group Members:
1. 
2. Munezero Eliane <e.munezero@alustudent.com>
3. John Akech  <j.akech@alustudent.com>
4. Ange Mukundente <a.mukundent@alustudent.com>

# Linux Command Practice Assignment
1. Creating and Renaming Files/Directories
   
  Commands:

  mkdir test_dir

  cd test_dir

  touch example.txt

  mv example.txt renamed_example.txt

  Explanation:
  
  - Creates a directory `test_dir`, enters it, creates an empty file `example.txt`, and renames it to `renamed_example.txt`.
  
2. Viewing File Contents
   
  Commands:

  cat /etc/passwd
  
  head -n 5 /etc/passwd
  
  tail -n 5 /etc/passwd
  
  Explanation:
  
  - `cat` shows full file, `head` shows first 5 lines, `tail` shows last 5 lines.
  
3. Searching for Patterns
   
  Commands:
  
  grep "root" /etc/passwd
  
  Explanation:
  
  - Searches and displays lines in `/etc/passwd` that contain the word 'root'.
  
4. Zipping and Unzipping
   
  Commands:

  zip -r test_dir.zip test_dir

  mkdir unzipped_dir

  unzip test_dir.zip -d unzipped_dir

  Explanation:

  - Compresses `test_dir` into a zip and extracts it to `unzipped_dir`.
  
5. Downloading Files
   
  Commands:

  wget https://example.com/sample.txt

  Explanation:

  - Downloads a file from a URL using wget.
  
6. Changing Permissions
   
  Commands:

  touch secure.txt

  chmod 444 secure.txt

  Explanation:

  - Creates a file `secure.txt` and changes its permissions to read-only for all.
  
7. Working with Environment Variables
   
  Commands:

  export MY_VAR="Hello, Linux!"
  
  echo $MY_VAR
  
  Explanation:
  
  - Sets and prints a new environment variable.

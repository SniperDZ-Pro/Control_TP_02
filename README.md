
### Challenge 1 Filesystem Navigation & File Basics

1. From your home, create the directory tree `PracticeExam/{scripts,logs,configs}`.  
2. Inside `configs`, create an empty hidden file named **.draft** and display it.  
3. With `cat`, create **notes.txt** in `logs` containing exactly:
   ```
   Mastering Linux permissions is essential.
   ```  
4. Show results.



### Challenge 2 Symbolic `chmod` Basics

You’ve written a script `backup.sh` in `scripts`.

1. Grant yourself (the file’s owner) **read, write, execute**; give the *group* **read & execute**; give *others* **no rights** – *using the symbolic form* of `chmod`.  
2. Display the new permissions.  




### Challenge 3 Advanced Octal `chmod`

A shared research area must enforce group collaboration while preventing permission creep.

1. Create a directory **ResearchData** under `PracticeExam` (create it if it does not exist) and move **draft.pdf** inside it.
2. Inside **ResearchData**, apply octal mode  (`rw-r-----`) to **draft.pdf** with `chmod`.
3. Display the results.



# DAT250: Software Technology Experiment Assignment 2

### Technical Problems
I had a lot of trouble installing the Derby database. I downloaded it 3 times before everything was as it should. 
The things I had to change  to make it work was: update my Java SE to a newer version and download the correct Derby
link/version.

### Experiment 1 and 2
Here is the link to the experiments. I put everythig in one project, just in different modules. 
<https://github.com/puj009/dat250-jpa-example>

### Inspecting the databases
Here are some screenshots of the first database created by experiment 1, part 1. 
The database that was created here was testdb. Used the command **show tables;** to show all of the tables after connecting
to the database. Ignoring all the SYS table_schemas, the **Todo** was the one I created.
![The table](\Users\solma\OneDrive\Documents\UiB\Dat250\Assignment\2\tables.png)
Then selected that table to see what it contained. Did this with: **select * from TEST.TODO;**
![Todo](\Users\solma\OneDrive\Documents\UiB\Dat250\Assignment\2\select.png)

Nothing to inspect in part 2 of experiment 1 or experiment 2. 

### Pending issues
I did not manage to resolve the problems I got from part 2 of experiment 1. I got error after error and do not know
what I did wrong. Even tho I think I have everything needed and did just as the tutorial told me it still fails. 
The same problem happened for experiment 2. 
This is the latest error message:
![The error](\Users\solma\OneDrive\Documents\UiB\Dat250\Assignment\2\error.png)

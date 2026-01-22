Here is a table containing some useful bash commands that you are going to use very frequently in bioinformatic workflows:

| command                    | function                                                                                                                                                                                                                                                           |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `ls directory`             | The `ls` function is called on a folder/directory. It outputs a list of files and folders that are contained in the directory.                                                                                                                                     |
| `cd directory`             | `cd` is short for change directory and lets you go to the directory mentioned in the command. The directory that you choose to go to should be present in the current directory. You can check for all the current directories present by just using `ls` command. |
| `pwd`                      | Outputs the path of directory that you are currently in                                                                                                                                                                                                            |
| `cd ..`                    | This command is similar to the back button on Google Chrome or the file explorer. It lets you go back to a folder.                                                                                                                                                 |
| `cd`                       | This is the last iteration of `cd` commands. This simply takes you back to the home directory                                                                                                                                                                      |
| `rm file/ rm -r directory` | `rm file` deletes a single file, but won't delete the. folder. To delete a folder, add the 'r' flag to your command like `rm -r directory`. Note that `rm -r` commands will delete all the files so it should be used with CAUTION!                                |
| `mkdir directory`          | `mkdir genomes` will make a folder named genomes in the current directory.                                                                                                                                                                                         |

We are going to practice some of these commands using the shared directory in our hpcc account. Reminder when you log into the UCR hpcc you are automatically logged onto the home directory which should have a bigdata folder and shared folder. 
shared folder is common to all the phd students and undergrads. By default everyone in the lab have read and writing permissions to all files and folders in the home directory. Using the `cd` command move to the shared directory and investigate it using `ls` command.

Q1. What files and folders are present in shared directory?

Were you able to locate a folder called "Ava_pedigree_wildspecies" in the shared directory? If yes then use `cd` again to move into to Ava_pedigree_wildspecies folder. Investigate this folder using `ls` command.

Q2. Using `mkdir` command make following 6 folders in Ava_pedigree_wildspecies folder:
1) P_reticulata
2) M_bifurca
3) P_gracilis
4) P_infans
5) P_prolifica
6) P_pesidionis

The folders you made for question 2 are names of fish species whose genomes we are going to analyze. We are going to copy and paste genome files in each of these folder for next week's assignment. 
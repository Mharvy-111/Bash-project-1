# Bash Basic Project - Project 1

## Author
Marvellous Badmus

## Project Description
This project demonstrates basic Bash command-line operations.  
The tasks include creating folders, downloading files, moving and deleting files, searching sequences in a `.fna` file, and extracting information from a `.gbk` file.

All commands are run directly in the terminal.

---

## Steps Overview
1. Print your name and create a personal folder.  
2. Create a `biocomputing` folder and download required files (`.fna` and `.gbk`).  
3. Move the `.fna` file to your personal folder and delete duplicate `.gbk` files.  
4. Check whether the `.fna` file is mutant or wild type by searching for the `tatatata` sequence.  
5. If mutant, save the matching lines to a new file `mutant_sequences.txt`.  
6. Extract information from the `.gbk` file:
   - Number of lines (excluding header)
   - Sequence length (from `LOCUS`)
   - Source organism (from `SOURCE`)
   - Gene names (from `/gene=` tags)
7. Save your command history to `projectbasic_commands.txt`.  
8. List files in both folders to verify results.

---

## Key Commands
- `echo`, `mkdir`, `cd`, `wget`, `mv`, `rm`, `grep`, `tail`, `wc`, `awk`, `ls`, `history`, `clear`

---

## Expected Output
- Folder structure: `~/Marvellous` and `~/biocomputing`  
- Identification of mutant or wild type `.fna` file  
- `mutant_sequences.txt` file if mutant  
- `.gbk` file info: line count, sequence length, source organism, gene names  
- `projectbasic_commands.txt` containing commands used

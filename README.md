# Bash Notes

Bash Notes is a simple bash script for taking quick notes in your terminal.

## Installation
Download the script, make it executable, and put it into your path. 

```bash
git clone https://github.com/billyrigdon/Bash-Notes.git
cd Bash-Notes/
chmod +x note
sudo cp note /usr/bin/note
```

## Usage
Bash Notes creates a note file named with the current date and saves them inside of ~/.notes for ease of use if needed at a later time.

Calling it without any arguments will print the notes for the day in a numbered list. 

You can call 'note \<notes to add\>' to add a note to the note file.

You can also delete a specific line with 'note -d \<line number\>' or erase the current date's note file with 'note -ef'

```bash
note #Prints all notes from the current date
note This is a note #Adds 'This is a note' to the current date's note file
note -d 21 #Deletes line 21 from the current date's note file
note -ef #Erases the current date's note file 
```

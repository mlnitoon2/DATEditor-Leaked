# How to Use the DAT Decompiler

## Requirements:
- Latest version of Python installed.

## Steps:

### 1. Open Command Prompt (CMD)
Open a command prompt window and navigate to the folder where the script is located.

### 2. Locate the DAT File
Get a DAT file from the following location:  
`C:\Users\Your Name\AppData\LocalLow\Big Blue Bubble Inc\My Singing Monsters\1`  
Place this DAT file in the same folder as the script.

### 3. Decompiling the DAT File
In the command prompt window, type the following command:

```bash
python dat.py datname.dat
```

Replace `datname.dat` with the actual name of the DAT file you placed. This will decompile the file and produce an unobfuscated XML.

### 4. Editing the XML File
You can now edit the XML file as needed. Some things you can change:
- Island names
- Monster prices
- Add a shop to Gold Island
- Change monster files, etc.

### 5. Recompiling the XML File
Once you've made your changes, recompile the file using this command:

```bash
python dat.py decompiledxml.xml
```

This will produce a new DAT file that you can place back into the original MSM folder you got the DAT file from.
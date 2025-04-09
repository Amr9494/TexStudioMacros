# TexStudioMacros
Some macros for TexStudio that helps to fast write especially in math mode. Also, a MATALB script to automate the macro files generation.

## How to Use

### Import Macros into TeXstudio

1. Open TeXstudio.
2. Navigate to `Macros` → `Edit Macros`.
3. Click `Import` and select the `.txsMacro` files from the `texstudio_macros` folder.
4. Restart TeXstudio to apply the new macros.
5. If you copy-past the macros to the texstudio macro file path `Users/user_name/AppData/Roaming/texstudio/macros`, you have to do that while texstudio is closed, otherwise, the macros will be overwritten. 

### 2. Customize with MATLAB

The MATLAB script `generate_macros.m` creates `.txsMacro` files based on your own definitions. You can modify the current triggers or add your own ones. 

## Notes
- Most of macros are triggered automatically in math mode. However, to trigger math mode,you need to use `mm`+`tab` or `mt`+`tab`.
- The first 16 **non-math** macros are triggered by `tab` key to avoid confusion.

## Request 
It will be good if the script is converted to python also

## Finally 
You are free to modify or completely change whatever you like.
This work was inspired by [LatexSuit](https://github.com/artisticat1/obsidian-latex-suite?tab=readme-ov-file#cheatsheet) 
The gif credit is for them  
  
![demo (1)](https://github.com/user-attachments/assets/22a2f051-94d2-45c7-b342-0f7b6524c65a)

# SN-pen
A script to change default pens in SMART Notebook when told that you cannot and some files ripped from SMART Notebook

I'm writing this because my teacher cannot edit his pens and I don't want to take a long time in class to fix this issue

All that should be needed is an internet connection, A little bit of free space, and read/write permissions for this to work on Windows 10

Open command prompt by following these steps:
1. Press Win+R to open the run window
2. Type 'cmd'
3. press Enter

Simply input this one-liner into command prompt and it will do the rest:

cd %HOMEPATH%/Downloads && curl -O https://raw.githubusercontent.com/DylTrout/SN-pen/main/script.bat && script.bat && echo done

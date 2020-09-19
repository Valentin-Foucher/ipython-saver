# IPython Saver

This is a tool that will save your IPython sessions for you.

First fork this repository and clone it where you usually launch IPython.

Just launch this command, adding or not those optional arguments:
```bash
./start_ipython.sh -n <storing-directory> -s <script-to-import>
```
- storing-directory: directory where will be stored the session (common by default) 
- script-to-import: if you supply the path to a python script here, it will be played before the session starts

After your session ends, it will be stored in `sessions/<storing-directory>`, and you can then freely reimport it another time.


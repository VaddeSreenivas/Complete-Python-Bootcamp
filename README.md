To activate environment use below steps:
1. Open Terminal and select cmd prompt not powershell
2.Anaconda install in your machine
3. use this command : conda create -p venv python==3.12

4. Step 1: Run conda init cmd.exe
Open Anaconda Prompt (not regular CMD) — this is important!
You can find it by searching for "Anaconda Prompt" in the Start menu.
In the Anaconda Prompt, 
run: conda init cmd.exe
After it runs successfully, close all terminals, including CMD and Anaconda Prompt.
✅ Step 2: Reopen Command Prompt (CMD) in Visual studio
Now, open a new Command Prompt window.
Run:
conda activate
conda activate "C:\Users\PC\Documents\GenerativeAI Complete Course\COMPLETE-PYTHON-BOOTCAMP\venv"


If that works and you see the base environment activated ((base) appears), then you're good.
I'm able to see like this :
(C:\Users\PC\Documents\GenerativeAI Complete Course\Complete-Python-Bootcamp\venv) C:\Users\PC\Documents\GenerativeAI Complete Course\Complete-Python-Bootcamp>


To run the Jupiter notebook use this command
Run : pip install ipykernel

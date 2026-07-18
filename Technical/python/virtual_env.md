# Virtual Environments (venv) - 17/7/26

### What is it?
A virtual environment is an isolated self-contained directory that 
contains a specific Python installation and its own set of additional packages. 

### Why do we need it?
To avoid dependency conflicts. If Project A needs Django version 3.0, 
and Project B needs Django version 5.0, installing them globally breaks 
one of the projects. Virtual environments keep them completely separate.

### Key Commands
- **Create:** `python -m venv myenv`
- **Activate (Mac/Linux):** `source myenv/bin/activate`
- **Activate (Windows):** `myenv\Scripts\activate`
- **Command Prompt (Windows):** `.\env\Scripts\activate.bat`
- **Bypass Windows:** `powershell -ExecutionPolicy Bypass -File .\myenv\Scripts\Activate.ps1`
- **Deactivate:** `deactivate`

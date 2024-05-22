```powershell
# Process Management
# List all processes
Get-Process

# Start a new process (e.g., Notepad)
Start-Process -FilePath "notepad.exe"

# Service Management
# List all services
Get-Service

# Start a service (e.g., Windows Update)
Start-Service -Name "wuauserv"

# Event Logging Management
# Read system event log
Get-WinEvent -LogName "System" -MaxEvents 10
```

## Student request 2024:

- [ ] Automate: Suspend users after a set amount of time

- [ ] Rights? (Export or set?) 

- [ ] Read/write csv files with powershell

- [ ] Script that take the payroll. And compare it in AD for users --> then update, add, suspend

- [ ] Script för använda behörigher, program paketering 

- [ ] Git, lägg up .md. Push -pull. Eleverna skapar konton.
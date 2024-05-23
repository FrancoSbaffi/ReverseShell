# Reverse Shell

Python Client-Server script to establish a reverse connection between both machines (target machine, attacking machine).

To use this script, run the attacker.py script from the attacking machine. It will prompt the user to enter a command to send to the target machine, where it will be executed using the subprocess library. Simultaneously, the output from the target machine will be received back to the attacking machine, showing the result of the executed command.

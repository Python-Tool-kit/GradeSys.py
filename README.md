# GradeSys.py
Grade system with python

<img width="1280" height="800" alt="Screenshot From 2026-08-05 10-42-00" src="https://github.com/user-attachments/assets/5c773f81-436b-438e-a384-c19edaf0bbd7" />

<br><br>

<img width="1920" height="1031" alt="Screenshot From 2026-08-05 10-35-45" src="https://github.com/user-attachments/assets/f5177d29-a7db-4f27-af40-e748f4364e2e" />
<br><br>


```

# This program takes the marks of a student as input and outputs the corresponding grade based on the following criteria:

#Banner

Red = '\033[31m'  # Red color
Green = '\033[32m'  # Green color
cyan = '\033[36m'  # Cyan color
Yellow = '\033[33m'  # Yellow color
reset = '\033[0m'  # Reset color


print(cyan + r""" 

 ██████╗ ██████╗  █████╗ ██████╗ ███████╗    ███████╗██╗   ██╗███████╗
██╔════╝ ██╔══██╗██╔══██╗██╔══██╗██╔════╝    ██╔════╝╚██╗ ██╔╝██╔════╝
██║  ███╗██████╔╝███████║██║  ██║█████╗      ███████╗ ╚████╔╝ ███████╗
██║   ██║██╔══██╗██╔══██║██║  ██║██╔══╝      ╚════██║  ╚██╔╝  ╚════██║
╚██████╔╝██║  ██║██║  ██║██████╔╝███████╗    ███████║   ██║   ███████║
 ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝ ╚══════╝    ╚══════╝   ╚═╝   ╚══════╝
                                                                         """ + reset)







#variable
marks = 0

#user input
marks = int(input("Enter your marks: "))

#conditional statements

if marks >= 90:  # Grade A
    print(f"{Green}Congratulations! You have scored Grade A with {marks} marks.{reset}")
elif marks >= 80:  # Grade B
    print(f"{Green}Congratulations! You have scored Grade B with {marks} marks.{reset}")
elif marks >= 70:  # Grade C
    print(f"{Green}Congratulations! You have scored Grade C with {marks} marks.{reset}")
elif marks >= 60:  # Grade D
    print(f"{Green}Congratulations! You have scored Grade D with {marks} marks.{reset}")
elif marks >= 50:  # Grade E
    print(f"{Green}Congratulations! You have scored Grade E with {marks} marks.{reset}")
else:
    print(f"{Red}Sorry, you have failed with {marks} marks.{reset}") # Failing grade.


```

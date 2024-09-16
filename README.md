# Python Creating Webpage Timer Function
### Requirement:
- **Objective**: Create a countdown timer for an online reservation system, which reminds users about their reservation time and prints a timeout message when the time expires.
- **Duration**: The timer should count down from a total of 600 seconds (10 minutes) and only print specific messages during the last 10 seconds.
- **Print Messages**:
  - At 5 minutes remaining: Print `Place your reservation soon! 5 minutes remaining.` instead of showing the integer.
  - At 2 minutes remaining: Print `Don't lose your seats! 2 minutes remaining.` instead of showing the integer.
  - At 0 minutes remaining: Print `User timed out.` instead of showing the integer.

### My Python Code:
``` python
from time import sleep
mins = 10
sec = mins * 60

while sec >= 0:
    if sec <= 10:
        if sec == 5:
            print('Place your reservation soon! 5 minutes remaining.')
        elif sec == 2:
            print('Don\'t lose your seats! 2 minutes remaining.')
        elif sec == 0:
            print('User timed out.')        
        else:
            print(sec)
    else:
        # No output for the time before the last 10 seconds
        pass # Placeholder for future code
    sec -= 1 
    sleep(1)  
```
### Result:
![image](https://github.com/user-attachments/assets/19ae70ea-6a91-4e3f-bcf1-b0040df5766f)

Thank you for stopping by, and I'm pleased to connect with you, my new friend!

**Please do not forget to FOLLOW and star ⭐ the repository if you find it valuable.**

Wish you a day filled with happiness and energy!

Warm regards,

Hien Moon | [Visit My Blog](https://hienmoon.com/?utm_source=github&utm_medium=readme)

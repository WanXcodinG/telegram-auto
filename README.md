# Telegram Automation Script

This script automates tasks in the Telegram desktop application, including referral processes, creating usernames, and solving captchas. 

## Requirements

- Python 3.x
- `pyautogui`
- `requests`
- `faker`
- `termcolor`

You can install the required packages using:
```bash
pip install pyautogui requests faker termcolor

python all3.py

Enter coordinates, delay, click type, and description (x y delay [left/right] description) one by one. Type 'done' to finish:

- {EXAMPLE coordinat get_query}
90 50 2 left type @UEEx_Miner_bot
138 107 2 left klik bot
302 1006 2 left klik menu
393 925 2 left klik /start
443 881 2 left klik start now
451 600 10 left klik ok buka bot
300 452 2 left press f12
512 147 2 left klik application
214 344 2 left klik link session
538 527 2 right klik tgweb
636 546 2 left klik copy value
842 1055 2 left klik notepad
0 0 3 left ctrl + v
0 0 3 left lakukan enter
436 838 2 left kembali ke bot
486 201 2 left tutup bot


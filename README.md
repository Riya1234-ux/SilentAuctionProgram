# 🕵️ Silent Auction Program (Python)

This is a simple command-line based Silent Auction program built in Python. It allows multiple users to place secret bids, and at the end, reveals the highest bidder and the winning bid amount. It's ideal for small-scale events or as a beginner Python project to understand dictionaries, loops, and basic input/output.

---

## 🚀 Features

* Accepts multiple bidders with hidden bid amounts
* Uses Python dictionaries to store user data
* Automatically determines the highest bid
* Clean and user-friendly CLI
* Easily customizable

---

## 🧠 How It Works

1. The program welcomes users and prompts for their name and bid amount.
2. After each bid, the screen is cleared to keep bids hidden.
3. Once bidding is complete, the program announces the winner and their bid.

---

## 🛠️ Technologies Used

* Python 3.x
* os module for screen clearing
* Basic Python constructs: loops, functions, dictionaries

---

## ▶️ Getting Started

### Prerequisites

* Python 3 installed on your system
* A terminal or command prompt

### Run the Program

bash
python silent_auction.py


---

## 📄 Sample Output


Welcome to the Silent Auction Program.
Enter your name: Alice
What's your bid?: $120
Are there any other bidders? Type 'yes' or 'no': yes

(Next bidder...)

And the winner is: Alice with a bid of $120!


---

## ✏️ Code Structure

python
from replit import clear  # or os.system('cls'/'clear')
auction_data = {}

def find_highest_bidder(bidding_record):
    # logic to find highest bid


---

## 📌 Notes

* For platforms that do not support clear(), replace it with:

  python
  import os
  os.system('cls')  # For Windows
  os.system('clear')  # For macOS/Linux
  
* This is a basic version and does not include input validation or error handling.

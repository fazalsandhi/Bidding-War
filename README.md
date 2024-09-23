
# Bidding War

A simple command-line program where participants can place their bids, and the highest bidder wins. This project demonstrates basic Python concepts such as dictionaries, loops, and functions.

## Features

- Each participant can enter their name and bid amount.
- The program checks if there are more participants.
- Once bidding is over, the program announces the highest bidder.

## Usage

1. Clone the repository.
   ```bash
   git clone https://github.com/fazalsandhi/Bidding-War.git
   cd Bidding-War
   ```
   
2. Run the program.
   ```bash
   python main.py
   ```

3. Follow the prompts to enter your name and bid amount.

4. After all participants have placed their bids, the highest bidder will be announced.

## Example

```
What is your name?: Alice
What is your bid?: $200
Are there any other bidders? Type 'yes' or 'no'.
yes

What is your name?: Bob
What is your bid?: $250
Are there any other bidders? Type 'yes' or 'no'.
no

The winner is Bob with a bid of $250.
```

## Files

- `main.py`: Contains the main logic for collecting bids and determining the highest bidder.
- `art.py`: Provides the logo displayed when the program runs.

## Logo

The program includes a simple auction hammer logo displayed at the start of the program, stored in the `art.py` file.

```
                         ___________
                         \         /
                          )_______(
                          |"""""""|_.-._,.---------.,_.-._
                          |       | | |               | | ''-.
                          |       |_| |_             _| |_..-'
                          |_______| '-' `'---------'` '-'
                          )"""""""(
                         /_________\
                       .-------------.
                      /_______________\
```

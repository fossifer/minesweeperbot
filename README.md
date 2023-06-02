# minesweeperbot
A Telegram Minesweeper game bot, currently runs as [@P4MinesweeperBot](https://t.me/P4MinesweeperBot), which is a clone of [@mine_sweeper_bot](https://t.me/mine_sweeper_bot) and [@archcnmsbot](https://t.me/archcnmsbot).

## New Features
* Guess-free map generation if possible - No more painful 50/50 at the end!
* Fine-tuned reward/punishment curve based on 3bv (map difficulty)
* Enhanced message display with better user experiences
* And more!

## Build and Run
```
pip install -r requirements.txt
TOKEN='<YOUR BOT TOKEN HERE>' python tgmsbot.py
```

## Acknowledgement
This project adapted codes from the following two repositories:
* https://git.jerryxiao.cc/Jerry/tgmsbot
* https://github.com/gamescomputersplay/minesweeper-solver
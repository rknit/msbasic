# TbO2 msbasic

  A demo project for the TbO2 6502 microprocessor emulator.
This project is inspired from [Ben Eater 6502 videos](https://www.youtube.com/watch?v=LnzuMJLZRdU&list=PLowKtXNTBypFbtuVMUVXNR0z1mu7dp7eH).
  You can run the project by referring to the [How to Run](#how-to-run) section.

## How to Build

  It should not be required to build the project yourself in order to run the project.
You can refer to [How to Run](#how-to-run) section on how to run. If you still want
to build the project, please refer to the requirements and instructions below.

### Requirements

- Unix system (or any system capable of running bash scripts).
- ca65 & ld65 compiler.

### Instructions

- Run [./make.sh](./make.sh)
  (You may need to allow execution for the script to work).
- Run `cargo build` in the console.

## How to Run

- Run the command ```cargo run --release``` in the console,
  or run the executable found in the target directory.
- Character `\` should be printed to the console.
  This means that you are now running Wozmon using TbO2 emulator.
- Send the following message (after '>' is shown on the console) to start up [msbasic](https://github.com/mist64/msbasic).
- To quit msbasic, use **CTRL+D** key combination.

```Text
\
> 8000 R
8000: 4C
MEMORY SIZE? > [HIT ENTER]
TERMINAL WIDTH? > [HIT ENTER]

 31743 BYTES FREE


COPYRIGHT 1977 BY MICROSOFT CO.

OK
>
```

Congrats! You are now in MS BASIC!

A text-based hacking simulation game built in Python, where the player takes on contracts to hack fictional computers, manage resources, and complete objectives without getting caught.

About the project

This was my first personal programming project, built while learning Python. I wanted to challenge myself by building something playable from scratch, without following a tutorial step by step. Looking back at the code now, it's clear I was still getting familiar with object-oriented programming at the time — class structure and data handling evolved a lot as the project grew, and there's plenty I'd approach differently today. I'm keeping the project as-is as a snapshot of where I started.

How it works
You play as a hacker who takes on contracts against randomly generated target computers.
Each computer has a difficulty level (Easy / Medium / Hard), which determines its integrity (health), number of files, bank balance, and the type of contract (e.g. Data Theft, Virus Installation, Assassination, Identity Theft, Sabotage, Cyber Attack).
Computers contain a mix of important, decoy, and bonus files, which you need to identify, download, decode, or expose depending on the mission.
You manage a set of resources and tools: Malware, Brute Force, Viruses, DDoS, and Decoders, which can be bought in the in-game shop and used to break into systems, weaken them, or crack encrypted files.
Your core stats are Money, Honor, and Integrity (your own system's health) — completing missions earns money and can affect your honor, while getting detected can cost you integrity and money.
Missions are completed by meeting specific conditions (e.g. emptying a target's bank account, installing enough viruses, stealing and sending the right file), handled through a set of dedicated mission functions.
Running the project
Clone the repository.
Make sure you have Python installed.
Run main.py to start the game.
Status

This project is complete as a learning exercise and is not actively maintained, but issues and suggestions are welcome.

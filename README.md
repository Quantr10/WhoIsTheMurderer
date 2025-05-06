# 🕵️‍♂️ WhoIsTheMurderer: A Text-Based Adventure Game

## 🎮 Project Overview

This is a multi-checkpoint **text-based murder mystery adventure game** built in Java, inspired by the classic interactive fiction game *Zork*. The player navigates through a mysterious world by typing commands like `look`, `go`, `examine`, `take`, and more. Through these interactions, players uncover secrets, collect items, and unravel the truth—entirely through text.

This game focuses on engaging the player's imagination, mimicking the feel of reading an interactive novel, with logical command handling and object-oriented design principles.

---

## ⚙️ How to Play

Once compiled and run, interact with the game by typing commands such as:

```
look
examine knife
go north
take bottle
drop turkey
inventory
take coin from chest
put lantern in vault
help
quit
```

Each command affects the character's environment or inventory. Try exploring, picking up items, and solving the mystery.

---

## 🔧 Features

- ✅ Text-based input with command parsing
- ✅ Dynamic item and inventory handling
- ✅ World navigation with connected locations
- ✅ Support for container items
- ✅ Case-insensitive item recognition
- ✅ Robust error messages for unsupported or malformed commands
- ✅ Expandable object-oriented architecture

---

## 🧪 Example Commands

| Command                  | Description                                                        |
|--------------------------|--------------------------------------------------------------------|
| `look`                  | Displays the current location, its description, and item names     |
| `go <direction>`        | Moves the player in a valid direction (e.g., `go east`)            |
| `examine <item>`        | Describes an item in detail if found at the location               |
| `inventory`             | Lists items in the player's backpack                               |
| `take <item>`           | Picks up an item and adds it to inventory                          |
| `drop <item>`           | Drops an item from inventory into the current location             |
| `take <item> from <container>` | Removes item from a container item at the current location    |
| `put <item> in <container>`   | Places item from inventory into a container item              |
| `help`                  | Displays all available commands                                    |
| `quit`                  | Exits the game                                                     |

---

## 🛠️ Technologies Used

- **Java** (JDK 17 or later)
- **Object-Oriented Programming** principles
- **Text-based input** via `Scanner`
- **ArrayLists & HashMaps** for item and world management

---

## 📌 Installation & Running

1. Clone the repository or download source files.
2. Compile all Java files:
   ```
   javac *.java
   ```
3. Run the game:
   ```
   java Driver
   ```

---

## 📣 Credits

Created by *Quan Tran* and partners as part of a semester-long programming assignment.

Inspired by **Zork**, one of the earliest interactive fiction games.

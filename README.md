# Discord Bot Assignment Tracker
As a student, I and many others have many different assignments, exams, and deadlines to keep track of. It is easy to forget some of these things, and remembering to do them can be difficult. This discord bot that allows you to keep track of different assignments and deadlines, and can remind you at the beginning of the day so you know what you have to do for that day.

## Eisenhower Matrix

|                         | **Urgent** | **Not Urgent** |
|-------------------------|------------|----------------|
| **Important** | **Do (MVP)**<br><br>- Allow users to add an assignment and due date.<br>- Store assignments and due dates.<br>- Ping users every day with assignments due that day.<br>- Allow users to remove assignments. | **Schedule (V2.0+)**<br><br>- Allow users to add descriptions to assignments.<br>- Allow users to add recurring assignments (e.g., CS193 due every Sunday at 11:59 PM).<br>- Allow users to edit assignments and due dates.<br>- Allow users to mark assignments as complete.<br>- Add categories for different types of due dates (assignments vs. exams). |
| **Not Important** | **Delegate (Use a Library)**<br><br>- Use the Discord API to interact with Discord.<br>- Use premade schedulers to schedule the Discord bot.<br>- Use premade file-handling tools to write and save data. | **Delete (Cut It)**<br><br>- Allow users to customize the Discord bot's output.<br>- Allow users to change the daily ping time to align with their start of day.<br>- Add complex effects, animations, or design to bot messages. |

## How it works

![System diagram](docs/Discord%20Bot%20Assignment%20Tracker%20Architecture.drawio.png)

## Tech Stack

- **Language:** for the language
- **Libraries:** JDA library to interact with Discord API, Java Time to manage dates and Java File I/O to manage reading and writing files to save data.
- **External tools:** Discord API and Discord.

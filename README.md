This workflow connects an AI-powered assistant with Google Calendar and Google Sheets to manage tasks and events through natural chat commands.

✨ Features

Chat-triggered AI agent powered by OpenAI (gpt-4o-mini)

Memory support for contextual conversations (buffered chat history)

Google Calendar integration

Create new events

Search for events within a date range

Update existing events (with search-first safeguard)

Google Sheets integration

Append new tasks with Task Name, Description, Due Date, Priority

Search for tasks by due date

Update tasks (ensuring the correct record is found first)

🛠 How it Works

Workflow starts when a chat message is received.

The AI agent interprets the request using defined system rules.

Depending on the intent:

Calendar events are created, searched, or updated.

Task entries are added, retrieved, or modified in Google Sheets.

All dates are handled in the MM/DD/YYYY format to keep consistency.

📌 Use Cases

Quickly add or update meetings in Google Calendar via chat.

Maintain a task list in Google Sheets directly from natural conversation.

Automate scheduling and task tracking without switching apps.

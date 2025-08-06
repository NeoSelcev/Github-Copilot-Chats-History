# Github Copilot Chats History

This repository stores chat histories and summaries generated from conversations with GitHub Copilot Chat Assistant.

## How to Save a Conversation Summary

**Prompt:**

Save a summary of this conversation in the repository NeoSelcev/Github-Copilot-Chats-History.
Create a new file named as follows:
`YYYY-MM-DD_HH-MM-SS_<platform>_<short-name>.md`
where:
- `YYYY-MM-DD_HH-MM-SS` is the current date and time (UTC),
- `<platform>` is the platform you’re using (e.g., iOS, browser, VS Code, etc.),
- `<short-name>` is a brief identifier for this conversation (e.g., github-repo-setup).

The file content should be:
- The filename as the title (Markdown `#` heading)
- The platform and timestamp in a bullet list
- The short name as a subheading (Markdown `##`)
- The summary of the conversation below

Commit and push the file to the main branch with the message:
`Add conversation summary: <short-name> on <YYYY-MM-DD HH:MM:SS> (<platform>)`

## How to Load a Conversation History by Topic

**Prompt:**

Load a conversation history from the repository NeoSelcev/Github-Copilot-Chats-History.
Search for a file by topic using a keyword in the filename (e.g., `<topic>`).
Return the contents of the file(s) that match the topic.

**Instructions:**
- List all files in the repository or a specific folder.
- Filter files that contain the topic keyword in their name (e.g., `platform_topic.md`).
- Display the contents of the matching file(s) for review or to continue the conversation.

## How to Update an Existing History by Topic

**Prompt:**

Update an existing conversation history in the repository NeoSelcev/Github-Copilot-Chats-History.

Steps:
1. Search for a file whose name contains the topic keyword (e.g., `<topic>`).
2. Select the correct file from the search results.
3. Update the file with new content (e.g., append new conversation summary, add a new section, or modify existing content as needed).
4. Commit and push the changes to the main branch with a commit message:
   `Update conversation history: <topic> on <YYYY-MM-DD HH:MM:SS>`

**Instructions for Content Update:**
- Clearly separate the new content from the previous content (e.g., with a date or Markdown divider).
- Ensure the update preserves the original content and structure.
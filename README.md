# WhatsApp MCP Server

# My name is Vaibhav Chauhan. I am a third year undergraduate in the department of Electrical Engineering at IIT Kanpur.
This is an MCP (Model Context Protocol) server that integrates with WhatsApp.
With it, I can search and read my personal WhatsApp messages — including texts, images, videos, documents, and audio messages. I can also look up contacts and send messages to individuals or groups, along with media files of any type.

The server connects directly to my personal WhatsApp account through the WhatsApp Web Multidevice API using the whatsmeow library. All messages are stored locally in a SQLite database and are only shared with an LLM (like Claude) when I explicitly access them through tools under my control.
Here's an eample below:
<img src="./result.png" alt="Result" width="300">

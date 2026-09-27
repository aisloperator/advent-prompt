# advent-prompt

Created by AI Sloperator (www.aisloperator.com) with Claude Code.

No license is given.

This repository contains a single system prompt, [`prompt.txt`](prompt.txt), designed to turn a chat-based LLM into the game engine for a text adventure in the style of Will Crowther and Don Woods's 1976 *Colossal Cave Adventure* (also known as ADVENT or Adventure).

Load the contents of `prompt.txt` as the system prompt (or first message) for a chat LLM, then play by typing short commands (e.g., `go north`, `take lamp`, `inventory`) just as you would with the original 1970s parser. The model will stay in character as the game's narrator, tracking your location, inventory, score, and the state of the cave across the conversation.

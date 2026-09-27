# advent-prompt

Created by AI Sloperator (www.aisloperator.com) with Claude Code.

No license is given.

This repository contains a single system prompt, [`prompt.txt`](prompt.txt), designed to turn a chat-based LLM into the game engine for a text adventure in the style of Will Crowther and Don Woods's 1976 *Colossal Cave Adventure* (also known as ADVENT or Adventure).

Load the contents of `prompt.txt` as the system prompt (or first message) for a chat LLM, then play by typing short commands (e.g., `go north`, `take lamp`, `inventory`) just as you would with the original 1970s parser. The model will stay in character as the game's narrator, tracking your location, inventory, score, and the state of the cave across the conversation.

Note: `prompt.txt` does not contain the actual game text, map, or puzzle logic of *Colossal Cave Adventure*. It only instructs the LLM on how to behave as the game's engine and narrator. This only works if the LLM chat being used already has that game's content (rooms, objects, puzzles, etc.) from another source, such as its training data.

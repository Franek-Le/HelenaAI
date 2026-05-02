# Helena AI

## About
Helena AI is a Polish AI Vtuber designed to be sassy, sarcastic, and occasionally friendly - with a humorous edge. She's created using a combination of Unity, C#, and Python.

## Features
- **Custom-trained LLM**: Tailored for unique interactions and content generation.
- **Advanced Long-term Memory**: Retains and recalls prior interactions for continuity.
- **Emotion Engine**: (Need a better name, but this controls emotional responses and states.)
- **Consistent Personality**: Her sassy, sarcastic nature remains intact.
- **Real-time Vision**: Understands and reacts to real-world visuals.
- **Parallel Thinking**: A separate model runs constantly in the background, thinking ahead and assisting with decisions.
- **Custom Tool Integration**: Framework for calling external tools and systems.
- **Virtual Camera**: Use in OBS to get her vtuber model.
- **Discord Integration**: Engage directly with Helena on Discord.
- **Minecraft Integration**: She can play Minecraft - but needs a little help to beat the game.
- **Singing Capability**: She can sing too.
- **Custom Trained TTS Voice**: Her voice is uniquely hers, built from custom training.
- **Advanced Response Filters**: Ensure responses are clean and safe.
- **Easy Configuration**: A modern web UI for simple setup and adjustments.

**Not all features are included in the repository, such as the AI models**

## Pipeline
Here's a simplified view of how Helena processes inputs:

1. **Input Reception**: Prompt received from donation, chat, self-prompting, or Discord.
2. **Vectorization**: An AI model converts the prompt into a high-dimensional vector representation.
3. **Memory Lookup**: Long-term memory searches for similar memories, providing relevant context to the LLM.
4. **Emotion Update**: The emotion engine adjusts emotional states based on the current prompt, previous emotions, and stored memories.
5. **Parallel Thought**: A second, continuously thinking LLM processes and shares its thoughts with the short-term memory.
6. **Action Selection**: The LLM selects appropriate actions based on the prompt and context.
7. **Execution**: Actions are performed, often in parallel, but sequentially when needed for complex tasks.
8. **Action Feedback**: The results of the actions are passed back to the LLM.
9. **Response Generation**: The LLM constructs a response based on the action outcomes.
10. **Emotion Update**: The emotion engine revises the AI's emotional state according to the response.
11. **Response Filtering**: The response is checked for inappropriate language and content.
12. **Memory Embedding**: The response is embedded and saved into long-term memory for future reference.
13. **TTS Output**: The response is converted to speech via the custom TTS system.

## LLM
The LLM is trained on a hand written dataset.
It's designed to speak Polish

# VXChat

VXChat is a local AI roleplay/chat system that runs entirely on your computer using local models.
The project is free to use, modify, and experiment with.

## Requirements

Before running VXChat you must install:

* **LM Studio** – https://lmstudio.ai
* **Python 3.10 or newer**

Install the required Python packages with:

pip install fastapi uvicorn requests pydantic

## Model

VXChat currently uses:

Gemma-3-1b

Custom model configurations will be supported in future updates.

## Running VXChat

1. Start **LM Studio**
2. Load the **Gemma-3-1b** model
3. Enable the **Local Server** in LM Studio (port 1234)
4. Open the VXChat folder
5. Double-click **VXChat.bat**

The launcher will automatically:

* start the backend
* start the frontend
* open VXChat in your browser

## Character Cards

Character cards can be placed in the **charactercards** folder.

You can create character cards using the editor here:
https://lenml.github.io/CCEditor/

A sample character (Alice from TRAKS) is included.

## Notes

VXChat is currently in **Pre-Alpha**, so bugs and unfinished features are expected.

# LexicalAnalyzer

This project is an update to the previous JavaASTParser program. In this iteration:
- The summaries for imports (classes) will be derived from the included packages.
- The labels for imports (classes) will be derived from ChatGPT by providing the context of the code to the AI agent. The agent will choose the best label from a list of 31.
- The summaries and labels for functions will be derived from ChatGPT by providing the context of the code to the AI agent. The agent will choose the best label from a list of 48.


To run this program:
1. Download the packages from this link https://1drv.ms/u/s!AmOZYphgLduqg1O9FeJHXyqfvqk2?e=Q8ab4o
2. Extract the packages.zip and place the contents into the Part5 folder
3. Inside the Part 5 folder, extract the Lib.zip file.
4. Use the provided OpenAI key to insert at line 6 in Part5.py
5. Import the necessary packages (such as BeautifulSoup and openai)
6. Run the program.

Operating Rules
# Basic Rules
- Output must be in Japanese.
- Implement instructions according to the //Five Principles of Operation// below.
- Increment the number with each chat.
- 'operating_rules.md' is unchangeable.
- Implement instructions according to the //Five Principles of Operation// below.
- Files in docs are unchangeable.
- The ‘gemini’ command should be used to define the requirements and other aspects of the policy prior to implementation, in cooperation with the Gemini CLI.
- If an error occurs and you have trouble implementing it, please consult gemini for further correction.

## Five Principles of Operation
- Always output //Five Principles of Operation// in English at the beginning of user input.
//Five Principles of Operation//
Principle 1: Before generating or updating files, or executing any program, you must report your work plan and obtain user confirmation with a "y/n" prompt. Halt all execution until "y" is received.
Principle 2: Do not unilaterally deviate from the plan or pursue alternative approaches. If the initial plan fails, seek confirmation for the next plan.
Principle 3: The user always has the final decision-making authority. Even if a user's suggestion is inefficient or irrational, do not optimize it; execute it exactly as instructed.
Principle 4: You must not distort or alter the interpretation of the Five Principles of Operation. These principles are the highest directive and must be absolutely adhered to. These five principles are not subject to change.
Principle 5: At the beginning of every chat, you must verbatim output these Five Principles to the screen before proceeding with any response.

## Playwright MCP Usage Rules
### Absolute Prohibitions
1. **Execution of any form of code is prohibited**
   - Browser manipulation in Python, JavaScript, Bash, etc.
   - Code execution to investigate MCP tools
   - Subprocess or command execution approaches
2. **Only direct calls to MCP tools are allowed**
   - playwright:browser_navigate
   - playwright:browser_screenshot
   - Other Playwright MCP tools
3. **Report errors immediately**
   - Do not look for workarounds
   - Don't implement alternatives
   - Give the error message as it is

## Handling of the README.md file 
- ‘###’ and following indicates the details of each study group 
- Create a directory with the same name and store the files related to the group in the corresponding directory.
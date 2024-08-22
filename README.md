## Do Terminal

Ever switched back and forth to chatgpt/google and terminal to get the correct command to execute that you don't know. Not anymore!...  Hopefully :)

Do-terminal gives the command ready to execute directly in the command terminal.

Install latest version ollama in machine (old one didn't work). Refer ollama docs: https://ollama.com/download

Use your desired model from ollama. I am using llama3.1 7b

Run: `ollama run llama3.1`. This command pulls and runs the model in your machine.

Paste the igris file in a env folder - `/usr/local/bin`(for linux systems)

Give executable permission to the file: `chmod +x igris`. Make sure you have python3 in your system :)

Now we can ask all our question in the command terminal and waste our time here instead of chatgpt :)

Try out: `igris list all the files`

PS: You can change the name of the igris file to call it anything. Have fun :)
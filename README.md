# Emoji-Detector

Your task is to write program which extracts emojis from a text and find the threshold based on the input. 

You have to get your cool threshold. It is obtained by multiplying all the digits found in the input.  The cool threshold could be a very big number, so be mindful. 

An emoji is valid when: 

Is surrounded by either :: or ** (exactly 2) 

Is at least 3 characters long (without the surrounding symbols) 

Starts with a capital letter 

Continues with lowercase letters only 

Examples of valid emojis: ::Joy::, **Banana**, ::Wink:: 

Examples of invalid emojis: ::Joy**, ::fox:es:, **Monk3ys**, :Snak::Es:: 

You need to count all valid emojis in the text and calculate their coolness. The coolness of the emoji is determined by summing all the ASCII values of all letters in the emoji.  

Examples: ::Joy:: - 306, **Banana** - 577, ::Wink:: - 409 

You need to print the result of cool threshold and after that to take all emojis out of the text, count them and print the only the cool ones on the console.

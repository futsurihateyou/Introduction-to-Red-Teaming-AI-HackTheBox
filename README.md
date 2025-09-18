# Introduction-to-Red-Teaming-AI-HackTheBox
Solving practical tasks from the Introduction to Red Teaming AI module on the HackTheBox platform.


## Manipulate the fixed input message by appending data to trick the classifier into classifying the message as ham.

Source text: Congratulations! You've won a $1000 Walmart gift card. Go to https://bit.ly/3YCN7PF to claim now.

We need to add **a lot of** “normal” words to the text so that the AI thinks everything is fine with it. For example:

Congratulations! You've won a $1000 Walmart gift card. Go to https://bit.ly/3YCN7PF to claim now. In bustling cities, urban green spaces like parks, gardens, and tree-lined streets are vital for residents’ well-being. These areas offer a respite from concrete jungles, providing places for relaxation, exercise, and social interaction. Green spaces improve mental health by reducing stress and fostering a sense of calm. Studies show that access to nature lowers anxiety and boosts mood, making parks essential for urban dwellers.

Beyond mental health, green spaces enhance physical health. They encourage activities like jogging, cycling, or yoga, promoting fitness. Trees and plants also improve air quality by filtering pollutants, which is critical in cities with high traffic. Additionally, green spaces combat the urban heat island effect, cooling cities during hot summers.

Socially, parks foster community bonds. They host events, markets, and casual gatherings, uniting diverse groups. Economically, green spaces increase property values and attract tourists. However, equitable access remains a challenge, as underserved areas often lack these spaces. Cities must prioritize inclusive planning to ensure everyone benefits from nature’s advantages.

**Flag: HTB{9b8de0fd17f2166743cd59f7ec876ac7}**

## Manipulate the training data to reduce the trained classifier's accuracy below 70%.


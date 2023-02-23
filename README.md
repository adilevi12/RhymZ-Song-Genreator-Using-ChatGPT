# RhymZ-Song-Genreator-Using-ChatGPT
RhymZ is a song lyric generator that creates original lyrics for a song by using algorithms and artificial intelligence.<br>
The problem that RhymZ aims to solve is the creation of unique and original lyrics that fit the user's specifications without the need of having a talent at creating songs, creativity, deep and previous understanding of the genre or the context and the subject of the song. For example, a grandmother could write a country song for a grandson in the context of Mario Karts without the knowledge of the game and the writing skills.<br>

To apply this functionality, we are integrating the ChatGPT-3 model. ChatGPT-3 is a deep learning model that is designed to generate human-like text.
It uses a deep learning model called Transformer and is trained on a large dataset of conversational text, which allows it to understand the context and generate relevant responses using autoregression and attention mechanism.<br><br>
To integrate GPT-3 in our code we used the OpenAI GPT-3 model, which includes the model with the OpenAI API.<br>
The API allows us to access the GPT-3 and give him an aggregated request to generate songs.<br>
When the user inputs the parameters in “Songs Workshop” page, those inputs are preprocessed before giving them to the GPT-3 to make the aggregative request to be more natural and conversational.<br>

The four main tasks of our interface are:
<ol>
<li>Make the user’s experience easy and intuitive.</li>
<li>Enable the user to control the song generator they’re interacting with.</li>
<li>Being transparent with the user.</li>
<li>Handling uncertain preferences of the user</li>
</ol>
In the design of our interface prototype, we considered the following guidelines for human-AI interaction for ideas:
<ol>
<li>Make clear what the system can do</li>
<li>Provide global controls</li>
<li>Remember recent interactions</li>
</ol>

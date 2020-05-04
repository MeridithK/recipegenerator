# Recipe Generator
Need new dinner ideas while self-quarantining? We've got you covered.

We discuss this network, as well as potential improvements, in this<a href="https://medium.com/@artneuralrecipes/creating-a-neural-network-to-generate-recipes-c204e407e61f"> blog post</a>.

<h3>Pre-Recommendations</h3>
This blog post is generally for readers of all backgrounds; basic Python knowledge and neural network experience are 
recommended but not required.
If you are interested in our project, we suggest you work with Google Colaboratory.

<h3>The Objective</h3>
In our project, we attempted to apply what we learned about Artificial Neural Networks to create a model which would provide 
suggestions based on the ingredients you already have at home.
Our goal was that, once you fed into the model a list of the ingredients at hand, it would generate a possible recipe in which 
to use them, including a list of ingredients and instructions (or close to it).

<h3>The Files</h3>
Recipe Scraper: the code we used to scrape data<br>
Training network: the code we used to train the network, using 4 128-cell LSTM layers and 8 epochs<br>
Network: <b>this is the file to play with</b>. We transferred the weights from the trained network to here, and provided example code to prompt a new recipe<br>
recipesgo1_config, recipesgo1_vocab, recipesgo1_weights: preserves training information<br>
CombinedText: our training data

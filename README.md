# Seinfeld_Script_Generation

The goal of this project is to create an LSTM Neural Network to generate a Seinfeld Script. The network was fed the five highest rated Seinfeld episodes, according to IMDB. I tested many different neural networks. A sequential network with three layers with 400 nodes each and dropout layers in between trained over 100 epochs produced the following text:

"h)\njerry: (to elaine) let me ask you a question.\nelaine: mm-hm.\njerry: you're a hostage, captured by terrorists-\nelaine: (smiling, choekding) nh. it's ouerty good. huh?\n \njerry: well, well.  \nsusan: himho. you're there and they don't have to say for yourself.\nelaine: oh, it was nike for me to be around no tomething.\njerry: (pointing) yeah. i'm aoming. i'm vellin' he didn't shake it up in the meeting?\n \n(jerry picks up the money, cousinuation to the bouiter) she's sleeping with his mother)\ngeorge"

Through this project I learned how to implement various deep learning models. Because I was running the model locally, I had to limit the amount of data I fed into my model. The next step I would like to take is to use a cloud based system like Google Cloud Analytics and feed it more data to create a more accurate model.

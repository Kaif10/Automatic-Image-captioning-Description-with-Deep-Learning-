# Automatic-Image-captioning-Description-with-Deep-Learning-

![](https://miro.medium.com/max/1400/1*UOThCj27n-ZnGM5BOrTrmg.jpeg)



## Building the model
Coming to the main model, image captioning architecture consists of three models:

A CNN: used to extract the image features
A TransformerEncoder: The extracted image features are then passed to a Transformer
             based encoder that generates a new representation of the inputs
A TransformerDecoder: This model takes the encoder output and the text data
             (sequences) as inputs and tries to learn to generate the caption.



### Short summary of model
CNN extract features >> Tranformer encoder (new representation of CNN output) >> TransformerDecoder takes (transformer encoder outputs + text data (in integer sequence format) and learns to generate captions corresponding to imgs)


![](https://github.com/Kaif10/Automatic-Image-captioning-Description-with-Deep-Learning-/blob/main/outputs.png)

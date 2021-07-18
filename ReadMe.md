<h1> Captcha reader </h1><br>
Simple OCR model that uses CNN and RNN to read captchas, based on keras <br>
- StringLookup: <br>
</t> This layer translates a set of arbitrary strings into an integer output via a table-based vocabulary lookup. <br>
https://www.tensorflow.org/api_docs/python/tf/keras/layers/experimental/preprocessing/StringLookup <br>
- RNN <br>
</t> Recurent neural network, learns based on previous inputs, feedback loop so it cla learn from memory, good for sequential data <br>
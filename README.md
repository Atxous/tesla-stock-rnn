# tesla-stock-rnn
unfinished - trial run with pytorch (I have no idea how pytorch works)

# How It Works

This data was taken from Kaggle's TSLA stock dataset, at
https://www.kaggle.com/datasets/jimschacko/tesla-inc-last-5-years-stock-historical-data
It looked at dates from 2018 to 2022. I tried to use STL in order to unseasonalize the data.
Valid loss is horrible, but the training loss is okay. This is probably best explained because
I split the data between where Tesla Stock had spiked in 2020-2021

This was one of my first "official" kind of projects. It's a basic RNN with LSTM in pytorch.
I came from Tensorflow to Pytorch, so I'm still trying to figure out how to do things.

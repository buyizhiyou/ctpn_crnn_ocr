Convolutional Recurrent Neural Network
======================================

Referring to [crnn](https://github.com/meijieru/crnn.pytorch).<br>
This software implements the Convolutional Recurrent Neural Network (CRNN), a combination of CNN, RNN and CTC loss for image-based sequence recognition tasks, such as scene text recognition and OCR. For details, please refer to [crnn](http://arxiv.org/abs/1507.05717)
##run
download a pretrained model from [Dropbox](https://www.dropbox.com/s/dboqjk20qjkpta3/crnn.pth?dl=0),put the model file into directory `data/`<br>
`python demo.py`
##dependence 
* [warp-ctc-pytorch](https://github.com/SeanNaren/warp-ctc)
* lmdb:pip install lmdb
##train
``python crnn_main.py [--param val]`` .Explore ``crnn_main.py`` for details.


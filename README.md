I can never remember any of the names of the seven dwarfs in snow white, so I created a [web-app](https://seven-dwarfs.onrender.com/) which can.



What's interesting is the data itself has about 30% of its images mislabeled, yet the prediction accuracy is much higher from testing it myself. I need to create a correct validation set first for a proper numerical test, so that is a TODO for me.



The reason for such mislabeled data is that not even google images knows which dwarf is which most of the time and my labelled images came from the front pages of those searches.



This was done with [fast.ai](fast.ai), [render](render.com), and cheeky fork of a [fast-ai render deployment template](https://github.com/render-examples/fastai-v3).

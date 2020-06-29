I can never remember any of the names of the seven dwarfs in snow white, so I created a [web-app](https://seven-dwarfs.onrender.com/) which can.



What's interesting is the data itself has most of its images mislabeled, yet the prediction accuracy is much higher than 70%! I have yet produced an accurate validation set as I personally get stumped on a few of the dwarfs, so that is a TODO for me. Once that's done, I can numerically know how good my model is.


The reason for such mislabeled data is that not even google images knows which dwarf is which most of the time and my labelled images came from the front pages of those searches.



This was done with [fast.ai](fast.ai), [render](render.com), and cheeky fork of a [fast-ai render deployment template](https://github.com/render-examples/fastai-v3).

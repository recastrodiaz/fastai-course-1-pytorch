# Practical Deep Learning for Coders (fast.ai courses), PyTorch Port

This is a PyTorch port of Rachel's and Jeremy's 1st part Machine Learning massive open online course. For the original version written in Keras 1.2.2 please see [here](https://github.com/fastai/courses).

## Acknowledgments

I would like to start by thanking Rachel and Jeremy for all the time they have put in this free online MOOC. This is by far the best practical Machine Learning course available today and it has proven to be an invaluable resource. I [wrote in my blog](https://rodrigo.red/blog/picmatix-pragmatic-machine-learning-company/) that open collaboration is an undisputed reason to the success of Machine Learning and I am convinced that the educational work Rachel and Jeremy are doing is a perfect example of this mindset. Thank you very much!

The notebooks in this repo would not be possible without @ncullen93's amazing work in [torchsample](https://github.com/ncullen93/torchsample). A high-level package that includes Keras-like training methods and many other gems.

Last but not least, I would like to thank all Keras and PyTorch maintainers and contributors for pushing the boundaries of what's possible.

## Motivation

Keras is a very well designed Machine Learning library. It does not come as a surprise that Google is making it its default API. Nonetheless, in Keras, many important details are hidden away behind easy-to-use APIs and high-level abstractions. This is perfect for when you are looking for good results quickly, but from a learning perspective, I believe we can do better. Moreover, for certain types of architectures, Keras may not be the best fit and it would make sense to learn and use a different framework.

PyTorch is the new kid on the block, promising easier to debug networks, flexible architectures, and state-of-the-art results. Who could say no to such a shiny new ML framework? 

Porting the course notebooks to PyTorch has meant a lot of hard work trying to figure out the small details (i.e. Why is my network not converging as fast as it should?) but the payoff has been an amazing learning & hands-on experience. I recommend you do the same and I hope you find value in this work.

Finally, these notebooks can also be used as a direct comparison between Keras and PyTorch. (Yet Another PyTorch vs. Keras post).

## Notebooks & Contributions

- Lesson 1 is significantly different from the original notebook as 1) I wasn't planning on making this work public when I started the course and 2) Pytorch's CNN/vision features are significantly different in that doing an exact port would be hard. 
- Lessons 2 and 3 haven't been ported to PyTorch. Feel free to submit a PR.
- Lessons 4-6 are almost line-to-line equivalents of the original notebooks with a few loose ends here and there. (such as the missing LSTM network in Lesson 5 and no Theano implementation in Lesson 6).
- Lesson 7 will be available in early June 2017.

If you have a better way of doing XYZ, please let me know through a Github issue.

## Additional Requirements

- Python 3.X
- PyTorch v0.1.12
- [Torchsample](https://github.com/ncullen93/torchsample)

## License

Apache 2.0
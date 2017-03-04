
There are two versions of the project here.
`localversion` is trained on my local machine, so has to run for fewer epochs, etc.

`floydversion` runs on http://floydhub.com/ on a gpu instance.
Run the following commands in the `floydversion` directory to get it running.

```
floyd init dlnd_image_classification
floyd run --gpu --env tensorflow-1.0 --mode jupyter --data diSgciLH4WA7HpcHNasP9j
```

Rest of instructions are as here:

https://github.com/ludwiktrammer/deep-learning/tree/master/image-classification

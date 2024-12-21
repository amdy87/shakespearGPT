# shakespearGPT
GPT transformer model that imitates shakespear text adapted from [Andrej Karpathy's lecture on building GPT](https://www.youtube.com/watch?v=kCc8FmEb1nY)

The v2 model is trained on all shakespear text found in the input.txt file. It utilizes the transformer multi-headed self-attention to achieve better results compared to the base bigram language model it was built on. 

```
Experimental Parameters
******************************
Batch size:  64
Block size:  64
Max Iterations:  5000
Evaluation interval:  500
Evaluation iterations:  200
Number of Embeddings:  256
Number of heads:  4
Number of layers:  6
******************************

step 0: train loss 4.5578, val loss 4.5666
step 500: train loss 1.7022, val loss 1.8416
step 1000: train loss 1.5139, val loss 1.7034
step 1500: train loss 1.4269, val loss 1.6239
step 2000: train loss 1.3776, val loss 1.6036
step 2500: train loss 1.3449, val loss 1.5905
step 3000: train loss 1.3139, val loss 1.5620
step 3500: train loss 1.2871, val loss 1.5497
step 4000: train loss 1.2670, val loss 1.5585
step 4500: train loss 1.2454, val loss 1.5701

The cause of foul intercyment of you!
All feel in me, I was to be forgot. Let us trusts,
Even back up and believous mount: what art,
stabb'd once even what you do consider my wife!
Where should all thou paints elected: hear
By his faces, steer blood to this face.

LUCIO:
Now, why, sir, in the Tower?
But this my mague father thanks the deed.

YORK:
Uncle Menenius? You know to appose the heaviliff;
And were well mine, and pace-so, dost hump,
For it stop apper with possessance to him?
And here thou
```

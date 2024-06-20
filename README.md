ne-Xt ray is a research paper published by Stanford University, where they outlined how bone fractures can be identified with high accuracy 98% using CNN networks. They used multiple different architectures: DenseNet (+variations) and ResNet152.

In this repo, I have coded the training code necessary to recreate the original architecture outlined in Stanford University's ne-Xt technical paper. 

Shortcoming (presented due to author's choice of not providing information)
1. No specified epoch count and steps count
2. Batch number absent
3. final layers after original ResNet152 not specified. 
4. Binary cross-entropy values missing and not mentioned what framework was used to get the loss function

We present training code in Tensorflow to train ResNet152 according to the Stanford's technical paper. 

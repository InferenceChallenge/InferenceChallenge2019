## MCL Embedded Inference Challenge 2019

> PyTorch, ONNX, LLVM, Neo, Bonseyes, Caffe, MLIR, TVM, XLA

If these are your tools, join the challenge and win one of two [Kunbus RevPi Connect](https://revolution.kunbus.com/revpi-connect/) or one of five [Nordic Thingy:52](https://www.nordicsemi.com/?sc_itemid=%7B3C201A33-5CA5-457B-87E4-A7B04C19EE71%7D)

![Kunbus RevPi Connect](https://revolution.kunbus.de/wp-content/uploads/2018/07/RevPi-Core-Tutorial.png)
![Nordic Thingy:52](https://www.mouser.com/images/marketingid/2017/img/116326113_Nordic_Thiny52IoTSensorDevelopmentKit.png)

## Task

- Pick an LSTM-based model from the list on [paperswithcode.com](https://paperswithcode.com/sota/language-modelling-on-penn-treebank-word). Train on [Penn Treebank dataset](https://www.tensorflow.org/tutorials/sequences/recurrent) (or as you like, as long as test perplexity is smaller than 80).
- Optimise, transform, quantise the model as you deem suitable (as long as perplexity stays below 80)
- Generate a self-contained binary implementing inference on the test data set for the RevPi (ARM Cortex A53 (ARMv8)). Keep test data set in plain text.
 - Send the binary, the output of `readelf -h -S binary`, a short document, describing your approach and tools used (max 4 pages, pdf format) to [InferenceChallenge@mcl.at](mailto:InferenceChallenge@mcl.at) Deadline: 31.6.2019 (extended!)

We will rank the entries by size of the .data section. The top seven will receive a [Kunbus RevPi Connect](https://revolution.kunbus.com/revpi-connect/) or [Nordic Thingy:52](https://www.nordicsemi.com/?sc_itemid=%7B3C201A33-5CA5-457B-87E4-A7B04C19EE71%7D).

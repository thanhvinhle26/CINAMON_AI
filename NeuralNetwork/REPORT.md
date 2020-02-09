# REPORT
* Experiment with different hidden dimmension (number of hidden units) 20, 50, 100.
    * 20: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D20%20n_hidden%3D20%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * 50: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D20%20n_hidden%3D50%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * 100: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D20%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    > We find that experiment with 100 hidden dimension has the highest loss and accuracy so we choose it to the next experiment
* Experiment with different epochs: 20, 50, 100.
    * 20: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D20%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * 50: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D50%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * 100: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    > We find that experiment with 100 epochs has the highest loss and accuracy so we choose it to the next experiment 
* Experiment with different input scaling: 0-to-1, 0-to-255
    * 0-to-255 :![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * 0-to-1 : ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9%20scale1.png)
    > We find that experiment with input scaling 0-to-255 has the highest loss and accuracy so we choose it to the next experiment
* Experiment with different learning rate: 0.1, 0.001, etc.
    * 0.1 : ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * 0.001: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.001%20momentum%20%3D%200.9%20scale1.png)
    >  We find that experiment with learning rate 0.1 has the highest loss and accuracy so we choose it to the next experiment
* Experiment with different momentumn factors: 0.9, 0.8, 0.1, 0.0.
    * 0.9: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * 0.8: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.8.png)
    * 0.1: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.1.png)
    * 0.0: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.png)
    > We find that experiment with momentumn factors: 0.9 has the highest loss and accuracy so we choose it.
    
1. The higher hidden units we use the better we have in loss and accuracy
3. My network does not over fit with accuracy of the training set is 0.94 and the test set is 0.93
    * Training set: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9.png)
    * Test set: ![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/NeuralNetwork/epoch%3D100%20n_hidden%3D100%20learning%20rate%20%3D%200.1%20momentum%20%3D%200.9%20test.png)
4. Confusion matrix:

|5765|0|37|14|4|54|27|20|22|34|
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|---:|
|0|6586|17|15|21|22|8|33|60|14|
|18|30|5475|122|26|41|35|68|64|25|
|13|19|60|5600|2|137|3|26|94|87|
|6|4|70|3|5565|38|28|50|28|148|
|35|28|20|149|8|4891|78|10|100|24|
|36|6|92|20|48|71|5713|1|32|4|
|4|22|76|76|7|16|1|5943|18|115|
|41|40|97|96|24|102|24|17|5374|38|
|5|7|14|36|137|49|1|97|59|5460|
        

        
    

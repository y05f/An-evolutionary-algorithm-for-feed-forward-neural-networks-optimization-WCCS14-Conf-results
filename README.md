# An-evolutionary-algorithm-for-feed-forward-neural-networks-optimization-WCCS14-Conf-results

Y. Safi and A. Bouroumi, "An evolutionary algorithm for feed-forward neural networks optimization," in Complex Systems (WCCS), 2014 Second World IEEE Conference on, Agadir 2014, pp. 475-480.

https://doi.org/10.1109/ICoCS.2014.7060901

* To compile: g ++ -std = c ++ 0x main.cpp -o ./Emlp -fopenmp
* To run: ./Emlp
When running:
* Choose 0 to start the evolution of a new population or 1 to test the performance of an old saved population of neural networks architectures.
* In both cases the program asks you to enter the name of the dataset. This name is exactly the name of the folder that contains the train.csv, valid.csv and test.csv data
Once the dataset is chosen: 
* In the case of 0 (learning), the program initializes the parameters and starts the evolution then it ends with the recording of the final population in ./save directory.
* In the case of 1 (testing), the program will ask for the name of the folder which contains the architectures with their saved synaptic weights. Each neural network is saved under the name XX-SavedWeights.xsl where XX denotes the number of neurons in the single hidden layer. The folder which contains the architectures and the weights must be in the ./save directory. When the program accepts the saved architectures, it does the fitness calculation and re-registers the results again in the same folder where the architectures are located but under the name of CEP_log.xl

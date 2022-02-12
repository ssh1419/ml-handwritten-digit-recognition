COM S 573
Lab 2
SeokHwan Song


1. Version


Python 3.7.4
Pandas 0.25.1
Numpy 1.17.2
Keras 2.3.1


2. Specify how to run your code in Windows command line. 
Every python files and datasets on one directory, and run each python files.

I used Jupyter notebook so you have to command Jupiter notebook in Windows command line. (You have to install Jupyter notebook). If you need another version for this, I can provide in another format.

3. Specify how to change the parameters 
Change the parameters by hand
1. mse
   1. opt = SGD(learning_rate=0.2, momentum=0.2, nesterov=False)
      1. Change the numbers as the tables on the report
      2. ex) learning_rate=0.2 >>>learning_rate=0.3
   2. tf.keras.layers.Dense(30, activation='relu')
      1. Change the number as the table on the report
2. cross
   1. opt = SGD(learning_rate=0.2, momentum=0.2, nesterov=False)
      1. Change the numbers as the tables on the report
   2. tf.keras.layers.Dense(30, activation='relu')
      1. Change the number as the table on the report
3. tanh
   1. opt = SGD(learning_rate=0.2, momentum=0.2, nesterov=False)
      1. Change the numbers as the tables on the report
   2. tf.keras.layers.Dense(30, activation='relu')
      1. Change the number as the table on the report
4. cnn
   1. model.add(Conv2D(15, kernel_size=(5,5), activation= 'relu', input_shape=(8,8,1)))
      1. Change the numbers as the tables on the report
      2. ex) kernel_size=(5,5) >>> kernel_size=(2,2)
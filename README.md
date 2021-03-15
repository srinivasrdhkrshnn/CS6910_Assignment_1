# CS6910_Assignment_1

##Running training model
to train parameters,
parameters=do_GD(X_train,Y_train,optimizer,activation,hl_size,input_size,output_size,n_epoch,lr,reg,w_init,loss_type,minibatch_size=1,logging=False)

X_train, Y_train input and output datasets. Note that Y_train must be a class vector, and X_train must be a row vector(convert square image to single row).
/1optimizer-'nadam','sgd', 'momentum', 'nesterov', 'rmsprop', 'adam' for selecting optimizer
/activation-activation function ('sigmoid'/'relu'/'tanh')
/hl_size-size of each hidden layer in a list
/input_size,output_size-size of input and output vectors
/n_epoch-number of epochs
/lr-learning rate
/reg-weight decay term
/w_init-initialization algorithm-'xavier'/'random'
/loss_type-'cross_entropy','squared_error'
/minibatch_size-size of each minibatch
/logging-set to True to log loss and accuracy to wandb

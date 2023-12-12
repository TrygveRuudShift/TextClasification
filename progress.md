# Progress

## Model trained on: 2023-11-06T11:55:04

Comment: **Standard 20 epoch training**

Result:

- Test loss: 0.079
- Test accuracy: 0.9715

![Loss plot](figure/loss/2023-11-06T11:55:04.png)
![Accuracy plot](figure/accu/2023-11-06T11:55:04.png)

## Model trained on: 2023-11-06T12:14:57

Comment: **Added hidden layer**

Result:

- Test loss: 0.0736
- Test accuracy: 0.9825

![Loss plot](figure/loss/2023-11-06T12:14:57.png)
![Accuracy plot](figure/accu/2023-11-06T12:14:57.png)

## Model trained on: 2023-11-06T12:24:18

Comment: **added dropout**

Result:

- Test loss: 0.0792
- Test accuracy: 0.982

![Loss plot](figure/loss/2023-11-06T12:24:18.png)
![Accuracy plot](figure/accu/2023-11-06T12:24:18.png)

## Model trained on: 2023-12-08T13:15:23

Comment: **Added early stopping with patience=2 and delta=.01**

Result:

- Test loss: 0.0454
- Test accuracy: 0.988

![Loss plot](figure/loss/2023-12-08T13:15:23.png)
![Accuracy plot](figure/accu/2023-12-08T13:15:23.png)

## Model trained on: 2023-12-08T13:26:12

Comment: **Failed attempt at increasing test accuracy by increasing size**

Result:

- Test loss: 0.1565
- Test accuracy: 0.966

![Loss plot](figure/loss/2023-12-08T13:26:12.png)
![Accuracy plot](figure/accu/2023-12-08T13:26:12.png)

## Model trained on: 2023-12-08T14:43:25

Comment: **Failed attempt with decresing size**

Result:

- Test loss: 0.0866
- Test accuracy: 0.971

![Loss plot](figure/loss/2023-12-08T14:43:25.png)
![Accuracy plot](figure/accu/2023-12-08T14:43:25.png)

## Model trained on: 2023-12-08T14:52:31

Comment: **Added momentum 0.3 and changed patience to 6**

Result:

- Test loss: 0.0557
- Test accuracy: 0.9895

![Loss plot](figure/loss/2023-12-08T14:52:31.png)
![Accuracy plot](figure/accu/2023-12-08T14:52:31.png)

## Model trained on: 2023-12-08T15:03:06

Comment: **Fail using reduce lr plateau**

Result:

- Test loss: 0.1096
- Test accuracy: 0.9785

![Loss plot](figure/loss/2023-12-08T15:03:06.png)
![Accuracy plot](figure/accu/2023-12-08T15:03:06.png)

## Model trained on: 2023-12-08T16:03:59

Comment: **Fail: using Adam with lr=0.1, lasted for only 3 epochs. Will test with lower lr**

Result:

- Test loss: 0.2667
- Test accuracy: 0.9755

![Loss plot](figure/loss/2023-12-08T16:03:59.png)
![Accuracy plot](figure/accu/2023-12-08T16:03:59.png)

## Model trained on: 2023-12-08T16:11:46

Comment: **Fail: adam with lr 0.001, worse ressults and 11 epochs**

Result:

- Test loss: 0.1169
- Test accuracy: 0.974

![Loss plot](figure/loss/2023-12-08T16:11:46.png)
![Accuracy plot](figure/accu/2023-12-08T16:11:46.png)
## Model trained on: 2023-12-08T16:23:15

Comment: **Success: changed opimizer to RMSprop with lr=0.001**

Result:

- Test loss: 0.0336
- Test accuracy: 0.9915

![Loss plot](figure/loss/2023-12-08T16:23:15.png)
![Accuracy plot](figure/accu/2023-12-08T16:23:15.png)

## Model trained on: 2023-12-08T16:30:43

Comment: **Success: changed lr to 0.01**

Result:

- Test loss: 0.0218
- Test accuracy: 0.994

![Loss plot](figure/loss/2023-12-08T16:30:43.png)
![Accuracy plot](figure/accu/2023-12-08T16:30:43.png)


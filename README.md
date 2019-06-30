ACM
===

This is a Data Interpretation Document.

 

1 ,mnist_test_set

mnist_data.mat : 784\*10000

mnist_data_1.mat :784\*10000

2 ,qmnist_test_set

Qmnist_data.mat :784\*60000

Qmnist_data_1.mat :784\*60000

 

MNIST / (MNIST \_1) QMNIST /(QMNIST \_1) Real label

Col-mark ,num ,Col-mark ,num

1-980 ,980 ,1-5952 ,5952 ,0

981-2115 ,1135 ,5953-12743, 6791 ,1

2116-3147 ,1032 ,12744-18769 ,6026 ,2

3148-4157 ,1010 ,18770-24853 ,6084 ,3

4158-5139 ,982 ,24854-30633 ,5780 ,4

5140-6031 ,892 ,30634-36087, 5454 ,5

6032-6989 ,958 ,36088-42044 ,5957 ,6

6990-8017 ,1028 ,42045-48275, 6231 ,7

8018-8991 ,974, 48276-54165 ,5890 ,8

8992-10000 ,1009, 54166-60000 ,5835 ,9

Total ,10000 ,60000

 

3 ,00 ,01 ,02 ,03 ,04 are the sample data generated based on SPCA.

0.mat : training the data “0” which is the 1st column of samp_data.mat

lossall: 2\*5 cell——2 layers and 5 patterns——loss value

recognoresult : 5\*2 cell

1st column ——Unrecognized labels at each layer in mnist_data.

2nd column ——Unrecognized labels at each layer in mnist_data_1.

recognoresultq: 5\*2 cell

1st column ——Unrecognized labels at each layer in qmnist_data.

2nd column ——Unrecognized labels at each layer in qmnist_data_1.

recogresult: 5\*5 cell ,row represents pattern

1st column ——recognized labels at each layer in mnist_data.

2nd column ——Recognition Rate of 0-9 in mnist_data.

3rd & 4th col——Total number of identifications per layer.

5th col ——Number of correct identifications for each number.

recogresult_1: For mnist_data_1.

recogresult_1q: For qmnist_data_1.

recogresultq : For qmnist_data.

 

res_imgdata: 2\*5 cell——2 layers and 5 patterns——impression

timedata: Reference time (s) for block operation.

 

4 ,samp_data_origin1 —— samp_data_origin10

Digital data sampled from the original training set（mnist_train_set,60000）

 

5 test_results

1),Validation_00_mnist_data.mat 10000\*3

training “0” in files \<00\>, test on mnist_data.

1st col : real label

2nd col : Recognition results of 1st layer under P3.

3rd col： Recognition results of 2nd layer under P3.

2), Validation_00_mnist_data_1 ,For mnist_data_1

3), Validation_00_Qmnist_data ,For Qmnist_data

4), Validation_00_Qmnist_data_1 ,For Qmnist_data_1

 

 

6, \\data\\00\\impressiondata\\

impression_data.mat , 2\*10 cell ,the results of intermediate process.

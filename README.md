# Algorithm_03

## Model 1 : 3 Layer ( 3x3 Conv > 2x2 Max_Pool > FC (Activation:Softmax) )
![Model1](https://user-images.githubusercontent.com/66230126/83494832-cbb60a00-a4f1-11ea-93f1-9b13a6a460b9.PNG)
### 1. Architecture
![Model1_Arch](https://user-images.githubusercontent.com/66230126/83494835-cc4ea080-a4f1-11ea-9494-003ec3fcca2a.PNG)
### 2. Training : 5 epochs training (Optimizer=Adam, Loss function=Crossentropy)
![Model1_Train](https://user-images.githubusercontent.com/66230126/83494839-cce73700-a4f1-11ea-81aa-bd41da85a7be.PNG)
### 3. Test performance
![Model1_Acc](https://user-images.githubusercontent.com/66230126/83494834-cbb60a00-a4f1-11ea-896a-d18da877eb43.PNG)
### 4. Examples of right prediction
![Model1_Right](https://user-images.githubusercontent.com/66230126/83494837-cc4ea080-a4f1-11ea-8beb-7eec5e0be5f2.PNG)
### 5. Examples of wrong prediction
![Model1_Wrong](https://user-images.githubusercontent.com/66230126/83494826-ca84dd00-a4f1-11ea-8add-9038444b30d9.PNG)

## Model 2 : 5 Layer ( 3x3 Conv > 2x2 Max_Pool > 3x3 Conv > 2x2 Max_Pool > FC (Activation:Softmax) )
![Model2](https://user-images.githubusercontent.com/66230126/83494931-f4d69a80-a4f1-11ea-8b75-d611df55c18c.PNG)
### 1. Architecture
![Model2_Arch](https://user-images.githubusercontent.com/66230126/83494932-f607c780-a4f1-11ea-8c51-b7bf8cef9b79.PNG)
### 2. Training : 5 epochs training (Optimizer=Adam, Loss function=Crossentropy)
![Model2_Train](https://user-images.githubusercontent.com/66230126/83494941-f99b4e80-a4f1-11ea-8040-ec974a444eaf.PNG)
### 3. Test performance
![Model2_Acc](https://user-images.githubusercontent.com/66230126/83494945-fb651200-a4f1-11ea-89e6-ffefc2e3dfe2.PNG)
### 4. Examples of right prediction
![Model2_Right](https://user-images.githubusercontent.com/66230126/83494948-fd2ed580-a4f1-11ea-87f1-db39645f62b7.PNG)
### 5. Examples of wrong prediction
![Model2_Wrong](https://user-images.githubusercontent.com/66230126/83494949-fdc76c00-a4f1-11ea-8435-137254a7ace8.PNG)

## Model 3 : 7 Layer ( (3x3 Conv > 2x2 Max_Pool)*3 > FC (Activation:Softmax) )
![Model3](https://user-images.githubusercontent.com/66230126/83495004-12a3ff80-a4f2-11ea-9844-8de36e267a27.PNG)
### 1. Architecture
![Model3_Arch](https://user-images.githubusercontent.com/66230126/83495116-39facc80-a4f2-11ea-8a13-a664b406dddb.png)
### 2. Training : 5 epochs training (Optimizer=Adam, Loss function=Crossentropy)
![Model3_Train](https://user-images.githubusercontent.com/66230126/83495002-120b6900-a4f2-11ea-808a-a86d60546b33.PNG)
### 3. Test performance
![Model3_Acc](https://user-images.githubusercontent.com/66230126/83495009-13d52c80-a4f2-11ea-811a-19ce79b60048.PNG)
### 4. Examples of right prediction
![Model3_Right](https://user-images.githubusercontent.com/66230126/83495014-159ef000-a4f2-11ea-80ae-baba86368274.PNG)
### 5. Examples of wrong prediction
![Model3_Wrong](https://user-images.githubusercontent.com/66230126/83495017-16378680-a4f2-11ea-803c-1fd23b023aab.PNG)

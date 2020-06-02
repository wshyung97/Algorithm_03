# Algorithm_03

## Model 1 : 3 Layer ( 3x3 Conv > 2x2 Max_Pool > FC (Activation:Softmax) )
![Model_1](https://user-images.githubusercontent.com/66230126/83489272-24cd7000-a4e9-11ea-85b8-b5e4b2a065f5.PNG)
### 1. Architecture
![Model_1_Arch](https://user-images.githubusercontent.com/66230126/83489274-25660680-a4e9-11ea-9a67-74598919e712.PNG)
### 2. Training : 5 epochs training (Optimizer=Adam, Loss function=Crossentropy)
![Model_1_Train](https://user-images.githubusercontent.com/66230126/83489278-25fe9d00-a4e9-11ea-8cb6-be3287a7f2a5.PNG)
### 3. Test performance
![Model_1_Acr](https://user-images.githubusercontent.com/66230126/83489273-25660680-a4e9-11ea-81ef-4b98c25d97d6.PNG)
### 4. Examples of right prediction
![Model_1_True_2](https://user-images.githubusercontent.com/66230126/83489268-2434d980-a4e9-11ea-9bde-b36fffe2ce90.PNG)
### 5. Examples of wrong prediction
![Model_1_False](https://user-images.githubusercontent.com/66230126/83489276-25fe9d00-a4e9-11ea-9226-1790aafd8a9b.PNG)

## Model 2 : 5 Layer ( 3x3 Conv > 2x2 Max_Pool > 3x3 Conv > 2x2 Max_Pool > FC (Activation:Softmax) )
![Model_2](https://user-images.githubusercontent.com/66230126/83489449-5f370d00-a4e9-11ea-92a3-510fb31e19e5.PNG)
### 1. Architecture
![Model_2_Arch](https://user-images.githubusercontent.com/66230126/83489453-5fcfa380-a4e9-11ea-88ed-3d9887a88214.PNG)
### 2. Training : 5 epochs training (Optimizer=Adam, Loss function=Crossentropy)
![Model_2_Train](https://user-images.githubusercontent.com/66230126/83489457-60683a00-a4e9-11ea-8b72-53bb8728496a.PNG)
### 3. Test performance
![Model_2_Acr](https://user-images.githubusercontent.com/66230126/83489451-5fcfa380-a4e9-11ea-8aec-30cbe8a00125.PNG)
### 4. Examples of right prediction
![Model_2_True2](https://user-images.githubusercontent.com/66230126/83489444-5e9e7680-a4e9-11ea-8786-32b0fae64832.PNG)
### 5. Examples of wrong prediction
![Model_2_False](https://user-images.githubusercontent.com/66230126/83489456-60683a00-a4e9-11ea-8930-80daab9ad53c.PNG)

## Model 3 : 7 Layer ( (3x3 Conv > 2x2 Max_Pool)*3 > FC (Activation:Softmax) )
![Model_3](https://user-images.githubusercontent.com/66230126/83489489-6cec9280-a4e9-11ea-86ed-990d0e6cbaee.PNG)
### 1. Architecture
![Model_3_Arch](https://user-images.githubusercontent.com/66230126/83489491-6d852900-a4e9-11ea-9a23-407382ccf925.PNG)
### 2. Training : 5 epochs training (Optimizer=Adam, Loss function=Crossentropy)
![Model_3_Train](https://user-images.githubusercontent.com/66230126/83489495-6e1dbf80-a4e9-11ea-9700-598823dc74c8.PNG)
### 3. Test performance
![Model_3_Acr](https://user-images.githubusercontent.com/66230126/83489490-6d852900-a4e9-11ea-8118-d252d21c138b.PNG)
### 4. Examples of right prediction
![Model_3_True2](https://user-images.githubusercontent.com/66230126/83489485-6c53fc00-a4e9-11ea-8dfd-5cb465f82dc6.PNG)
### 5. Examples of wrong prediction
![Model_3_False](https://user-images.githubusercontent.com/66230126/83489493-6e1dbf80-a4e9-11ea-9105-5a2b4435b5e3.PNG)

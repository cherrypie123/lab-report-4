1. I entered in 
``` 
rm -rf lab7
```
to delete the fork on my account

![Delete fork of respository](https://user-images.githubusercontent.com/122495762/221437976-ae415ac7-38ee-44a4-848e-e3e8ffeca1e5.jpg)

2. I clicked on the button fork on lab7 

![screenshot 1677447534](https://user-images.githubusercontent.com/122495762/221439005-ef396ba0-e8f6-40ce-aa1d-70d079de8c0d.jpg)

3. I took me around 1 minute and 35 seconds to finish the challenges.
4. I enter in 
``` 
ssh cs15lwi23adt@ieng6.ucsd.edu
``` 
to log into my ssh account

5. I enter 
```
git clone git@github.com:ucsd-cse15l-w23/lab7.git
```

![Clone fork repository](https://user-images.githubusercontent.com/122495762/221438075-7e6a60ab-bb93-47f1-9a04-d4e03ddb6840.jpg)

6. I entered ```javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java```
and 

```
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore 
TestListExamples
```

![Failed test](https://user-images.githubusercontent.com/122495762/221438229-4f7b15c8-a14a-40f8-8c19-ce201b64d45b.jpg)

7. After vim ListExamples.java
I press ```<G>``` to go move cursor to the end of the document 
 
![screenshot 1677446858](https://user-images.githubusercontent.com/122495762/221438366-be90aa27-0097-44b1-8e38-ed99ebe09563.jpg)
 
Then I press ```<up>``` arrow 6 times to go the beginning of the line that needs fixing
 
![screenshot 1677446956](https://user-images.githubusercontent.com/122495762/221438402-86c92efb-5e95-4bc9-9959-34e7fa7b728b.jpg)
 
Then press the ```<next>``` arrrow 12 times 

![screenshot 1677447084](https://user-images.githubusercontent.com/122495762/221438532-0d673558-77cb-4926-9018-b98c153d8d1f.jpg)

Then press ```<i>``` to enter insert mode and and press ```<delete>```

![screenshot 1677447155](https://user-images.githubusercontent.com/122495762/221438590-383f2732-95a0-48ea-b48c-7e3d163cd9c9.jpg)
 
then enter in number ```<2>```

![screenshot 1677447191](https://user-images.githubusercontent.com/122495762/221438624-822369f4-c10e-44f6-8cd1-c7dd542a1dcc.jpg)
 
 Then I press ```<Esp>``` to escape insert mode, then enter ```:wq``` to save the change and exit vim 
 
 ![screenshot 1677447221](https://user-images.githubusercontent.com/122495762/221438701-1fe3ea58-e5d9-46db-ac0e-3f494a753cff.jpg)
 
8.
  I entered ```javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java```
and 

```
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore 
TestListExamples
```
 ![screenshot 1677264410](https://user-images.githubusercontent.com/122495762/221438777-22f96fca-8c64-4df1-ac3a-2f0b36fe22e2.jpg)
 
9.I enter 
 ``` 
 git add List Examples.java
 git commit -m "Updated" 
 git push origin main
 ```
 
 ![screenshot 1677264746](https://user-images.githubusercontent.com/122495762/221438831-872603b4-4415-4e2c-aabd-dd50d0570146.jpg)


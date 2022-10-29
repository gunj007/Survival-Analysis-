# Survival-Analysis- Sc_rna-seq

#Survival analysis in R Programming Language deals with the occurrence of an interesting event within a specified time and failure of it produces
incomplete observations. 

#Methods used to do survival analysise are of two types which can be used to perform survival analysis 

Kaplan-Meier method Cox Proportional hazard model

# Kaplan-Meier Method : The Kaplan-Meier method is used in survival distribution using the Kaplan-Meier estimator 
           censored data.It estimates are based on the number of patientts from the total number of patients who survive for a certain time after treatment.


# Cox proportional hazard model : It is a regression modeling that measures the instantaneous risk of deaths and is bit more difficult to illustrate than the
Kaplan-Meier estimator. It consists of hazard function (which in this case is cancer) which describes the probability of event or survival up to a particular time 

# Packages used comes with the functions:

The Surv() function takes two times and status as input and creates an object which serves as the input of survfir() function. We pass ~1 in survfit() function
to ensure that we are telling the function to fit the model on basis of the survival object and have an interrupt. 

Dataset: http://www.cgga.org.cn/download.jsp#mRNAseq_693 -clinical data 
_CGGA.mRNAseq_693_clinical.20200506.txt 

# here, the survival was checked on the basis of gender:
![image](https://user-images.githubusercontent.com/110597928/198853083-7fb48083-9725-4502-b8f0-15ef4e1bec56.png)


age:![image](https://user-images.githubusercontent.com/110597928/198853065-720554d1-5d2b-46c7-9232-e442bdda0972.png)

gender with age:![image](https://user-images.githubusercontent.com/110597928/198853107-b235b0e9-c75c-4e85-b808-6121ba576a91.png)

histology w.r.t. gender and stage of breast cancer according to gender:![image](https://user-images.githubusercontent.com/110597928/198853144-1152e7d0-5bcd-4b78-b3a5-3973ede440cd.png)

race:
![image](https://user-images.githubusercontent.com/110597928/198853031-b2f129aa-be4e-466f-ac47-886a2f9ed7b7.png)

	below 50 age male are at high risk with PRStype primary having gade WHO III are having less survial time of 900-1200days range
survfit() creates survival curves and prints the number of values, number of events(people suffering from cancer), the median time and 95% confidence interval 
 

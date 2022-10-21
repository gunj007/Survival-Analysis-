# Survival-Analysis- Sc_rna-seq

Survival analysis in R Programming Language deals with the occurrence of an interesting event within a specified time and failure of it produces
incomplete observations. 
Methods used to do survival analysise are of two types which can be used to perform survival analysis 
Kaplan-Meier method Cox Proportional hazard model Kaplan-Meier Method The Kaplan-Meier method is used in survival distribution using the Kaplan-Meier estimator 
for truncated or censored data. It's a non-parametric statistic that allows us to estimate the survival function and thus not based on underlying probabilit
y distribution. The Kaplan-Meier estimates are based on the number of patients from the total number of patients who survive for a certain time after treatment.
Cox proportional hazard model It is a regression modeling that measures the instantaneous risk of deaths and is bit more difficult to illustrate than the
Kaplan-Meier estimator. It consists of hazard function h(t) which describes the probability of event or survival up to a particular time .
The Surv() function takes two times and status as input and creates an object which serves as the input of survfir() function. We pass ~1 in survfit() function
to ensure that we are telling the function to fit the model on basis of the survival object and have an interrupt. 
survfit() creates survival curves and prints the number of values, number of events(people suffering from cancer), the median time and 95% confidence interval 

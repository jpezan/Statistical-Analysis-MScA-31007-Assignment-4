# Statistical-Analysis-MScA-31007-Assignment-4
Homework Assignment Analysis of Residuals of Linear Model

## Assigment

### Download your sample from left sidebar, unpack and read it.

### Create variable dataPath equal to path to your local folder where you saved the data file Week4_Test_Sample.csv. It should look like:

dataPath<-"C:/Your path"
Note that in R path is specified with forward slash “/”. Do not end the path with / when you assign dataPath.

### Read the data.

dat <- read.table(paste(dataPath,'Week4_Test_Sample.csv',sep = '/'), header=TRUE)
The sample dat has the following format:

dat$X - predictor X values;
dat$Y - output Y values.
Fit linear model, analyze residuals and separate the mixed samples. Create variable Unscrambled.Selection.Sequence using the same method as you did in Section 3 and save it in file result.csv Create list variable res

res <- list(Unscrambled.Selection.Sequence =  Unscrambled.Selection.Sequence)

### Save res to a file and upload the file using left sidebar.

write.table(res, file = paste(dataPath,'result.csv',sep = '/'), row.names = F)

### Your score will be equal to balanced accuracy of matching the correctly estimated selection sequence.

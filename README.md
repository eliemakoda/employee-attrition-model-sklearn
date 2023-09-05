Here we are trying to solve the employee attrition.
our model need to decide wether or not an employee should remain in the enterprise base on past data record of the employee
Here we are using the random forest algorythm 
accuracy=1.0

data: 

input: 
	TotalMonthsOfExp        int64
	TotalOrgsWorked         int64
	MonthsInOrg             int64
	LastPayIncrementBand    int64
	AverageFeedback         int64
	LastPromotionYears      int64

output: 
		Attrition               int64 (1="leave the enterprise", 0="remain in the enterprise")
dtype: object
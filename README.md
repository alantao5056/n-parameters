# N Parameters

The question is: What is the causal effect of postcards on voting in the 2026 election? Do those effects vary by political engagement? I have cleaned the data and also did an exploratory plot of civil engagement and voting. I then examined stability, representativeness and unconfoundedness. One problem is that voters in Michigan might not represent voters io Texas. I then made a brm model with the equation: voted ~ age_z + sex + treatment + voter_class + treatment * voter_class.

Check out the full paper here: [https://rpubs.com/alienjao/parametersn](https://rpubs.com/alienjao/parametersn)

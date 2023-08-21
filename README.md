# Thesis results
This repo contains some of the results of the experiments I performed as part of my master's thesis.

## Rule lists
Rule lists are printed as ".csv" files, 
- the first column is a string representation of the rule
- the second column is the label distribution of training samples covered by the rule.  Interpretation: [_#reject_, _#hire_] 
- the third column is the 3-way label distribution of training samples covered by the rule.  Interpretation: [_#reject_, #both, _#hire_] 
- the fourth column is the distribution of the sensitive attribute of training samples covered by the rule.   Interpretation: interpret as a dictionary: (_key_:_count_) where _key_= 0 for Belgians and 1 for foreigners
- the fifth column is the evaluation score given to the rule.

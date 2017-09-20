# games_howell
GAMES_HOWELL: post-hoc Games-Howell test for one-way ANOVA.

[h,p,stats]=games_howell(data,group,alpha) performs the Games-Howell test for one-way ANOVA (analysis of variance). The Games-Howell test compares all individual group means to each other in a pairwise fashion. It accommodates groups with unequal sample sizes (with a recommended minimum number of 6 observations in any given group) and variances.

This function calls the function CDFTUKEY, by Peter Nagy (copyright). http://www.mathworks.com/matlabcentral/fileexchange/37450
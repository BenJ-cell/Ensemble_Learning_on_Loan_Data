# Ensemble_Learning_on_Loan_Data

In this project, I tried to predict whether a loan will be repaid or not.

It is a classification problem where i used Ensemble Modelling combining predictions from: ExtraTrees, RandomForest, LightGBM, GradientBoosting and CatBoost Classifiers. The stacked model performed better than any other model on each of our 5-fold cross validation obtaining a mean accuracy of 95% as shown below.

	RandomForest	ExtraTrees	LightGBM	GradientBoost	CatBoost	stackingModel
0	0.875232	0.751855	0.927180	0.938312	0.879870	0.951299
1	0.882189	0.775046	0.913729	0.932746	0.887291	0.945733
2	0.887755	0.793135	0.914657	0.942950	0.886827	0.950835
3	0.884972	0.784787	0.917904	0.946660	0.889147	0.959184
4	0.886827	0.780612	0.927644	0.940167	0.892857	0.955937
mean	0.883395	0.777087	0.920223	0.940167	0.887199	0.952597

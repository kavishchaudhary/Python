Data Dictionary

•	battery_power- energy in mAh.

•	blue- whether the phone has Bluetooth or not.	

•	clock_speed- microprocessor speed.	

•	dual_sim- phone supports dual sim or not.	

•	fc- front cameras mega pixels.

•	four_g- phone supports 4g or not.	

•	int_memory- internal memory in GB

•	m_dep- mobile depth in cm.

•	mobile_wt- weight of the phone.

•	n_cores	- no. of cores in processor.

•	pc- primary camera mega pixels.	

•	px_height- pixel resolution height.	

•	px_width- pixel resolution width.	

•	Ram- RAM in megabytes.	

•	sc_h- screen height in cm.

•	sc_w- screen width in cm.	

•	talk_time- longest time when a single battery charge will last.	

•	three_g	- phone has 3g or not.

•	touch_screen- phone has touch screen or not.	

•	Wifi- phone has wifi or not.	

•	price_range- price range of the phone(4 class)




INSIGHTS

•	ram(predictor)- This variable has a very high correlation with the target variable.

•	Multi collinearity is not a problem in this data set.

•	The target variable has 4 classes which are equally balanced.

•	The categorical predictor variables are equally balanced except for three_g.

•	The continuous predictor variables are uniformly distributed except for fc, px_height and sc_w.

•	SVC, CatBoost, LGBM Boost, XG Boost had a prediction accuracy of more than 90%


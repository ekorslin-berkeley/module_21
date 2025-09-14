# Determining causality & additional warning signs for professionals who treat addictive disorders in the field of behavioral health
Initial Report and Exploratory Data Analysis (EDA)

As a budding data scientist & close affiliate to a number of aspiring mental health professionals in the field of modern-day behavioral psychology, I recently came across a comprehensive study from 2014 completed at the University of Michigan Institute for Social Research that surveyed roughly 50,000 subjects on approximately 3,000 different situational & environmental considerations in the everyday lives of its subjects alongside several behavioral health-related questions that could potentially be used to arrive at actual clinical mental health disorder diagnoses, when appropriate, according to the DSM-IV, a trusted diagnostic guideline widely-used today for assessing behavioral health disorders in the field of mental health.

The provided dataset, although comprehensive in its extensive coverage across a wide area of potential social influences, after-effects, and sympotoms relating to addicative disorders, was maybe too detailed, I found, in terms of needs for this assignment.  For that reason, I underwent a very careful approach to first find the top five to 10 features that correlated the strongest with the subjects who were diagnosed with the unfortunate DSM-IV dianosis of having an actual cocaine dependency disorder at some point in the past 12-months.  

<img width="569" height="338" alt="image" src="https://github.com/user-attachments/assets/b16895e5-c6f2-44e4-9111-f2b27643a284" />

The features that returned w/ the strongest positive correlation for those w/ a cocaine dependency disorder are as follows:
  1.  DEPNDIEM: Illicit Drug Other Than Marijuana Deo In Past YR    [0.838386]
  2.  COCEMCTD: Cont'd to use Cocaine Despite EMOT Problem          [0.501517]
  3.  DEPNDPSY: Psychotherapeutic Dependence in the Past Yr         [0.190381]
  4.  SERVICE:  Even Been in the Armed Forces?                      [0.100504]
  5.  ILLPFMLY: Last/Current Ill drug Tx Paid for by Family Mmbr(s) [0.025569]

Although I set out more-so in search of better understanding causality for environmental & life consideration factors that influence & potentially lead to these horrifying  disorders, the strongest correlations stood out as sidebar warning signs for any treatment professional sought out by those in need of help for illegal drug disorders in that they suggest a very strong likelihood for other illicit drug dependencies at play, as well, for those struggling with a cocaine dependency addiction, for example.  Additionally, the correlation analysis also found a strong correlation that those who have been clincially diagnosed typically continue to abuse narcotics even after being qualifying for an official disagnosis by a licensed professional.  Further, the analysis suggests that there is lesser causality than originally presumed in that having served in the armed forces does not significantly increase one's likelihood to develop an addictive disorder, a reassuring finding.

Lastly, a predictive model was created using a Logistic Regression model to determine from a test data set the accuracy of such a model.  The accuracy score of this model scored at just over 96.6%, an encouraging result.

<img width="397" height="273" alt="image" src="https://github.com/user-attachments/assets/fb98942c-8749-487b-b432-c0000fc1ea60" />


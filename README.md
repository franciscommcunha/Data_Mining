A data mining project involves : pre-preocessing of the raw data, the training of the machine learning algorithm and the evaluation of the algorithm.

Task A: Pre-processing
This step incorporates one or more of the following
	1. Mapping categorial data into numeric data
	2. Rank features.
	3. Perform dimension reduction (Principal Component Analysis or Kernel Principal Components).

Task B: Predictive Model
	Choose two of the leaning algorithms taught during the lectures and train the model. Note that most of the algorithms require the assigment of hyperparameters and these values have influence on the performance of the model. This aspect is an important issue to be discussed on the report.

Task C: Evaluation
Incorporate an evaluation scheme.
	1. hold-out method (the default strategy to measure the performance of the model). 
	2. Following one scheme described on https://arxiv.org/abs/1809.09446v1 (https://arxiv.org/abs/1809.09446v1)
	Note that sckit-learn has facilities to implement cross-validation techniques. The paper has a systematic overview of the problem and it should be used as a guide on the discussion of your results.

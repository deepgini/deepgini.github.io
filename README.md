## DeepGini: Prioritizing Massive Tests to Reduce Labeling Cost

Deep neural network (DNN) based systems have been deployed to assist various tasks, including many tasks in safety-critical scenarios. In company with the fantastic effectiveness on many tasks, these systems could also exhibit incorrect behaviors and lead to accidents and losses. Therefore, beyond the conventional accuracy-based evaluation, testing techniques that can detect incorrect behaviors in the earlier stage of software lifecycle is also necessary and critical. However, given the fact that automated testing oracle is often not available, testing DNN-based systems usually requires expensive human efforts to label the testing data. In order to reduce the efforts and, meanwhile, diagnose as many fault-inducing tests as possible in a limited time, developers usually want to ￿nd an ideal order of tests in which fault-inducing tests are ordered before the others. To this end, we propose DeepGini, a test prioritization technique designed based on a statistical perspective of DNN. Such a statisti- cal perspective allows us to transform the problem of measuring the possibility of misclassifying a test to the problem of measuring set impurity. To evaluate our technique, we conduct an extensive empirical study on four popular datasets. The experiment results show that DeepGini outperforms conventional coverage-based test prioritization in terms of both effectiveness and effciency.

### DeepGini: Prioritizing Tests of a DNN

The metric we use to measure the likelihood of misclassifcation is defined as below.



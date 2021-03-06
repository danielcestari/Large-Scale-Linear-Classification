# Large-Scale-Linear-Classification
Large Scale Linear Classification Methods Evaluation

~~~
Liblinear
https://www.csie.ntu.edu.tw/~cjlin/liblinear/
Multi-core Liblinear
https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/multicore-liblinear/
Large linear classification when data cannot fit in memory (liblinear-cdblock)
http://www.csie.ntu.edu.tw/~cjlin/libsvmtools/#large_linear_classification_when_data_cannot_fit_in_memory
Incremental Learning Extension of Liblinear
http://www.csie.ntu.edu.tw/~cjlin/papers/ws/index.html

Vowpal wabbit
https://github.com/JohnLangford/vowpal_wabbit

SVMSGD
http://leon.bottou.org/projects/sgd

SVM Heavy
http://people.eng.unimelb.edu.au/shiltona/svm/

SGD and SDCA
http://www.vlfeat.org/api/svm.html

online SVM
https://www.quora.com/Support-Vector-Machines/What-are-some-good-tools-for-training-online-svm
http://stats.stackexchange.com/questions/26041/can-svm-do-stream-learning-one-example-at-a-time

Pegasos
"Pegasos: Primal Estimated sub-GrAdient SOlver for SVM"
http://www.cs.huji.ac.il/~shais/code/
http://vision.princeton.edu/pvt/SiftFu/SiftFu/SIFTransac/vlfeat/doc/api/pegasos.html
"Pegasos algorithm for one-class SVM"
http://cs.kangwon.ac.kr/~leeck/software/OC_SVM/
Python implementation
http://atpassos.me/post/44900142506/pegasos-in-python-0

sofia-ml (Pegasos)
https://code.google.com/p/sofia-ml/

FTRL
https://github.com/dselivanov/FTRL

passive-aggressive algorithms 
http://webee.technion.ac.il/people/koby/code-index.html

incremental/decremental SVM learning in Matlab
https://github.com/diehl/Incremental-SVM-Learning-in-MATLAB
Incremental and Decremental Support Vector Machine Learning
http://www.isn.ucsd.edu/svm/incremental/

Using stochastic gradient descent (SGD) with explicit and implicit updates to fit large-scale statistical models.
http://www.people.fas.harvard.edu/~ptoulis/harvard-homepage/implicit-sgd.html
https://github.com/ptoulis/implicit-sgd

BudgetedSVM
http://www.dabi.temple.edu/budgetedsvm/algorithms.html

SGD
http://scikit-learn.org/stable/modules/sgd.html

SVMlin
http://vikas.sindhwani.org/svmlin.html
and other SVM's
https://github.com/shogun-toolbox/shogun

SVMperf
http://www.cs.cornell.edu/people/tj/svm_light/svm_perf.html

SVMTorch
http://bengio.abracadoudou.com/SVMTorch.html

SVMLight
http://svmlight.joachims.org/

Shark machine learning library - BudgetedSGD
http://image.diku.dk/shark/sphinx_pages/build/html/rest_sources/tutorials/algorithms/kernelBudgetedSGD.html

Parallel SVM
https://github.com/djebm2/psvm

Python:
sklearn.linear_model.SGDClassifier
http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.SGDClassifier.html
Differen solvers in python (primal coordinate descent, dual coordinate descent (SDCA, Prox-SDCA), SGD, AdaGrad, SAG,SVRG,FISTA)
https://github.com/mblondel/lightning
~~~


TODO:
~~~
http://lingpipe-blog.com/2009/04/08/convergence-relative-sgd-pegasos-liblinear-svmlight-svmper/
https://github.com/zygmuntz/large-scale-linear-learners
http://fastml.com/vowpal-wabbit-liblinear-sbm-and-streamsvm-compared/
https://github.com/szilard/benchm-ml
http://courses.cs.washington.edu/courses/cse599s/12sp/

SVM list
http://www.svms.org/software.html
http://www.support-vector-machines.org/SVM_soft.html

~~~

TODO:
~~~
Check optimization method in linear svm
https://github.com/cjlin1/liblinear
Maybe rewrite it in c++/stl as exercise, make it crossplatform by using cmake build system, maybe blas should be excluded from project itself and something like openblas used.
~~~

Materials about Stream learning / Online learning / Incremental  learning
~~~
http://stats.stackexchange.com/questions/26041/can-svm-do-stream-learning-one-example-at-a-time
~~~

tools for convertion:
~~~
https://github.com/JohnLangford/vowpal_wabbit/wiki/Input-format#libsvm-format
https://github.com/zygmuntz/phraug
https://github.com/zygmuntz/phraug2
~~~

related:
~~~
https://github.com/mrgloom/Gradient-Descent-Evaluation

Large scale learning:
http://leon.bottou.org/research/largescale
~~~

Other:
~~~
Enhancements to SGD include Pegasos, PassiveAggressive algorithms, Confidence Wighted Learning, Adagrad, AROW, and Natural Gradient Descent.
~~~

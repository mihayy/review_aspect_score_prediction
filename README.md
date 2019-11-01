# Stance Detection in Scientific Reviews

Master's Thesis: “Stance Detection in Scientific Reviews”.

The thesis studies the peer review artifact and presents a practical approach for solving the novel, [Review Aspect Score Prediction](https://arxiv.org/abs/1804.09635) NLP task using the [PeerRead](https://github.com/allenai/PeerRead) dataset. The task consists of predicting the aspect (e.g. clarity, originality) scores of a scientific paper by its peer review comments.

**Accuracy on Review Aspect Score Prediction task, for [ACL_2017](https://github.com/allenai/PeerRead/tree/master/data/acl_2017) reviews: 0.61428**


## Abstract

People use feedback as a basis for improvement. Upon delivering a paper, the author receives feedback on his submission, which usually comes as free text and may also contain scores for various aspects such as correctness, originality and clarity. However, despite its popular use, the feedback process is time consuming and tends to be biased towards the reviewer. A recent paper released the first scientific peer review dataset, PeerRead, and formulated a novel task to help research and solve the shortcomings of peer reviewing process through automatic and consistent score prediction. The task, Review Aspect Score Prediction, consists in predicting the aspect scores of a paper by its peer review comments. The central aim of the thesis is to research and solve the Review Aspect Score Prediction task.

The thesis studies the peer review artifact through a thorough exploration of aspect scores and feedback comments. In effort to solve the novel task by applying Deep Learning on a very small dataset, we attack with a suite of neural model classifiers such as CNN, RNN, Multitask RNN, [Conditional RNN](https://arxiv.org/abs/1606.05464), state-of-the-art [ULMFiT](https://arxiv.org/abs/1801.06146). This yields an accuracy of 0.59788.

The thesis then looks for ways to advance performance by acting on the small dataset. We use weak supervision to improve reviews’ quality, and show that having consistent structure and more relevant content of comments further boosts the performance on aspect prediction task to 0.61428.

The thesis provides insights through empirical observations on comments, aspects and models. We suggest ways for optimizing the scientific peer reviewing process by dropping unnecessary aspects and keeping the most valuable sections of reviews.

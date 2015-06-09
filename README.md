# Word-Sense-Disambiguation-TiMBL

Final Project
L665/B659: Applying Machine Learning Techniques in CL; Sandra Kuebler
Your task is to build a Word Sense Disambiguation system based on the SemEval-3 lexical sample
data set. The question you will investigate is how feature selection affects the classifer.This involves the
following subtasks:

1. Select a machine learner. Note that you have to motivate the choice in your Final paper.

2. Design a feature set, which should minimally consist of the 3 words left and right of the target word,
their POS tags, and keywords from the remaining context. Add any features you think would be
helpful.

3. In order to POS tag the data, I would suggest that you use the Stanford POS tagger: http:
//nlp.stanford.edu/software/tagger.shtml. This POS tagger comes with a pretrained model.
If you need help with running the parser, let me know.

4. Decide on a representation of your features depending on the choice of machine learner. Motivate
the representation in your Final paper.

5. Choose a feature selection method and implement it. Note that if you decide to use either forward or
backward selection, you will need to find subgroups of features. Do not run tests on adding/removing
every single feature.

6. Run (at least) the following experiments: baseline (use only the immediate context), one run with
all features, and one run with the features selected by the feature selection method. If you choose
a Filter method, run several experiments with a varying number of features.

7. Write a scientific paper, with an introduction, a related work section, a section on methodology, a
section on results, including a discussion, and a conclusion. The paper should be 6-8 pages long.
The paper should explain your research question in the introduction. The related work section should
give an overview of work in WSD and more specifcally on feature selection for WSD. In the
methodology section, describe your choice of classifer and motivate the latter. Then describe the
data set and the feature set and motivate the representation that you chose. Then, explain your
feature selection method and motivate it.

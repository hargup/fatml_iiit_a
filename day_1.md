# Basics of Machine Learning by Prof. Harish Karnick (IIT Kanpur)

In this lecture Prof. Karnick covered some of the basic of machine learning,
first he went through we use machine learning, what are the various dimensions
of machine learning (supervised, unsupervised, reinforcement etc). Then he
explained the supervised Learning problem, explained perception. All these
things are which are usually explained in a machine learning class. Here are
the things which are not usually covered:

## Why ML algos gives wrong results

* All the supervised learning models assume that the data is independently and
    identically distributed, but in most applications this is not true.
    Sometimes it doesn't really matter but in other cases it can drastically
    change the result.

* Attributes can be different w.r.t magnitude in range. Hence it is very
    important to normalize the data.

* The dataset can be unbalanced. For example if you want to predict if someone
    has aids, then the percentage of people with aids is very low say 1%. If
    you give everyone the label that she doesn't have aids then you are 99%
    accurate but you are not even looking at the data. Hence it is important to
    balance the data.

* Signal can be hidden in a lot of noise or it can be hard to determine what is
    noise and what isn't.

## Performance metrics

There can exist various performance metrics, precision, recall, the ROC curve,
all of them measure certain things but it is important to look at things which
these metrics don't measure, like comprehensibility, discrimination and privacy.
These are also qualities which we would like our ML algorithms to have and the
rest of the course is about how we can incorporate them in ML.

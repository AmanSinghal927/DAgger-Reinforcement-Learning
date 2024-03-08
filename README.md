# A Reduction of Imitation Learning and Structured Prediction to No-Regret Online Learning

Sequential prediction problems such as imitation
learning, where future observations depend on
previous predictions (actions), violate the common i.i.d. assumptions made in statistical learning. This leads to poor performance in theory
and often in practice. Some recent approaches
(Daumé III et al., 2009; Ross and Bagnell, 2010)
provide stronger guarantees in this setting, but remain somewhat unsatisfactory as they train either
non-stationary or stochastic policies and require
a large number of iterations. In this paper, we
propose a new iterative algorithm, which trains a
stationary deterministic policy, that can be seen
as a no regret algorithm in an online learning setting. We show that any such no regret algorithm,
combined with additional reduction assumptions,
must find a policy with good performance under
the distribution of observations it induces in such
sequential settings. We demonstrate that this
new approach outperforms previous approaches
on two challenging imitation learning problems
and a benchmark sequence labeling problem.

You can find more information at [paper](https://arxiv.org/pdf/1011.0686.pdf) [^1].

## References

- [^1]: @inproceedings{ross2011reduction,
  title={A reduction of imitation learning and structured prediction to no-regret online learning},
  author={Ross, St{\'e}phane and Gordon, Geoffrey and Bagnell, Drew},
  booktitle={Proceedings of the fourteenth international conference on artificial intelligence and statistics},
  pages={627--635},
  year={2011},
  organization={JMLR Workshop and Conference Proceedings}
}
- [^2]: **Montague, P. R.** (1999). "Reinforcement learning: an introduction, by Sutton, R.S. and Barto, A.G." _Trends in Cognitive Sciences_, 3(9), 360. Elsevier.

For further reading on related topics, see the comprehensive book by Sutton & Barto[^2].

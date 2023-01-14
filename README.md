# ML-DecisionTrees

### Measure of Impurity

#### Entropy

$$ Entropy(S) =  \sum_{i=1}^{c} -p_i * \log(p_i) $$

$$c: the num of class$$

$$ Entropy(S_2) =  \sum_{i=1}^{n} w_i * Entropy(P_i) $$

$$w_i: percentage of the $$ith$$ partition $$

##### Info Gain

$$ InfoGain(F) = Entropy(S_1) - Entropy(S_2) $$

#### Gini

$$ Gini(S) = 1 - \sum_{i=1}^{c} p_i^2 $$
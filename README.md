# KERMIT4NLI

## Project Datasets

- **MultiNLI** (https://www.aclweb.org/anthology/N18-1101.pdf)

  This paper introduces the Multi-Genre Natural Language Inference (MultiNLI) corpus, a
  dataset designed for use in the development
  and evaluation of machine learning models for
  sentence understanding. At 433k examples,
  this resource is one of the largest corpora available for natural language inference (a.k.a. recognizing textual entailment), improving upon
  available resources in both its coverage and
  difficulty. MultiNLI accomplishes this by offering data from ten distinct genres of written
  and spoken English, making it possible to evaluate systems on nearly the full complexity of
  the language, while supplying an explicit setting for evaluating cross-genre domain adaptation. In addition, an evaluation using existing machine learning models designed for the
  Stanford NLI corpus shows that it represents a
  substantially more difficult task than does that
  corpus, despite the two showing similar levels
  of inter-annotator agreement.

- **HANS** (https://www.aclweb.org/anthology/P19-1334.pdf)

  A machine learning system can score well on
  a given test set by relying on heuristics that are
  effective for frequent example types but break
  down in more challenging cases. We study this
  issue within natural language inference (NLI),
  the task of determining whether one sentence
  entails another. We hypothesize that statistical NLI models may adopt three fallible syntactic heuristics: the lexical overlap heuristic,
  the subsequence heuristic, and the constituent
  heuristic. To determine whether models have
  adopted these heuristics, we introduce a controlled evaluation set called HANS (Heuristic Analysis for NLI Systems), which contains
  many examples where the heuristics fail. We
  find that models trained on MNLI, including
  BERT, a state-of-the-art model, perform very
  poorly on HANS, suggesting that they have
  indeed adopted these heuristics. We conclude
  that there is substantial room for improvement
  in NLI systems, and that the HANS dataset can
  motivate and measure progress in this area.


## Models

### Bert Only

### Bert + Kermit

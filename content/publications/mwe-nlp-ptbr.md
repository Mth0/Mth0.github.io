+++
date = 2025-11-28
title = "Challenges in Multiword Expressions Processing for NLP Tasks in Portuguese"

[extra]
authors = "Mariana Gonçalves da Costa, Matheus do Ó, Marcia dos Santos Machado Vieira, and Sérgio Serra da Cruz"
where = "3rd International Conference on Data & Digital Humanities"
#doi =
pdf = "mwe-nlp-ptbr.pdf"
+++

In Natural Language Processing, Multiword Expressions (MWEs) refer to combinations of words with idiosyncratic properties; that is, their meaning cannot be directly inferred by the meaning of the individual words and are usually interpreted as a single lexical unit. Among MWEs, some expressions can function idiomatically and literally, requiring comprehension of both meanings. For example, the expressions morrer de/a X (to die of X) and chorar de/a X (to cry of X) in Portuguese are commonly used metaphorically for intensification, but can also be interpreted literally. This semantic ambiguity poses challenges for NLP tasks, such as sentiment analysis, that depend on the reliable interpretation of figurative language. These challenges are especially pronounced in low-resource languages, where the scarcity of annotated data is another issue. This paper presents an ongoing study investigating the impact of MWEs on sentence-level sentiment analysis in Portuguese, with a particular focus on openly available BERT-based models. Beyond evaluating model performance, we aim to demonstrate how insights from theoretical linguistics can inform NLP research. Relying on Usage-Based Construction Grammar, we analyze MWEs as instances of constructions, approaching them as conventionalized meaningful patterns rather than isolated lexical units. Preliminary results show that metaphorical intensifier constructions significantly interfere with sentiment classification in the trained models available for Portuguese. These findings highlight the importance of incorporating linguistically informed representations of meaning variation and constructional patterns into NLP methodologies.

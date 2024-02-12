# FOMC_minutes Dataset

The dataset, named 'fomc_minutes-label.csv', comprises 1,350 sentences each labeled under one of three categories: 'growth', 'employment', and 'inflation'. These labels were meticulously assigned by a team of three graduate researchers, all males aged between 20 to 30 years, to facilitate the training of large language models. Our methodology for labeling involved reaching a consensus among the researchers; a sentence was labeled based on a sentiment only if at least two researchers agreed on the classification. In cases where no majority agreement was reached, the sentence was categorized under 'No majority found', which is eliminated in the dataset. This dataset was instrumental in fine-tuning FinBERT and served as a benchmark to assess the model's performance in interpreting complex financial texts.

Related researches:

1) Gössi, Sandro, et al. (2023). "FinBERT-FOMC: Fine-Tuned FinBERT Model with Sentiment Focus Method for Enhancing Sentiment Analysis of FOMC Minutes." Proceedings of the Fourth ACM International Conference on AI in Finance.

2) Kim, Wonseong, Jan Frederic Spörer, and Siegfried Handschuh. (2023). "Analyzing FOMC Minutes: Accuracy and Constraints of Language Models." arXiv preprint arXiv:2304.10164.

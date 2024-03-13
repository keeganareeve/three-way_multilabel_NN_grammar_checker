# grammar_checker
Task: Using PyTorch to predict correct starting word between 'they're', 'their', and 'there'.

Content: I have a linear model (with ReLU transformations and 5 layers) as well as a bidirectional RNN model.

Here, my RNN model has the settings for the lowest processing power as possible to achieve comparable results (also, given the small dataset).

Tools:
(I coded both models in Jupyter notebooks. Both of these use PyTorch, and the data preprocessing is done mostly in pandas before changing the data to torch tensor datatypes.)

Reference (for data)

Pokou J. M., Fournier-Viger, P., Moghrabi, C. (2016). Authorship Attribution Using Small Sets of Frequent Part-of-Speech Skip-grams. Proc. 29th Intern. Florida Artificial Intelligence Research Society Conference (FLAIRS 29), AAAI Press, pp. 86-91. \< https://data-mining.philippe-fournier-viger.com/datasets-of-30-english-novels-for-pattern-mining-and-text-mining/ > Last accessed May 1, 2024.

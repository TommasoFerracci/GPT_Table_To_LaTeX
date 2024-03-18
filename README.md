# GPT-powered Table to $\LaTeX$ Converter

The purpose of this very simple Streamlit app is to allow users to convert small tables in .csv (the maximum number of tokens is a significant bottleneck) to $\LaTeX$ code. Behind the scenes a prompt is passed to GPT-3.5-turbo, after verifying that the table is not too long. If the user is not satisfied with the default result, he can prompt the model with specific stylistic preferences. This prompt is first checked for possible prompt injections.

Manually converting tables to $\LaTeX$ for reports can be a pain, so I hope you will find [this app](https://table-to-latex.streamlit.app/) useful! 

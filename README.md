# Credit Card Fraud: Exploratory Data Analysis

This notebook explores a Kaggle dataset of 999 credit card transactions, each labelled as fraudulent or legitimate. The main goal of the notebook is to answer one key question: what separates fraudulent transactions from legitimate ones?

I used Claude 5.5 Sonnet in my EDA project and it was responsible for all code outputs. I simply provided the inputs and any additional tweaks, and Claude took care of the rest by returning useful code that attempted to mirror the template.

## Reflection

Using Claude Sonnet 5.5 showed me how much faster AI can write code than I can. It often returned perfect code before I even conceived where to start. Also, it let me describe each step in plain English and get ready-to-go Python code back, such as a count plot with green and red bars, a title, axis labels, and a legend. It also took care of Python's strict formatting and syntax details. The code usually ran without errors, so I could spend my time on what the plots meant instead of on debugging grammatical errors.

Even with all the positives, there are real dangers for someone who uses AI to build this notebook without learning data science properly. The AI's interpretations of results tended to be pretty broad and generic, and it can reach a conclusion without showing the evidence of how it arrived there. The code also doesn't always do exactly what the person had in mind and a beginner data scientist with minimal experience probably might not notice. For example, the count plot of chip usage shows only 13 fraudulent transactions among chip users versus 63 among non-chip users, which makes chips look like they cut fraud by about 80%. However, there were far fewer transactions using a chip and the percentage plot shows the real difference is much closer than it appeared. Someone who stopped at the first chart would draw the wrong conclusion because they didn't understand the concepts behind their data analysis.

I really enjoyed doing the project and working through rebuilding a notebook with AI. It was much faster than simply hand coding, but it also taught me the importance of knowing what the AI is doing and not blindly accepting it.

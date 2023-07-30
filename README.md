# Persian Text Generator

In this project, we used RL methods to produce meaningful sentences in Persian language.

To run this model, you need to specify the first word of the sentence and then run the language model on it. For this, you can use the following code at the end of the notebook.

```
state = sentence_to_state('کلمه')
print('کلمه', end=' ')
for s in get_result(state):
    print(words[s], end=' ')
```

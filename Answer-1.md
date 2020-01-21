## Solution of Answer-1

__Steps Involved__:
1. Go on to the [link](https://genome.ifmo.ru/phantasus/). You will see something like this:

![1st.png](attachment:1st.png)

2. In choose the file, load (`.gct`) from your system.
3. After loading the file, following can be seen:

![2nd.png](attachment:2nd.png)

4. The highlighted category is the criteria by which we need to classify the data.
5. Removing (`NA`) data is the first step in classification.
6. Select all the (`NA`) data-points from the dataset and remove it. Other features can also be removed to see the cleaner picture.
7. After processing, following can be seen:

![3rd.png](attachment:3rd.png)

8. Now select any two columns and plot as PCA

![4th.png](attachment:4th.png)

9. After the plot, choose the color type as the feature that you want to classify.

![5th.png](attachment:5th.png)



### Result

- Following is the plot obtained.

![6.png](attachment:6.png)

__From the plot following can be easily inferred__:

- Data can be classfied based on the feature selected.
- Andocrine and exocine tumors can be classfied with higher probability in the given data.
- But data is limited and dataset is not very large, so we can't apply this on new data. We should obtain more data and see if the classification persists.

This classification can also be done by coding on $python$ or $R$, but for simple classification like this online tool can be used.




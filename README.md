# Prodigy InfoTech Machine Learning Internship Task 2

## **Task Details**

Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

## **Implementation**

The given [dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data) was pretty clean to begin with so I didn't need to do any data cleaning.

I began exploring the features available and how they relate to eachother. I also visualized all the features together to get a better picture of which features to use for clustering.

### **How many clusters?**

The next step was deciding on the number of clusters (K) that I should use for each pair of features. This can be done manually by trial and error however I chose to do it in a more iterative manner using an elbow point plot. This helps narrow the choices down quite a lot.

Lastly, after training and fitting my data, I visualize my clusters and think about what each cluster tells me about the data.

<div align="center">
    <a href="https://github.com/itsmeSamrat" target="_blank">
        <img src="https://images.unsplash.com/photo-1595948215427-904a1a82c2e5?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" 
        alt="Logo" width="500" height="300">
    </a>
</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=500&center=true&vCenter=true&width=435&lines=Wholesale+Customer+Data+Analysis">
</div>

[getting started](#getting-started)

## Description

`OBJECTIVE: The objective of the project is to describe the variation in the different types of customer that the wholesale distributor interacts with, with the help of Machine Learning.`

### About the Dataset

The dataset illustrates the clients of a wholesale distributor. It has the annual spending in monetary units on different kind of products like Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicassen. The dataset is small with 440 rows and 8 columns. All the columns are of integer type.

**Attribute Information :**

1. **Fresh**: annual spending on fresh products (integer, continuous)
2. **Milk**: annual spending on Milk products (integer, continuous)
3. **Grocery**: annual spending on Grocery products (integer, continuous)
4. **Frozen**: annual spending on Frozen products (integer, continuous)
5. **Detergent Paper**: annual spending on Detergent products (integer, continuous)
6. **Delicassen**: annual spending on Delicassen products (integer, continuous)
7. **Channel**: who are the customers (integer, nominal). **Horeca (Hotel/Restaurant/Cafe) and Retail**
8. **Region**: where does these customer live (integer,nominal) **Lisnon, Oporto and Other**

### Step taken:

Firstly, we clean the data and make sure it doesn't have any NaN values or duplicated values. Then we do EDA, in which we check for outliers, normalize the data, see the correlation between the variables, do feature scaling of the data.

Here for the feature scaling, we have compared StandardScalar and MinMaxScalar. We look at the kde plot of each variable and found out that the StandardScalar feature scaling worked better for this set of data.

We divide the data, we got from the feature scaling. As, this is a classification problem, we have used XGBoost Classifier. After all the hyper parameter optimization and we got an accuracy of 0.9015 or 90.15%, Precision of 90.13%, Recall of 90.15% with the time of 2.0ms for our testing data. Our model was not able to correctly predict about 13 data points which can be seen in the confusion matrix i.e the False Positive and False Negative. The accuracy of 90% also implies that, our model is not overfitted or underfitted

## Getting Started

- Clone the repo into your local machine.

```bash
    git clone https://github.com/itsmeSamrat/Random-Nuggets-of-Code.git
```

- Install all the packages and libraries from requirement.txt file
- Run the file as it is. It should run properly.
- Try getting more accuracy with other ML or AI models.
- Support by staring the repo 🙂😁. Thank You.

## Acknowledgement

- [Dataset](https://archive.ics.uci.edu/ml/datasets/wholesale+customers)

## License

This project is under MIT License - see the [License.txt](<insert link here>) file for more details.

## Contact Me 📨

Email : [itsmesamratthapa@gmail.com](mailto:itsmesamratthapa@gmail.com)

<!-- Back to the top -->

[Return Back to Top ⬆️](#getting-started)

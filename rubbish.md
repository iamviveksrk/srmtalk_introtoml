# Dataset
Dataset. Observe that a User ID is of the following pattern:

$$\text{X}ab$$

where $\text{X}$ denotes the group name (among A, B, C, D & E) and $ab$ denotes the member number. 

For example, the User ID $\text{A}01$ denotes that the corresponding user is in group $\text{A}$ with number $01$. 

## Section 1: EDA

### Question 1 [MCQ]

Which movie has the highest average rating?

- [ ] Movie 1
- [ ] Movie 2
- [ ] Movie 3
- [ ] Movie 4

**Answer: C**

### Question 2 [MCQ]

Find the mode for the ratings recieved by movie 5.

- [ ] 1
- [ ] 2
- [ ] 3
- [ ] 4
- [ ] 5

**Answer: 3**

### Question 3 [NAT]

Find the median for the ratings recieved by movie 6.

**Answer: 3**

### Question 4 [MCQ]

Split the dataset on the basis of their groups; you must now have 5 seperate sections.  Find the average movie ratings on each of these sections, to get the group-wise average ratings. 

Which $\text{Group, Movie}$ pair has the highest group-wise average rating?

- [ ] Group $\text{A}$, Movie $4$
- [ ] Group $\text{D}$, Movie $1$
- [ ] Group $\text{E}$, Movie $6$
- [ ] Group $\text{B}$, Movie $1$

**Answer: B**

### Question 5 [MCQ]

Which $\text{Group, Movie}$ pair has the lowest group-wise average rating?

- [ ] Group $\text{E}$, Movie $4$
- [ ] Group $\text{D}$, Movie $1$
- [ ] Group $\text{C}$, Movie $3$
- [ ] Group $\text{B}$, Movie $2$

**Answer: C**

## Section 2: K-NN

Consider a new user who's id is $\text{T}01$, whose movie ratings for the first 5 movies is as follows:

User ID|Movie 1|Movie 2|Movie 3|Movie 4|Movie 5|Movie 6
--|--|--|--|--|--|--
$\text{T}01$|2|5|2|5|3|N/A

The user is yet to watch Movie 6, and we are interested to find if the user would like the movie. For this purpose, we will use the KNN algorithm, to predict the rating given by the user for Movie 6.

### Question 1: 

Find the distances between User $\text{T}01$ and all the users in the given dataset. Use the euclidean distance, along the ratings only for the first 5 movies. 

Using the distances, find the 3 nearest neighbours and select the appropriate option below:

- [ ] $\text{A}09$, $\text{C}03$, $\text{E}02$
- [ ] $\text{E}09$, $\text{B}02$, $\text{D}08$
- [ ] $\text{A}10$, $\text{C}06$, $\text{B}07$
- [ ] $\text{B}09$, $\text{C}02$, $\text{D}02$

**Answer : D**

### Question 2: 

Apply the K-NN algorithm and predict the rating for user $\text{T}01$ on movie 6 by setting $K=1$:

**Answer: 4**

### Question 3: 

Apply the K-NN algorithm and predict the rating for user $\text{T}01$ on movie 6 by setting $K=1$:

**Answer: 4**

### Question 4: 

Apply the K-NN algorithm and predict the rating for user $\text{T}01$ on movie 6 by setting $K=1$:

**Answer: 1**

## Section 3: K-Means

We now want to perform K-Means clustering on the dataset, with $K=2$. We will initalize our cluster centres $C_1$ and $C_2$ to be the ratings of $\text{A}06$ and $\text{B}03$ respectively.

### Question 1 [NAT]

Consider the User with User ID $\text{A}01$. What is the distance between $\text{A}01$ and cluster centre $C_1$?

### Question 2 [MCQ]

Which cluster would the the User with User ID $\text{E}05$ be assigned to according to the K-Means cluster assignments step?

- [ ] $C_1$
- [ ] $C_2$

### Question 3 [MCQ]

After the assignment step, perform the cluster recomputation step to obtain the new cluster centres. What is the new value of $C_1$?

### Question 4 [MCQ]

After the assignment step, perform the cluster recomputation step to obtain the new cluster centres. What is the new value of $C_1$?



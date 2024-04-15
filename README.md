# Applied Machine Learning: Feature Engineering
This is the repository for the LinkedIn Learning course `Applied Machine Learning: Feature Engineering`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

Machine learning is not magic. The quality of the predictions coming out of your model is a direct reflection of the data you feed it during training. This course with instructor Matt Harrison guides you through the nuances of feature engineering techniques for numeric data so you can take a dataset, tease out the signal, and throw out the noise in order to optimize your machine learning model. Matt teaches you techniques like imputation, binning, log transformations, and scaling for numeric data. He covers methods for other types of data, like as one hot encoding, mean targeting coding, principal component analysis, feature aggregation, and text processing techniques like TFIDF and embeddings. The tools you learn in this course will generalize to nearly any kind of machine learning algorithm/problem, so join Matt in this course to learn how you can extract the maximum value from your data using feature engineering.

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

 ### Instructor

Matt Harrison

Python and Data Science Corporate Trainer, Author, Speaker, Consultant                   

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/matt-harrison?u=104).



[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/applied-machine-learning-feature-engineering-23752649
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQHy5vdQuVfgvw/learning-public-crop_675_1200/0/1712707937171?e=2147483647&v=beta&t=F_Dqs3N174G-FLIAoBvKf0LDPwx8mRQ5BKJhZ7FPv4k


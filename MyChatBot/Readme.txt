The chatbot books a:
1. Restaurant for you, given your specific preferences and also, 
2. Books a Doctor's appointment, given the appropriate time slot, location, specialization etc.

I am identifying the intent of the user based on the classification algorith which 
uses the Bag of Words feature extraction, with the Linear SVM classifier (Bonus criterion).

As I have a relatively big dataset (250+ rows), I was able to achieve the accuracy of ~95% 
for the dataset.

High Level Algo:
    1. Find the intent of the user and set the context for either booking restaurant/doctor
    2. Collect the parameters iteratively
    3. Filter and present the most appropriate results
    4. Send book instruction

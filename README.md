Problem : E-commerce Credibility Detection

We worked on an application that checks the reviews of a product listed for sale on an e-commerce platform, to detect whether it is a fraudulently listing, or if it is genuine, if so, it checks for its credibility as well. This would be implemented by two separate machine learning algorithms using sentiment analysis, with Tensorflow from Intel AI Analysis Kit/oneAPI.

Part 1 - Input of Product SKU, gathering all its consolidated reviews and grouping them together.


Part 2 - Checking for fraudulence in product listing : 
         Machine Learning model used - Stochastic Gradient Descent Classifier
         Dataset - Fake Reviews Dataset from osf.io
         Here, we check if each review is fake or not, classified by the SDG model, and the total count of genuine and fake reviews is taken and compared          to label it as fraudulent or not.
         
         
Part 3 - Checking for credibility in product listing : 
         Dataset: Amazon reviews dataset from Kaggle.
         Once we determine if a product is genuine, its credibility is also inferred, by checking for each review and its 'value', whether it is        a          positive or negative review. On comparing the overall ratings, we can determine if the product is credible.
         
         
 Team Name : The Spammers
 
 Team Members : 
 
 Ashwin Saji
 Ajith Bobby
 Alwin Shibu
 Ankit John Abraham
 
 Submitted for the Slash Key 2.0 Hackathon


       

# Dog-Breed-Classification-Project-ML
(The is a follow-along tutorial project done in the course "Complete AI & Machine Learning, Data Science Bootcamp" by Andrei N. & Daniel B.")

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.

In this project we're going to be using machine learning to help us identify different breeds of dogs by using "Unstructed data". Unstructtured datat is data you'll find outside of the traditional row and column structure (such as in an Excel spreadsheet or pandas DataFrame). Examples of unstructured data include images, audio and natural language. If you're working with these kinds of data sources, it's generally best to use deep learning, neural networks or transfer learning to gain insights out of them.

That's what this section focuses on.

To do this, we'll be using data from the Kaggle dog breed identification competition. https://www.kaggle.com/c/dog-breed-identification/overview.  It consists of a collection of 10,000+ labelled images of 120 different dog breeds.

This kind of problem is called "multi-class image classification". It's multi-class because we're trying to classify mutliple different breeds of dog. If we were only trying to classify dogs versus cats, it would be called binary classification (one thing versus another).

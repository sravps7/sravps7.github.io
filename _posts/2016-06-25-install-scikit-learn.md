---
layout: post
Title: Install scikit-learn library for Machine Learning
category: blog
---

So, for a project of mine, I had to work on Machine Learning with Python. I found this open source library: **scikit-learn** which had all the tools needed for machine learning.

Here is how you install it (on Ubuntu 14.04) :



The library requires Python of either of the following versions:

* 2.6 or greater
* 3.3 or greater



To check for the version of Python on your device using either of the following commands in the terminal: 
<p class="message">
	  python --version
</p>  

<p class="message">
	  python3 --version
</p>  

If either of them are not of a compatible version, then follow this link [here]( http://askubuntu.com/questions/101591/how-do-i-install-python-2-7-2-on-ubuntu/101595#101595 ) to upgrade.

**Similarly, make sure your NumPy version is greater than or equal to 1.6.1 and your SciPy version is greater than or equal to 0.9.** 

Then all you have to do is run the following command:

<p class="message">
	  pip install -U scikit-learn
</p> 

So if this works without any errors, then you can now use the library in your python code. All you have to do for that is to write a line in your code:

**from sklearn import xxxxx**

Here "xxxxx" would mean any particular thing you would want to import.

For example,

**from sklearn.cluster import KMeans** 

allows you to use the K-Means clustering algorithm in your code.

Go through the documentation and the example codes given on [this]( http://scikit-learn.org/stable/index.html ) website before you proceed further. They are very useful.

Thanks for reading! Hopes it helps!
# Active-Learning-for-GPPL-Preference-Learning-with-Humorousness-data-set

This is a final project for my Msc degree.

The work I do is to apply active learning for Predicting Humorousness with Gaussian Process Preference Learning.
The active learning methods I employed are random sample, BALD, BatchBALD and Replicas Reduced BALD.
Replicas Reduced BALD is a method I proposed to improve BALD by reducing same data points with lower computational time than BatchBALD.

Their codes can be found at https://github.com/UKPLab/acl2019-GPPL-humour-metaphor

My experiments results can be seen in the folders. You can see the visualized results in the .ipynb files in the folders.
500-10-1000 means the initial size of active learning is 500, batch size of active learning is 10 and the maximum training set is 1000.

The trained models are deleted becasue it's over the size limation of Github.

To run my code, you need download their codes first, meet their environmental requirements and add my codes in their python file.

For Replicas Reduced BALD:

``  
python run_experiments_myBALD.py humour 0 active
``  

For BALD:

``  
python run_experiments_BALD.py humour 0 active
``  

For BatchBALD:

``  
python run_experiments_Batch_BALD.py humour 0 active
``  

For Random Sample:

``  
python run_experiments_random_sample.py humour 0 active
``  

I'm only make sure my codes works well on humorous datasets in their repository.

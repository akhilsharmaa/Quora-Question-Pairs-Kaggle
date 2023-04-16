<p align="center" width="100%">
    <img width="25%" src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Kaggle_logo.png?20140912155123">
    <img width="10%" style='margin=:10px' src="https://static.wixstatic.com/media/a44da8_fd6bed84d4234271aa6c53350d454b42~mv2.png/v1/fill/w_260,h_260,al_c,q_85,usm_2.00_1.00_0.00,enc_auto/Kaggle%20Competition%20Logo%20Without%20Text.png"><img width="35%" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Quora_logo_2015.svg/1200px-Quora_logo_2015.svg.png">
</p>



# Quora Question Pairs [Competition](https://www.kaggle.com/c/quora-question-pairs) 

# **Method 1**: Random Forest
### **Accuracy using Random-Forest** : `0.73`

Apply random forest on the dataset directly, Let's see what is the accuracy.

# **Method 1.2**: Random Forest after *`feature engineering`*
### **Accuracy after feature eng. using Random-Forest** : `0.73`

In the feature engineering: *we will add this features in the data_frame*
  - `question1_lenght` - char lenght of question1 
  - `question2_lenght` - char lenght of question2 
  - `q1_word_count` - no. of words in the question1
  - `q2_word_count` - no. of words in the question2
  - `word_commmon` - common word in q1 & q2
  - `word_total` - Total word in q1 + q2
  - `word_share` - word_common / word-total


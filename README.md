# cv_study
Practice CV starting with the workout video set from kaggle:
https://www.kaggle.com/datasets/hasyimabdillah/workoutfitness-video/data

## Open issues:
1. currently, the model works on individual frames, but without the option to learn from consecutive frames about the flow of the workout. RNN?
2. the model should be a multi-class instead of multi-label, needs to be changed and checked.
3. frames are cut to 224,224; check the videos size to see if the 224,224 is a good choice or we lose info (or on the contrary- we can reduce size)

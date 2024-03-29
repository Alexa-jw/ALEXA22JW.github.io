## ALEXA Project

  ALEXA is telementoring project aim to providing prediction of medical instructions from videos of surgical procedures for the mentee system.

  The basic methodology is including two parts: First, create a database for surgery videos with annotations of each step in the operation. Second, train a Deep Learning model that could generate prediction of medical instructions from the videos. 

### Objective



```markdown
  The basic methodology is including two parts:

1. Create a database for surgery videos with annotations of each step in the operation;
2. Research, develop, and validate a Deep Learning model that could generate prediction of medical instructions from the videos.

```

### Dataset
- The dataset will collect surgical videos of different participants in the head mount view of the procedures. 
- The annotation of the action during surgeries will collected from the participants as an audio file format.
- The dataset is provide temporal context of actions.
- The dataset is split into train, validation and test set.


### Evaluation of Models
  The evaluation of the model will perform on the test datasets, which approximately 20% of the data of the entire dataset. Then, we will use different evaluation metrics (e.g. BLEU, METEOR, and SPICE) to evaluate the performance of the model by computing similarity score between the ground truth and the prediction. Besides the numerical evaluations, the expert emergency physician will also provide professional evaluations for the predictions. 


website: https://alexa-jw.github.io/ALEXA22JW.github.io/

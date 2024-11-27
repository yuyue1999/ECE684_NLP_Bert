## BERT-Based Emotion Classification

### Authors: Teng-Yu Hsiao, YiTao Shi, Yue Yu 
### NetID: th331,ys386,yy373

This project focuses on implementing a **BERT-based emotion classification model** to classify text inputs into predefined emotion categories such as `anger`, `fear`, `joy`, `love`, `sadness`, and `surprise`. The goal is to showcase the effectiveness of pre-trained NLP models like BERT in emotion recognition tasks.


### **Data**

- The training and testing data can be found in the `data/` directory.
- Modify or expand the dataset as needed to suit your experiment.

### **Usage**

1. Train and fine-tune the BERT model:
   - Follow the steps in `nlp_project_bert.ipynb` to preprocess the data, train the model, and evaluate its performance.

2. Perform emotion prediction on new text:
   - Use the `predict_emotion` function in the code to classify the emotion of any text input.

Example:

```python
text = "I'm feeling so sad today!"
predicted_emotion, probabilities = predict_emotion(text, model, tokenizer, emotion_labels, device=device)
print(f"Predicted Emotion: {predicted_emotion}")
print(f"Probabilities: {probabilities}")
```

### **Emotion Labels**

The model classifies text into the following emotion categories:
- `anger`
- `fear`
- `joy`
- `love`
- `sadness`
- `surprise`

### **Files Overview**

- `data/`: Contains training and testing datasets.
- `nlp_project_bert.ipynb`: Main notebook with steps to train, evaluate, and test the model.
- `model/`: Directory to save the trained BERT model and tokenizer.
- `README.md`: Instructions and details about the project.

### **Happy experimenting!** 🎉

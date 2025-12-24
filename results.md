Epoch	    Training Accuracy	     Validation Accuracy	      Validation Loss
 1	             93.53%	                 97.85%	                0.0687
 2	             98.26%	                 98.36%	                0.0425
 3	             99.13%	                 96.83%	                0.0884
 4	             98.95%	                 98.06%	                0.0485
 5	             99.00%	                 99.80%	                0.0073


• Final Accuracy: The model achieved a 99.80% Validation Accuracy, demonstrating exceptional generalization to unseen MRI images.
• Loss: The final Validation Loss of 0.0073 suggests high confidence in the model's classifications.
• Convergence: The accuracy plateaued quickly, underscoring the effectiveness of pre-trained weights in medical image analysis

Training Accuracy: 99%
(Measure of model success)
Testing Accuracy: 99.8%
Performance on unseen data

- The trained model successfully classified MRI images into:
  - **No Tumor**
  - **Positive Tumor**
- Predictions were visualized alongside MRI images using Matplotlib.
- Softmax probabilities were used to determine final class labels.

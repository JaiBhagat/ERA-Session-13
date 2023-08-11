## Assignment Overview

### Model Training Objectives

1. **Achieve Performance Metrics**:
    - Class accuracy > 75%
    - 'No Obj' accuracy > 95%
    - Object Accuracy:
        * > 70% if kernel numbers were reduced
        * > 80% otherwise

    - Aim to train the model for up to 40 epochs.

2. **Incorporate Training Enhancements**:
    - Integrate multi-resolution training (Note: provided code trains only on resolution 416).
    - Implement Mosaic Augmentation but limit its application to 75% of the time.
    - Train using float16 precision.
    - Integrate GradCAM visualization.

3. **Hardware Constraints Adaptations**:
    - Modifications in batch size are permitted.
    - Resolution adjustments are acceptable.
    - Alterations to OCP parameters are allowed.

### Deployment & Interface

1. **Hugging Face Spaces**:
    - Deploy the trained model on Hugging Face Spaces.
    - Allow users to upload custom images.
    - Provide sample images from the existing dataset.
    - Display the GradCAM output for both user-uploaded and sample images.

2. **Documentation**:
    - Specify the classes that the model recognizes.
    - Provide a direct link to the trained model.

### Assignment Deliverables

- [ ] **Hugging Face App**: Share the deployed app's link.
- [ ] **GitHub Repository**: Link to the Lightning code.
- [ ] **Training Notebook**: Share the link to the notebook containing the training logs on GitHub.


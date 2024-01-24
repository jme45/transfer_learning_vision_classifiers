# transfer_learning_vision_classifiers
> Package for creating classifiers for computer vision, based on transfer learning.


## Installation
pip install git+https://github.com/jme45/transfer_learning_vision_classifiers.git

## Usage example
```python
from transfer_learning_vision_classifiers import classifiers
classifier1 = classifiers.TransferLearningVisionClassifier("effnet_b2", 
                                                                ["cat", "dog"],
                                                                False)
```


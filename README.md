# NER-Sports-Certificate task


**Problem statement**
***The objective of this task is to build an NLP model that can extract specific pieces of information from sports certificates***. The information needed to be extracted includes -

- Participent name
- Winning position
- Sports name
- Year of organization

The task is to develop a model that can read and extract these pieces of information from the set of certificates. The model should also be adaptable to new certificates that means, if given a new type of certificate, model should be able to learn from it and then accurately extract the relevant information.

**Solution proposed**
- Since this is a task of Named Entity Recognition, 2 models have been used. To extract a person name, pre-trained BERT model has been used. To extract the Winning position, sports name and year of organization, spacy model has been used.

**Dataset used**
- The dataset has been provided with 300 certificates. The data has been manually extracted and is intended for training purposes.

### Teck stack used:
- Python
- FastAPI
- Deep learning
- Natural language processing
- BERT model
- Spacy model
### How to run

Step 1. Create conda environment
```anaconda prompt
conda create -p env python==3.9 -y
```
Step 2. Install necessary requirements
```anaconda prompt
pip install -r requirements.txt
```
Step 3. Rub the app.py file for training the model
```anaconda prompt
python app.py
```
Step 4. For inferencing run the prediction.py file.
```anaconda prompt
python prediction.py
```
Step 5. Training the model

`127.0.0.1:5000/train`

`127.0.0.1:5000/train/docs`

**Click** on following to start the training process:
1. `GET`
2. `Try it out`
3. `Execute`
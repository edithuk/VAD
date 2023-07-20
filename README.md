# VAD

## Training Stage
- Download the extracted I3D features of XD-Violence dataset from [here](https://roc-ng.github.io/XD-Violence/).
- Change the file paths of ```make_list.py``` in the list folder to generate the training and test list.
-  The hyperparameters are saved in ```option.py```, where we keep default settings as mentioned in our paper.
- Run the following command for training:
```
python main.py
```
## Test Stage
- Change the checkpoint path of ```infer.py```.
- Run the following command for test:
```
python infer.py
```

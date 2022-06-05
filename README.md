###	Modification of the original code
#### more information can be found in Part 4 of our report 

###	Environment Setup

Due to complicated dependency problems, you should follow the given installing order.
1. ```pip
   pip install -r "requirements.txt"
   ```

2. ```pip
   pip install -r "requirements_2.txt"
   ```

3. ```pip
   pip install -r "requirements_3.txt"
   ```
   
4. ```pip
   pip install numpy==1.18
   ```
   
5. ```pip
   pip install tensorboard==1.15
   ```
6. ```pip
   pip install ray==1.11
   ```

###	Simulation Data Generator

```python
python generator.py
```

###	Train

```python
python train.py
```
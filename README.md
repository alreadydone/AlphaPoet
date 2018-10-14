## AlphaPoet
*AlphaPoet* is one of works in 2018 International Collegiate Competition for Brain-inspired Computing Finals (国际大学生类脑计算大赛).    
Combining the power of Transfer Learning and Reinforcement Learing

## Requirements
* **Tensorflow r1.8.0**
* PIL (Pillow)
* Python 3.6
* CUDA 9.0 (For GPU)

## Structure
The structure of the system is shown below  
![structure](https://github.com/GeneZC/AlphaPoet/raw/master/img/structure.png)

## Result
Samples generated by the system with ONLY Supervised Learning and with Reinforment Learning  
![result](https://github.com/GeneZC/AlphaPoet/raw/master/img/result.png)

## Usage
- Modify the parameters in test.py to ensure the directory of the input image etc., for example
```python
DICO= 'tang.txt'
DICO_PKL = 'dict.pkl'
IMAGE = 'test/3.jpg'
```
- Run command in command line
```bash
python test.py
```

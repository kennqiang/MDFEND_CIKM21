# MDFEND: Multi-domain Fake News Detection
This is an official implementation for **MDFEND: Multi-domain Fake News Detection which has been accepted by CIKM2021**.
## Dataset
You can download the dataset **Weibo21** proposed in this paper only after an "Application to Use Weibo21 for Fake News Detection" has been submitted. 
## Code
### Requirements
refer to requirement.txt
### Data Preparation
After you download the **Weibo21** dataset (the way to access is described here), move the `train.pkl`, `val.pkl` and `test.pkl` into the path `MDFEND-Weibo21/data`.
### Run
You can run this model through:
```python
python main.py --model_name mdfend --batchsize 32 --lr 0.0007
```
### Reference
```
Nan Q, Cao J, Zhu Y, et al. MDFEND: Multi-domain Fake News Detection[C]//Proceedings of the 30th ACM International Conference on Information & Knowledge Management. 2021: 3343-3347.
```
or in bibtex style:
```
@inproceedings{nan2021mdfend,
  title={MDFEND: Multi-domain Fake News Detection},
  author={Nan, Qiong and Cao, Juan and Zhu, Yongchun and Wang, Yanyan and Li, Jintao},
  booktitle={Proceedings of the 30th ACM International Conference on Information \& Knowledge Management},
  pages={3343--3347},
  year={2021}
}
```

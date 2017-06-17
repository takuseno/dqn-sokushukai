## dqn-sokushukai
Sample DQN code for 速習会 in Wantedly.

`dqn.py` is based on original [dqn.py](https://github.com/chainer/chainerrl/blob/master/chainerrl/agents/dqn.py) in chainerrl without features not talken in the lecture.

## requirements
- Python3

## dependencies
- chainer==2.0.0
- gym[atari]
- chainerrl==0.2.0
- OpenCV3

## ussage
### training
```
$ python train.py --gpu {0 or -1} --render --final-steps 10000000
```

### playing
```
$ python play.py --gpu {0 or -1} --render --load {path of models}
```

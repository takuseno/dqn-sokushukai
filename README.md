## dqn-sokushukai
Sample DQN code for 速習会 in Wantedly.

## dependencies
- chainer
- gym[atari]
- chainerrl
- OpenCV3

## ussage
### training
```
$ python train.py --gpu {0 or -1} --render --finale-steps 10000000
```

### playing
```
$ python play.py --gpu {0 or -1} --render --load {path of models}
```

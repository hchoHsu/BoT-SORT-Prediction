# Kalman filter prediction research

This repo is to study the kalman filter on real time applcation for stablize the output of event predictions.

Using the KF and GMC from BoT-SORT

run:
```shell
$ python3 tools/demo-pred.py image --path ./MOT/MOT17/test/MOT17-01-DPM/ \
         -f yolox/exps/example/mot/yolox_x_mix_det.py \
         -c pretrained/bytetrack_x_mot17.pth.tar \
         --with-reid --fuse-score --fp16 --fuse --save_result
```
# LaserMark
This is the dataset released by LaserGuider accepted by the [Conference on Applied Cryptography and Network Security (ACNS’25)](https://acns2025.fordaysec.de/)
Traffic Signs Dataset with Laser Points as Backdoor Triggers

Folders:

- `origin`: Origin dataset images

- `added`: Added dataset images

## Images

Each image in LaserMark is names as the format:

`"-%d_%s_%s.jpg"%(index, label_encoding, color)`

There is four colors of laser points:

- 'r': red
- 'g': green
- 'b': blue
- 'c': clean(without laser points)

Here is the label-encodings of different traffic marks provided by TT100K.

<img src="marks.png" alt="Label-encodings" title="Label-encodings in LaserMark">

Below we list #pictures in each label in LaserMark. Notice that there are 60 pictures which do not belong to any labels in the former label-encodings, we mark them as label `uk`.

<img src="statistic.png" alt="Statistic of #pictures in each label" title="Statistic of #pictures in each label">

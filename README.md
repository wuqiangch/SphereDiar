# SphereDiar: an efficient speaker diarization system for meeting data

To use the system, setup an environment with:

```
Keras >= 2.2.4 
Tensorflow-gpu >= 1.10.1
spherecluster, https://github.com/jasonlaska/spherecluster
Multicore-TSNE, https://github.com/DmitryUlyanov/Multicore-TSNE
scikit-learn
librosa
joblib
wavefile
```

Citation:

```
@inproceedings{kaseva2019spherediar,
  title = {SphereDiar - an efficient speaker diarization system for meeting data},
  author = {Tuomas Kaseva and Aku Rouhe 
            and Mikko Kurimo},
  booktitle = {2019 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)},
  year = {2019},
}
```

Check demo.ipynb for further usage instructions.

### Speaker verification results with Voxceleb1 test set:

| Model  | Aggregation | Distance metric | EER (%) |
| ------------- |-----| ------| ---- |
| SphereSpeaker  |Average| Cosine | 6.2  |
| SphereSpeaker 200 |Average| Cosine | 5.2 |
| Current best |Average| Cosine | 2.2 |


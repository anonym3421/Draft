<p align="center">
  <img src="zoo.csv.png" height="250px" hspace="20">
  <img src="Yale.mat.png" height="250px" hspace="20">
  <img src="ecoli.data.png" height="250px" hspace="20">
</p>

<p align="center">
  <img src="movement_libras.csv.png" height="250px" hspace="20">
  <img src="mp_exp.txt.png" height="250px" hspace="20">
  <img src="usps.t.png" height="250px" hspace="20">
</p>

<p align="center">
  <img src="ctg.txt.png" height="250px" hspace="20">
  <img src="segment.dat.png" height="250px" hspace="20">
  <img src="GCM.csv.png" height="250px" hspace="20">
  <img src="fmnist.csv.png" height="250px" hspace="20">
</p>

In terms of deeper analysis, we also compute the distribution of the entropy of the softmax in the AM update equation (4) for the selected $\beta$ after the ClAM training, and see that, across multiple datasets, the entropy distribution spikes at zero, indicating that, for most points, the softmax puts all the probability mass on the closest prototype, which is the desired behavior.
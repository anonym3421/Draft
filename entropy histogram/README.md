<div>
  <figure>
    <img src="zoo.csv.png" height="150px" hspace="10">
    <figcaption>Zoo<figcaption>
  </figure>
  <figure>
    <img src="Yale.mat.png" height="150px" hspace="10">
    <figcaption>Yale</figcaption>
  </figure>
  <figure>
    <img src="ecoli.data.png" height="150px" hspace="10">
    <figcaption style="text-align:right;">Ecoli</figcaption>
  </figure>
</div>

<div>
  <figure>
    <img src="zoo.csv.png" title="Zoo" height="150px" hspace="10">
    <figcaption style="text-align:right;">Zoo</figcaption>
  </figure>
  <figure>
    <img src="Yale.mat.png" title="Yale" height="150px" hspace="10">
    <figcaption style="text-align:left;">Yale</figcaption>
  </figure>
  <figure>
    <img src="ecoli.data.png" title="Ecoli" height="150px" hspace="10">
    <figcaption style="text-align:left;">Ecoli</figcaption>
  </figure>
</div>

<!-- <p align="center">
  <img src="zoo.csv.png" title="Zoo" height="200px" hspace="10">
  <img src="Yale.mat.png" title="Yale" height="200px" hspace="10">
  <img src="ecoli.data.png" title="Ecoli" height="200px" hspace="10">
</p> -->

<!-- <p align="center">
  <img src="movement_libras.csv.png" height="200px" hspace="10">
  <img src="mp_exp.txt.png" height="200px" hspace="10">
  <img src="usps.t.png" height="200px" hspace="10">
</p>

<p align="center">
  <img src="ctg.txt.png" height="150px" hspace="10">
  <img src="segment.dat.png" height="150px" hspace="10">
  <img src="GCM.csv.png" height="150px" hspace="10">
  <img src="fmnist.csv.png" height="150px" hspace="10">
</p> -->

In terms of deeper analysis, we also compute the distribution of the entropy of the softmax in the AM update equation (4) for the selected $\beta$ after the ClAM training, and see that, across multiple datasets, the entropy distribution spikes at zero, indicating that, for most points, the softmax puts all the probability mass on the closest prototype, which is the desired behavior.
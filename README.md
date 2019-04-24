# Zurich Bicycle Dataset

```
├── Zurich_Bicycle_Dataset/
│    ├── DSCN2571/
│    ├── GOPR0200/
│    ├── GOPR0255/
│    ├── GOPR0265/
│    ├── GOPR0366/
│    ├── GOPR0369/
│    ├── GOPR0382/
│    ├── GOPR0386/
├── LICENSE.mit.md
├── README.md
```

The *Zurich Bicycle* dataset has been derived from the open-source Zürich Bicycle dataset developed for the original [DroNet](https://github.com/uzh-rpg/rpg_public_dronet) algorithm by the [RPG](http://rpg.ifi.uzh.ch/) from the University of Zürich (UZH).
Part of it is redistributed here with modified resolution, and in gray-scale to match the configuration of our ultra-low-power camera.
This release includes the same test set used in the original [DroNet](https://github.com/uzh-rpg/rpg_public_dronet).
It is composed of 8564 `.pgm` images with resolution 324x244, each tagged with a 0/1 collision label.
Each sub-folder contains a variable number of gray-scale `.pgm` images, ordered by number (e.g., `frame_1.pgm`, `frame_2.pgm`, etc.) and one `labels.txt` file with all the ground-truth labels in the same order.

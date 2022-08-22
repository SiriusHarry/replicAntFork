# FARTS
Fabi And René's Training-data Synthesizer

Generating synthetic datasets to improve inference on all sorts of computer-vision tasks involving insects.

# External files

Additional assets need to be dowloaded and placed into the content folder, which are hosted externally under the following link:
[Google Drive](https://drive.google.com/file/d/1FiboPJmrhqv6cDB2Ara-2n3-yDdHg0sh/view?usp=sharing)

# Generator TODOs

(Hosted externally in HacknPlan for now)

# Parser TODOs

* Update all parsers to use new **json** data format
  * YOLO
    * DONE
  * DLC
    * DONE
  * HERO DLC
    * DONE
  * COCO
    * DONE
  * Custom 3D
    * read in new json format files
    * check new 3D camera intrinsics and extrinsics and ensure the reprojected 3D coordinates align with the original 2D coordinates

* Generate new example datasets
  * Single
  * Multi

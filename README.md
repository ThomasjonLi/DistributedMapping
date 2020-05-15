# DistributedMapping

## Requirements
* [Eigen](http://eigen.tuxfamily.org)
* [g2o](https://github.com/RainerKuemmerle/g2o)
* [Sophus](https://github.com/strasdat/Sophus)
* [evo](https://github.com/MichaelGrupp/evo)(optional)

## Compilation
```
mkdir build
cd build
cmake ..
make -j4
./kitti(or ./sphere)
```

## Data/1/
```
x.g2o :initial poses
x_optimized.g2o :optimized poses
x_optimizedTUM.txt :optimized posed(TUM format)
initial.g2o	:total initial poses
fullGraph_optimized :optimized and merged poses
centralizedxxx.g2o :merged and optimized poses
```
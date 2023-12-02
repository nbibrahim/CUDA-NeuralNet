# FEED FORWARD NEURAL NETWORKS DONE WITH CUDA

- To run: 
  - sh get_data.sh 
  - nvcc \*.cu layers/\*.cu nn_utils/\*.cu -std=c++11 -o main 
  - ./main

all:
	nvcc  -arch=sm_35 --use_fast_math -lineinfo  --maxrregcount=32 --ptxas-options=-v try.cu  -O3  -o streams

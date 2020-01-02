tmake: ./src/main.cpp 
	icpc ./src/main.cpp -o APES -qopenmp -qopt-report5 -qopt-report-phase=openmp,vec  -std=c++14 -O3  -g -xCORE-AVX2 `gsl-config --cflags --libs` -I/opt/intel/advisor/include #-I$(HOME)/parallelstl/include -tbb 


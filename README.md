# N-body-Simulation-OpenMP

## Executable generate
* Create exe: "make" in the src folder 

Ex:

   cd ./src_files

   make

## Run
* Run:  ./nbody_simulation <path_for_the_input_file> 

* Change number of Threads to be used:  export OMP_NUM_THREADS=<number_of_threads>
* Run small input: ./nbody_simulation ../input_files/nbody_input-16384_16384.in
* Run big input: ./nbody_simulation ../input_files/nbody_input-32768_32768.in

Ex:

   export OMP_NUM_THREADS=4

   ./nbody_simulation ../input_files/nbody_input-16384_16384.in
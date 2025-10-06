#To compile and run the folder: Fault_simulation-version2_Model9.zip, Simulation_LESS_FaultCalculation_Model5.zip, and Simulation_LESS_Forgery Process.zip  

##Download and extract each file  

To build the benchmarking binaries, type ./build.sh.  

To clean the built files, type ./clean  

Go to the bin directory to find the executable binaries. To change the simulation parameters, go to the file Test_codes/lib/less_test_fault.c and set the parameters as macros. Here are the following parameters:  

Fault_simulation-version2_Model9: We changed the code in the Reference_Implementation/lib/seedtree.c file such that it provides the same effect of skipping the “parent_node=PARENT(current_node)+(off[h-1]/2)” for current_node=65  

Fault_simulation-version2_Model5: We changed the code in the Reference_Implementation/lib/seedtree.c file such that it provides the same effect of changing the flag[4] value from 1 to 0 

It checks whether our generated signature using the permutation is working 

 

To Compile and Run the folder: LESS_v2_attack-main_OneParmutation_Recovery.zip  

Download and extract the file: ESS_v2_attack-main_OneParmutation_Recovery.zip  

For one permutation recovery run the following commands:  

cd LESS_v2_attack-main_OneParmutation_Recovery/LESS_v2_attack-main/Utilities/Benchmarking/  

mkdir build  

cd build  

cmake ../  

make  

./LESS_benchmark_cat_252_45 (replace the last number parameter wise) 

 

### To compile and run the folder: Fault_simulation-version2_Model9.zip, Simulation_LESS_FaultCalculation_Model5.zip, and Simulation_LESS_Forgery Process.zip  

1. Download and extract each file  

2. To build the benchmarking binaries, type ./build.sh.  

3. To clean the built files, type ./clean  

4. Go to the bin directory to find the executable binaries. To change the simulation parameters, go to the file Test_codes/lib/less_test_fault.c and set the parameters as macros. Here are the following parameters:  

    a. Fault_simulation-version2_Model9: We changed the code in the Reference_Implementation/lib/seedtree.c file such that it provides the same effect of skipping the “parent_node=PARENT(current_node)+(off[h-1]/2)” for current_node=65  

    b. Fault_simulation-version2_Model5: We changed the code in the Reference_Implementation/lib/seedtree.c file such that it provides the same effect of changing the flag[4] value from 1 to 0 

    c. It checks whether our generated signature using the permutation is working 

 

### To Compile and Run the folder: LESS_v2_attack-main_OneParmutation_Recovery.zip  

1. Download and extract the file: ESS_v2_attack-main_OneParmutation_Recovery.zip  

2. For one permutation recovery run the following commands:  

    a. cd LESS_v2_attack-main_OneParmutation_Recovery/LESS_v2_attack-main/Utilities/Benchmarking/  

    b. mkdir build  

    c. cd build  

    d. cmake ../  

    e. make  

    f. ./LESS_benchmark_cat_252_45 (replace the last number parameter wise) 

 

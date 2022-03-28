# LabA-no.8
Dataflow Viewer , FIFO sizing and deadlocks

# 1. Dataflow Viewer

found in the `src/dataflow` folder.

the following command: 

```C++
vitis_hls -p script.tcl
```

Click the green Run Icon ![image](https://user-images.githubusercontent.com/102540321/160496680-c34216b5-aa40-47d7-95f2-c04b6974bace.png)

 to synthesize the design.

Right-click on the top-level function name (diamond) and select the Open Dataflow Viewer command to open a new Dataflow viewer window for the function as shown below.

![image](https://user-images.githubusercontent.com/102540321/160496887-d276d891-3ce3-49e3-b411-78af40d1201a.png)

##  RTL Co-simulation
select the Solution > Run C/RTL Co-Simulation command.

![image](https://user-images.githubusercontent.com/102540321/160496916-297c7980-e368-44b0-8568-3b416127e6ae.png)

Enable the Channel (PIPO/FIFO) Profiling checkbox.

![image](https://user-images.githubusercontent.com/102540321/160496939-8da6d064-9abb-4ee4-8204-7b92585b5b7c.png)

Click OK.

##  Dataflow Performance Using Waveform
select the Solution > Run C/RTL Co-Simulation command.

![image](https://user-images.githubusercontent.com/102540321/160497179-c6124c5e-7666-4f23-a9e3-05dcf2ef4c2b.png)

Using **Vivado XSIM** simulator.

Dump Trace choose **all**.

Enable the **Wave Debug** checkbox.

Enable the **Channel (PIPO/FIFO) Profiling** checkbox.

![image](https://user-images.githubusercontent.com/102540321/160497217-4dde628b-9869-4706-8d1e-71d5fa19a910.png)

**Waveform**

![image](https://user-images.githubusercontent.com/102540321/160497755-0a5f7ee6-495d-46a3-8438-5bc215e89440.png)

![image](https://user-images.githubusercontent.com/102540321/160497778-4764de4b-5ea2-4750-b973-828c47b99a01.png)

![image](https://user-images.githubusercontent.com/102540321/160497784-d1967afe-1a6b-4f1a-820e-32ea6ac5c30b.png)

# 2. FIFO Sizing And Avioding Deadlocks

found in the `src/deadlock` folder.

the following command: 

```C++
vitis_hls -p script.tcl
```

Click the green Run Icon ![image](https://user-images.githubusercontent.com/102540321/160496680-c34216b5-aa40-47d7-95f2-c04b6974bace.png)

 to synthesize the design.

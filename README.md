# IMD-DCDP-design
## Global variable identifier
the number in front of a global variable is used to differentiate different bodies 

| ID No.  | Body |
| ------------- | ------------- |
| 1.  | Hot Gas Distributor  |
| 2.  | Drying Drum  |

## Modifying the amount of miniPipes 
### 1. Roll back timeline to "#ABOVE_THIS" (Optional)
![](https://github.com/saltyfishie98/IMD-DCDP-design/blob/master/assets/miniPipeNumDemo_step1.gif)

### 2. Modify the amount in the desired section
Global variable "1. 1sec2_numColumnSet" controls the amount of miniPipes in section 2 of the 
distributor; same goes to section 3 and 4 with it respective global variable
![](https://github.com/saltyfishie98/IMD-DCDP-design/blob/master/assets/miniPipeNumDemo_step2.gif)

### 3. Roll forward slowly and fix resulting errors

## Buildchecks
check if the build would be successful. if the value in "Evalutes to" is <br/>
1(all): build would most likely be successful <br/>
0: build would most likely cause errors <br/>	

Example:
![](https://github.com/saltyfishie98/IMD-DCDP-design/blob/master/assets/checksDemo.gif)

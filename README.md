# MDP REPRESENTATION

## AIM:
To reach the goal of making air traffic better for a planes to take-off quickly.
## PROBLEM STATEMENT:
```
Name   : Shyam Kumar A
Reg No : 212221230098
```
### Problem Description
Reducing the air traffic using reinforcement learning.
### State Space
{R1,R2,R3}->{0,1,2}

R1-> Runway 1
R2-> Runway 2
R3-> Runway 3

### Sample State
R1-> 0 -> Runway 1

### Action Space
L - Left
S - Stop
R - Right

### Sample Action
R -> 2 -> Right
### Reward Function
```
R = {
    +1, if the plane has free runway to takeoff.
    +0, otherwise.
}
```


### Graphical Representation
![image](https://github.com/ShyamKumar-AI-DS/mdp-representation/assets/93427182/0e7e311f-4edf-40e9-be6f-715d1d761499)


## PYTHON REPRESENTATION:
```
T = {
    0 : {
        0 : [(1.0, 1, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    1 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    2 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 1, 0.0, False)]
    }
}

T
```

## OUTPUT:
![image](https://github.com/ShyamKumar-AI-DS/mdp-representation/assets/93427182/7950bd33-8326-4585-9414-8612c15fe88e)


## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.
Text representation, Graphical representation, Python - Dictonary representation.


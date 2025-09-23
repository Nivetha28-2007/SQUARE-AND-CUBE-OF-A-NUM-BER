# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END
```

## OUTPUT
<img width="292" height="316" alt="Screenshot 2025-09-22 232633" src="https://github.com/user-attachments/assets/54ebd10f-0cc7-4f19-ba25-8b01e875b650" />

<img width="793" height="275" alt="Screenshot 2025-09-22 232737" src="https://github.com/user-attachments/assets/9e087310-c928-4eb1-a648-d7a79bbf6fb5" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END
```
## OUTPUT
<img width="277" height="343" alt="Screenshot 2025-09-23 100712" src="https://github.com/user-attachments/assets/24833e20-e8b2-4d60-9dd1-a4e83a0d8a74" />

<img width="641" height="300" alt="Screenshot 2025-09-23 100803" src="https://github.com/user-attachments/assets/1cb47169-2d78-44d4-a44f-84ecf4d79d71" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.

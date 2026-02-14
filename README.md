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
ORG 0000H
	MOV R0,#50H
	MOV A,@R0
	MOV B,@R0
	MUL AB
	INC R0
	MOV @R0,A
	END
```

## OUTPUT
![b2882a22-6b41-4f9e-83cc-f715332e48b1](https://github.com/user-attachments/assets/c8d2d99d-33a7-4549-a47b-25d0ec16bee7)


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
![bca67c03-2478-48ef-8056-f294e011d549](https://github.com/user-attachments/assets/461ec3de-5ec6-4bf9-af86-940df3f7d018)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.

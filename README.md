# C Programming Assignment 4

## How to Run the Project
* Prerequisite
    * Software: C.
    * Operating System: Linux based.
### Section1: Randomness in Computation
* For question 1, Please execute the following command: 
    ```
    gcc 1.c
    ./a.out
    ```
* For question 2, Please execute the following command: 
    ```
    gcc 2.c
    ./a.out
    ```
* For question 3, Please execute the following command: 
    ```
    gcc 3.c
    ./a.out
    ```
* The graph for the estimation of value of π
### Section2: Streaming Computations
* For question 4(a), Please execute the following command:
    ```
    gcc 4a.c
    ./a.out <file_name_input.txt> <file_name_mean.txt>

    Note: Here file_name_input.txt is the file from where it reads the data.
    file_name_mean.txt is the file where mean is to be written.
    ```
* For question 4(b), Please execute the following command:
    ```
    gcc 4b.c
    ./a.out <file_name_input.txt> <file_name_mean.txt> <file_name_variance.txt>

    Note: Here file_name_input.txt is the file from where it reads the data.
    file_name_mean.txt is the file from where it reads the mean.
    file_name_variance.txt is the file where variance is to be written.
    ```
* For approximate variance, Please execute the following command:
    ```
    gcc approxVar.c
    ./a.out <file_name_input.txt> <file_name_approxvar.txt>

    Note: Here file_name_input.txt is the file from where it reads the data.
    file_name_approxvar.txt is the file where approximate variance is to be written.
    ```
* The graph for the approximate variance and the real variance is:
### Section3: Cryptography and Bit Manipulation
* For question 5(a), Please execute the following command:
    ```
    gcc 5a.c
    ./a.out
    ```
* For question 4(b), Please execute the following command:
    ```
    gcc 5b.c
    ./a.out
    ```
* For question 5c, there are two subprograms named 5c_encrypt.c and 5c_decrypt.c
    * For 5c_encrypt.c:
        ```
        gcc 5c_encrypt.c
        ./a.out <file_name_message.txt> <file_name_key.txt> <file_name_enstr.txt>

        Note: Here file_name_message is the file that contains message to be encrypted.
        file_name_key.txt is the file where 127 bit seed is stored.
        file_name_enstr.txt is the file in while in the encrypted string is written.
        ```
    * For 5c_decrypt.c:
        ```
        gcc 5c_decrypt.c
        ./a.out <file_name_key.txt> <file_name_enstr.txt> <file_name_destr.txt>

        Note: Here file_name_key.txt and file_name_enstr.txt are same as the files in 5c_encrypt.c.
        file_name_destr.txt is the file in while in the decrypted meassage is written.
        Decrypted message is same as the input message.
        ```
### Section4: Data on the Disk
* For question 6, Please execute the following command:
    ```
    gcc 6.c
    ./a.out <file_name_out.txt> <file_name_in1.txt> <file_name_in2.txt>

    Note: Here file_name_out.txt is the file where the output is written.
    file_name_in1.txt, file_name_in2.txt are input data files.
    Number of input files can be anything i.e., 2, 3, 4, 5, ... we can add the input files in CLI sequentially i.e., in1, in2, in3, ...
    ```
* For question 7, Please execute the following command:
    ```
    gcc 7.c
    ./a.out <file_name_out.txt> <file_name_in1.txt> <file_name_in2.txt>

    Note: Here file_name_out.txt is the file where the output is written.
    file_name_in1.txt, file_name_in2.txt are input data files.
    Number of input files can be anything i.e., 2, 3, 4, 5, ... we can add the input files in CLI sequentially i.e., in1, in2, in3, ...
    ```
* For question 8, Please execute the following command:
    ```
    gcc 8.c
    ./a.out <file_name_out.txt> <file_name_in1.txt> <file_name_in2.txt>

    Note: Here file_name_out.txt is the file where the output is written.
    file_name_in1.txt, file_name_in2.txt are input data files.
    ```
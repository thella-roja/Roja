       IDENTIFICATION DIVISION.
       PROGRAM-ID. ADD-TWO-NUMBERS.

       ENVIRONMENT DIVISION.
       INPUT-OUTPUT SECTION.

       DATA DIVISION.
       WORKING-STORAGE SECTION.
       01  NUM1           PIC 9(4) VALUE 0.
       01  NUM2           PIC 9(4) VALUE 0.
       01  RESULT         PIC 9(5) VALUE 0.

       PROCEDURE DIVISION.
       MAIN-PROCEDURE.
           DISPLAY "Enter the first number: " WITH NO ADVANCING.
           ACCEPT NUM1.
           DISPLAY "Enter the second number: " WITH NO ADVANCING.
           ACCEPT NUM2.

           COMPUTE RESULT = NUM1 + NUM2.

           DISPLAY "The sum of the two numbers is: " RESULT.

           STOP RUN.

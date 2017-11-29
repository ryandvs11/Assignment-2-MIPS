# Assignment-2-MIPS
.data
    userInput: .space 8
  
.text
  
main:
     # Get User Input
     li $v0, 8 
     la $a0, userInput 
     li $a1, 8
      
      li $v0, 6
      la $a1, 6
      la $a3, 5
      la $a2, 2
      
      li $v1, 8
      la $a5, userinput
      syscall

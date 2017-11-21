# Assignment-2-MIPS
.data
    userInput: .space 8
  
.text
  
main:
     # Get User Input
     li $v0, 8 
     la $a0, userInput 
     li $a1, 8
      syscall

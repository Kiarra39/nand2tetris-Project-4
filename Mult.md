	 @sum
	 M=0   //sum=0
	 @i
	M=1   //i=1
	 (LOOP)
	 @i    
	D=M   //D=i
	@R0
	D=D-M //D=i-R0
	@END
	D;JGT  // if(i-R0) > 0 goto END
	@R1
		D=M   //D=R1
	@sum
	M=D+M  //sum+=R1
	@i
	M=M+1  //i=i+1
	@LOOP
	0;JMP  //Goto LOOP
	(END)
	@sum
	D=M
	@R2
	M=D 

![image](https://github.com/user-attachments/assets/f6363002-6060-42c7-be3b-837107148163)



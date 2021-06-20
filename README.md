# Nice_code_lines

############################################################
# LIST COMPREHENSION HAVING IF ELSE CONDITION #
# ##########################
#list comphrension multiple

print([str(i)+"fuzz" if i %3==0 else str(i)+"buzz" if i%5==0 else  str(i)+"fizzbuzz" if i%3==0 and i%5==0 else str(i) for i in range(100)])

#########################################
# Taking 4 input one line
x,y,z,n=(int(input()) for _ in range(4))
print([[a,b,c] for a in range(0,x+1) for b in range(0,y+1) for c in range(0,z+1) if a+b+c !=n])
#########################################

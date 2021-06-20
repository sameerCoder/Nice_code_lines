# Nice_code_lines

############################################################
# LIST COMPREHENSION HAVING IF ELSE CONDITION #
# ##########################
#list comphrension multiple

print([str(i)+"fuzz" if i %3==0 else str(i)+"buzz" if i%5==0 else  str(i)+"fizzbuzz" if i%3==0 and i%5==0 else str(i) for i in range(100)])

#########################################

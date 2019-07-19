# an elementary calculator code

num_1 = input('Enter the first digit')

num_2 = input('Enter the second digit')

operator = input('Enter the operation sign')

if num_1.isdigit() and num_2.isdigit():

   num_1 = int(num_1)
   
   num_2 = int(num_2)
   

result = None

if operator == '+':

   result = num_1 + num_2
   
elif operator == '-':

   result = num_1 - num_2
   
elif operator == '/':

   result = num_1 / num_2
   
elif operator == '*':

   result = num_1 * num_2
   
else:

    print('Unknown Operator!')
    
if result!= None:

    print('{} {} {} = {}'.format(
    
       num_1,
       
       operator,
       
       num_2,
       
       result))
       

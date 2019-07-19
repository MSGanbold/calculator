#calculator
num_1 = input('Enter the first digit')\n
num_2 = input('Enter the second digit')\n
operator = input('Enter the operation sign')\n

if num_1.isdigit() and num_2.isdigit():\n
   num_1 = int(num_1)\n
   num_2 = int(num_2)\n

result = None\n
if operator == '+':\n
   result = num_1 + num_2\n
elif operator == '-':\n
   result = num_1 - num_2\n
elif operator == '/':\n
   result = num_1 / num_2\n
elif operator == '*':\n
   result = num_1 * num_2\n
else:\n
    print('Unknown Operator!')\n
if result!= None:\n
    print('{} {} {} = {}'.format(\n
       num_1,\n
       operator,\n
       num_2,\n
       result))\n

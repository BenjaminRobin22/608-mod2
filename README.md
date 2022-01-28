{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "369bd2d6-273a-4176-a3f2-c0e16af7caec",
   "metadata": {},
   "outputs": [],
   "source": [
    "# This is Ben Robin's 2nd project"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "7205f2d0-0f80-4410-8290-5cba8b324254",
   "metadata": {},
   "outputs": [],
   "source": [
    "#3.1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "ac036675-00b9-4439-8b62-faaa51343657",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter first integer:  10\n",
      "Enter second integer:  5\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The sum of 10 and 5 is 15\n"
     ]
    }
   ],
   "source": [
    "number1 = int(input('Enter first integer: '))\n",
    "number2 = int(input('Enter second integer: '))\n",
    "\n",
    "total = number1 + number2\n",
    "\n",
    "print( 'The sum of' , number1, 'and' , number2 , 'is' ,total)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "1b30905a-1dde-4c7f-9542-088cbd052203",
   "metadata": {},
   "outputs": [],
   "source": [
    "# 3.5 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "246c6b72-0fde-485d-9eb9-4d3638547f7a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Passed\n"
     ]
    }
   ],
   "source": [
    "grade = 85\n",
    "\n",
    "if grade >= 60:\n",
    "    print('Passed')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "c278f228-3058-46c8-9437-7bfba4d500d1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Passed\n",
      "Good Job!!\n"
     ]
    }
   ],
   "source": [
    "if grade >=60:\n",
    "    print('Passed')\n",
    "    print('Good Job!!')\n",
    "    "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "bfedd5be-5131-451e-8e94-1506679b20ba",
   "metadata": {},
   "outputs": [],
   "source": [
    "#3.5b"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "e4908ce1-d5cd-4a4c-a54a-e06b45123d70",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Passed\n"
     ]
    }
   ],
   "source": [
    "grade = 85\n",
    "\n",
    "if grade >= 60:\n",
    "    print('Passed')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "0e3df3be-e74c-49c9-9c98-58bd2f08e699",
   "metadata": {},
   "outputs": [],
   "source": [
    "#3.6 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "425d38ba-63c2-4f30-a5d3-a2a62539c661",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Failed\n"
     ]
    }
   ],
   "source": [
    "grade = 57\n",
    "\n",
    "if grade >= 60:\n",
    "    print('Passed')\n",
    "else:\n",
    "    print('Failed')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "id": "58c87b59-c0a6-4ea2-b321-dbf6e30e7d41",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Passed'"
      ]
     },
     "execution_count": 13,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "grade = 60 \n",
    "\n",
    "result = ('Passed' if grade>= 60 else 'Failed')\n",
    "result"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "id": "8a59e058-7db8-498a-b7e9-a63c89671be4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Passed\n",
      "You must take this course again\n"
     ]
    }
   ],
   "source": [
    "grade = 61 \n",
    "\n",
    "if grade >=60:\n",
    "    print('Passed')\n",
    "else: \n",
    "    print('Failed')\n",
    "print('You must take this course again')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "id": "de9e951b-28d8-4a4f-a9fd-a343311af772",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "B\n"
     ]
    }
   ],
   "source": [
    "grade = 87\n",
    "\n",
    "if grade >=90:\n",
    "    print('A')\n",
    "elif grade >=80:\n",
    "    print('B')\n",
    "elif grade >=70:\n",
    "    print('C')\n",
    "elif grade >=60:\n",
    "    print('D')\n",
    "else:\n",
    "    print('F')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "id": "35ba9a1f-13be-475d-9198-976a71b15dc8",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "81"
      ]
     },
     "execution_count": 16,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "product = 3 \n",
    "\n",
    "while product <= 50:\n",
    "    product = product * 3\n",
    "    \n",
    "product"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "id": "dbd86d70-1e91-4c1a-a5d4-f7d7e20355c8",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2401"
      ]
     },
     "execution_count": 17,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "product = 7 \n",
    "\n",
    "while product <= 1000:\n",
    "    product = product * 7 \n",
    "\n",
    "product"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 18,
   "id": "d89b1f42-6908-4254-9fef-3e7865d8c1ff",
   "metadata": {},
   "outputs": [],
   "source": [
    "#3.8 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "id": "890b42e3-8ffd-4bfe-a278-ff7a2adb4422",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "P--r--o--g--r--a--m--i--n--g--"
     ]
    }
   ],
   "source": [
    "for character in 'Programing':\n",
    "    print(character, end='--')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "id": "a71916df-a9d6-4cbb-9030-649a1847c92e",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "25"
      ]
     },
     "execution_count": 22,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "total = 0 \n",
    "\n",
    "for number in [2, -3, 0, 17, 9]:\n",
    "    total = total + number\n",
    "    \n",
    "total"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "id": "2ab14f8a-0b4a-498b-9791-2a7b08be8ce4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0, 1, 2, 3, 4, 5, 6, 7, 8, 9, "
     ]
    }
   ],
   "source": [
    "for counter in range(10):\n",
    "    print(counter, end=', ')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "id": "b0d6be7f-462f-408e-87f8-22d0d9f2c711",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "500000500000"
      ]
     },
     "execution_count": 24,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "total = 0 \n",
    "\n",
    "for number in range(1000001):\n",
    "    total = total + number\n",
    "    \n",
    "total"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "id": "baad87cf-ad1e-4335-a642-7e427435edd6",
   "metadata": {},
   "outputs": [],
   "source": [
    "# 3.9"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "id": "f3b984a2-e514-480e-a929-64b56235b450",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "15"
      ]
     },
     "execution_count": 26,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "total = 0\n",
    "for number in [1, 2, 3, 4, 5,]:\n",
    "    total += number\n",
    "\n",
    "total"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 27,
   "id": "bc5eab87-c1d4-4e47-b39b-68d2ef659c3a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "144"
      ]
     },
     "execution_count": 27,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "x = 12\n",
    "\n",
    "x **=2\n",
    "\n",
    "x"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "id": "d6c397f3-3f56-4f70-9363-ea346e93a546",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Class average is 81.7\n"
     ]
    }
   ],
   "source": [
    "# fig03_01.py Class average program with sequence-controlled repetition\n",
    "# initialization phase\n",
    "total = 0 # sum of grades\n",
    "grade_counter = 0 \n",
    "grades= [98, 76, 71, 87, 83, 90, 57, 79, 82, 94] # list of 10 grades \n",
    "\n",
    "#processing phase \n",
    "for grade in grades:\n",
    "    total += grade # add current grade to the running total \n",
    "    grade_counter +=1 #indicate that one more grade was processed\n",
    "    \n",
    "#termination phase\n",
    "average = total/grade_counter\n",
    "print(f'Class average is {average}')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "id": "b2bf0dba-34f9-45b9-8f2d-6688bfc6694a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "7 times 5 is 35\n"
     ]
    }
   ],
   "source": [
    "numberA = 7 \n",
    "numberB = 5\n",
    "print(f'{numberA} times {numberB} is {numberA * numberB}') "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 30,
   "id": "274cf541-c3f7-4340-bed7-4276df83014d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter grade, -1 to end:  97\n",
      "Enter grade, -1 to end:  88\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Class average is 97.00\n"
     ]
    },
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter grade, -1 to end:  72\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Class average is 92.50\n"
     ]
    },
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter grade, -1 to end:  -1\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Class average is 85.67\n"
     ]
    }
   ],
   "source": [
    "#fig03_02.py\n",
    "\"\"\"Class Average program with sentinal-controlled iterations. \"\"\"\n",
    "\n",
    "#initialization phase\n",
    "total = 0 # sum of grades \n",
    "grade_counter = 0 #number of grades entered\n",
    "\n",
    "#processing phase \n",
    "grade = int(input('Enter grade, -1 to end: ')) #get one grade\n",
    "\n",
    "while grade != -1:\n",
    "    total += grade\n",
    "    grade_counter += 1\n",
    "    grade = int(input('Enter grade, -1 to end: '))\n",
    "\n",
    "    #termination phase\n",
    "    if grade_counter != 0: \n",
    "        average = total / grade_counter\n",
    "        print(f'Class average is {average:.2f}')\n",
    "    else:\n",
    "        print('No grades were entered')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 33,
   "id": "f5a40d90-47ab-486f-a18f-2e18920ab675",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter result (1=pass, 2=fail):  1\n",
      "Enter result (1=pass, 2=fail):  1\n",
      "Enter result (1=pass, 2=fail):  2\n",
      "Enter result (1=pass, 2=fail):  1\n",
      "Enter result (1=pass, 2=fail):  1\n",
      "Enter result (1=pass, 2=fail):  1\n",
      "Enter result (1=pass, 2=fail):  1\n",
      "Enter result (1=pass, 2=fail):  1\n",
      "Enter result (1=pass, 2=fail):  2\n",
      "Enter result (1=pass, 2=fail):  1\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Passed: 8\n",
      "Failed: 2\n",
      "Bonus to instructor\n"
     ]
    }
   ],
   "source": [
    "#FIG03_03.py\n",
    "\"\"\"Using nested control statements to analyze examination results.\"\"\"\n",
    "\n",
    "#initialize variables\n",
    "passes = 0 #number of passes \n",
    "failures = 0 #number of fail grades\n",
    "\n",
    "#process 10 student's grades\n",
    "for student in range(10):\n",
    "    #get one exam result\n",
    "    result = int(input('Enter result (1=pass, 2=fail): '))\n",
    "    \n",
    "    if result == 1:\n",
    "        passes = passes + 1\n",
    "    else:\n",
    "        failures = failures + 1\n",
    "        \n",
    "#termination phase\n",
    "print('Passed:',passes)\n",
    "print('Failed:',failures)\n",
    "\n",
    "if passes >= 8:\n",
    "    print('Bonus to instructor')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "id": "201bb655-636a-44b1-95d2-e78a7046f7dd",
   "metadata": {},
   "outputs": [],
   "source": [
    "# fig 3.3 "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "id": "c56878ea-58c3-4a1f-9126-c63f7bff6d7c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter an integer:  10\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10 is even\n"
     ]
    },
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "Enter an integer:  7\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "7 is odd\n"
     ]
    }
   ],
   "source": [
    "for count in range(2):\n",
    "    value = int(input('Enter an integer: '))\n",
    "    if value %2 == 0:\n",
    "        print(f'{value} is even')\n",
    "    else:\n",
    "        print(f'{value} is odd')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 37,
   "id": "d8c3bfb7-2ead-450d-a7a2-c2a2d3bbf3c3",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "5 6 7 8 9 "
     ]
    }
   ],
   "source": [
    "for number in range(5, 10):\n",
    "    print(number, end =' ')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 42,
   "id": "4bafd041-51b3-4f39-8203-ce11d5f99b3f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "10 8 6 4 2 "
     ]
    }
   ],
   "source": [
    "for number in range(10, 0, -2):\n",
    "    print(number, end=' ')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 41,
   "id": "498754fc-bcce-46d3-a79a-3c8bf4b8cb1a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0 2 4 6 8 "
     ]
    }
   ],
   "source": [
    "for number in range(0, 10, 2):\n",
    "    print(number, end=' ')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "id": "49b271b4-fadf-4280-8e14-4d98f356ff79",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "99 88 77 66 55 44 33 22 11 0 "
     ]
    }
   ],
   "source": [
    "for number in range(99, -1, -11):\n",
    "    print (number,end=' ')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 46,
   "id": "ca3913fe-b069-4c15-b93e-6658c1b02746",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2550"
      ]
     },
     "execution_count": 46,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "total = 0 \n",
    "\n",
    "for number in range(2, 101, 2):\n",
    "    total += number\n",
    "    \n",
    "total"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 47,
   "id": "3f1523d1-a5d9-4c9e-b08f-e832e79507c9",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "112.31\n"
     ]
    }
   ],
   "source": [
    "amount = 112.31\n",
    "\n",
    "print(amount)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 48,
   "id": "f840c8d9-0bd7-4c7e-943d-043caaa1afae",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "112.31000000000000227374\n"
     ]
    }
   ],
   "source": [
    "print(f'{amount:.20f}')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 49,
   "id": "58bca6c7-b031-48c7-b73c-cb296a03ceb3",
   "metadata": {},
   "outputs": [],
   "source": [
    "from decimal import Decimal"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 52,
   "id": "e9c8ca38-b8f0-4266-8d3f-dedbc2ffebca",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Decimal('12.5')"
      ]
     },
     "execution_count": 52,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "x = Decimal('10.5')\n",
    "\n",
    "y = Decimal('2')\n",
    "\n",
    "x+y"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 53,
   "id": "db50cd6c-babd-48cc-aaeb-7af707e252df",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Decimal('5')"
      ]
     },
     "execution_count": 53,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "x//y"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 55,
   "id": "17d14ef2-4ae8-4fa5-a620-d2236b18b145",
   "metadata": {},
   "outputs": [],
   "source": [
    "x += y"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 56,
   "id": "0508e038-f314-402b-9907-2410939b45c8",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "Decimal('14.5')"
      ]
     },
     "execution_count": 56,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "x"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 60,
   "id": "289e9c01-c598-4341-8817-2d7d368146dd",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      " 1   1050.00\n",
      " 2   1102.50\n",
      " 3   1157.62\n",
      " 4   1215.51\n",
      " 5   1276.28\n",
      " 6   1340.10\n",
      " 7   1407.10\n",
      " 8   1477.46\n",
      " 9   1551.33\n",
      "10   1628.89\n"
     ]
    }
   ],
   "source": [
    "amount = 112.31\n",
    "principal = Decimal('1000.00')\n",
    "rate = Decimal('0.05')\n",
    "\n",
    "for year in range(1, 11):\n",
    "    amount = principal * (1 + rate) ** year\n",
    "    print(f'{year:>2}{amount:>10.2f}')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 70,
   "id": "e3d61c36-a41b-4599-8cf1-08ac8acc192e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "   39.791\n"
     ]
    }
   ],
   "source": [
    "from decimal import Decimal\n",
    "\n",
    "print(f\"{Decimal('37.45')*Decimal('1.0625'):9.3f}\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 72,
   "id": "ee47b71a-af4a-400b-b1cb-20656ef8964e",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "0,1,2,3,4,5,6,7,8,9,"
     ]
    }
   ],
   "source": [
    "for number in range(100):\n",
    "    if number == 10:\n",
    "        break\n",
    "    print(number, end=',')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 75,
   "id": "90479465-e56d-4635-80a8-82c7e4771edd",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Not a SR female\n"
     ]
    }
   ],
   "source": [
    "gender = 'male'\n",
    "\n",
    "age = 70 \n",
    "\n",
    "if gender == 'Female' and age >= 65:\n",
    "    print('Senior female')\n",
    "else:\n",
    "    print('Not a SR female')\n",
    "    "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 77,
   "id": "728dcfa1-82f8-456b-86f3-c5ab9a7b8131",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Student gets an A\n"
     ]
    }
   ],
   "source": [
    "semester_average = 83\n",
    "\n",
    "final_exam = 95 \n",
    "\n",
    "if semester_average >=90 or final_exam >=90:\n",
    "    print('Student gets an A')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 80,
   "id": "1d9328d4-ab7d-4b0b-8883-0b004b9554e4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The next grade is 87\n"
     ]
    }
   ],
   "source": [
    "grade = 87\n",
    "\n",
    "if not grade == -1:\n",
    "    print('The next grade is', grade)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 81,
   "id": "d5330438-62fe-48cb-bacc-6a8640deb659",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The next grade is 87\n"
     ]
    }
   ],
   "source": [
    "if grade!= -1:\n",
    "    print('The next grade is', grade)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 85,
   "id": "fc1e3c9b-1e9c-403f-8d3f-86367e9b742e",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 85,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "i = 1\n",
    "j = 2\n",
    "k = 3\n",
    "m = 2\n",
    "\n",
    "(i>=1) and (j < 4)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 86,
   "id": "8236fedd-54db-4dcf-9468-fd1be5ba2aaf",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 86,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "(m <=99) and (k == m)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 87,
   "id": "0ccde703-d623-4e13-9136-59810dc22850",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 87,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "(j >= 1) or (k == m)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 88,
   "id": "ff52a4be-c78a-44fd-9265-7875b7185a5b",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 88,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "(k+m<j) or (3-j>=k)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 89,
   "id": "d7e00689-6035-4fde-8f80-74bafc1fee3e",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "False"
      ]
     },
     "execution_count": 89,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "not (k>m)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 90,
   "id": "66073fa0-b41d-4ae0-a38e-b69ff84e0473",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "79.4"
      ]
     },
     "execution_count": 90,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "grades = [85, 93, 45, 89, 85]\n",
    "\n",
    "sum(grades)/ len(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 92,
   "id": "1845e865-47c4-4038-bd39-ee7984ce304e",
   "metadata": {},
   "outputs": [],
   "source": [
    "import statistics"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 93,
   "id": "480c9b89-82ec-4617-8c5f-e5e4d34e6119",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "79.4"
      ]
     },
     "execution_count": 93,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.mean(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 94,
   "id": "a8aeca3e-2c07-4609-9cae-fed3fd30e4f8",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "85"
      ]
     },
     "execution_count": 94,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.median(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 95,
   "id": "cc89a13a-ada0-4594-8dbd-b90d7ba7c8fe",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "85"
      ]
     },
     "execution_count": 95,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.mode(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 96,
   "id": "00c32fef-5738-43df-8078-2b0a1f9ae796",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "[45, 85, 85, 89, 93]"
      ]
     },
     "execution_count": 96,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "sorted(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 97,
   "id": "3ffae217-bdd6-4a1a-9f4a-028bfd3eb03d",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "79.16666666666667"
      ]
     },
     "execution_count": 97,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "values = [47,95,88,73,88,84]\n",
    "\n",
    "statistics.mean(values)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 98,
   "id": "28209681-fe50-4ded-a94e-787ca403a5f3",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "86.0"
      ]
     },
     "execution_count": 98,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.median(values)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 99,
   "id": "5d21cebd-cbeb-4a45-80c3-9900669b1254",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "88"
      ]
     },
     "execution_count": 99,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.mode(values)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 100,
   "id": "a5ff3b5c-7247-4e69-96c0-28c37f269fd1",
   "metadata": {},
   "outputs": [],
   "source": [
    "# 6. Calculate Measures of Central Tendency - Native Python # This is Ben Robin's work"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 102,
   "id": "07d4bd90-4747-4254-815a-536f15ac447b",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "79.4"
      ]
     },
     "execution_count": 102,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "grades = [85, 93, 45, 89, 85]\n",
    "\n",
    "sum(grades)/ len(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 116,
   "id": "2084ee8d-d888-4637-bef2-b8c4726e6160",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "5"
      ]
     },
     "execution_count": 116,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "len(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 117,
   "id": "1e42199c-cfd5-4ff7-bef6-0dcaca505e62",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "397"
      ]
     },
     "execution_count": 117,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "sum(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 113,
   "id": "4554a46c-5f9b-420b-934c-845be7a575f5",
   "metadata": {},
   "outputs": [],
   "source": [
    "# confirmed that numbers match"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 109,
   "id": "07ed6df7-716e-4685-9c0a-b8abd2ee9d36",
   "metadata": {},
   "outputs": [],
   "source": [
    "# 7. Calculate Measures of Central Tendency - with Statistics Module  # This is Ben Robin's work"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 110,
   "id": "d2817db8-2a1c-4d24-8cab-a9b305430af1",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "79.4"
      ]
     },
     "execution_count": 110,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "import statistics\n",
    "\n",
    "statistics.mean(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 111,
   "id": "1db4275b-a4e0-4e82-876d-88a5128b6892",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "85"
      ]
     },
     "execution_count": 111,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.median(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 112,
   "id": "90904c31-f3b6-44d0-8c57-2b4343f31f9d",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "88"
      ]
     },
     "execution_count": 112,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.mode(values)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 118,
   "id": "cee2755e-989a-4db1-ba89-b5c34468becb",
   "metadata": {},
   "outputs": [],
   "source": [
    "# confirmed that numbers match"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 119,
   "id": "eb0a92f3-5311-4c68-8bcf-22d43a27ad4a",
   "metadata": {},
   "outputs": [],
   "source": [
    "# 8. Custom Central Tendency # This is Ben Robin's work"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 120,
   "id": "6ec10c88-67d2-43aa-8c8a-52e7a9f562f1",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "9"
      ]
     },
     "execution_count": 120,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "grades = [98,86,89,95,1,79,89,92,85]\n",
    "\n",
    "len(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 121,
   "id": "53ed40c7-c9c9-4f06-be65-8c46c7b28def",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "714"
      ]
     },
     "execution_count": 121,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "sum(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 123,
   "id": "8baed693-edcd-45d7-b0a5-4c5505e3ccf8",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "79.33333333333333"
      ]
     },
     "execution_count": 123,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.mean(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 124,
   "id": "a0f081f3-dd1b-4692-9db1-adc42e9b571a",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "89"
      ]
     },
     "execution_count": 124,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.median(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 125,
   "id": "042c422c-b25d-4313-baf4-4029a26d0d8d",
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "89"
      ]
     },
     "execution_count": 125,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "statistics.mode(grades)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "bb53b2eb-5b59-4f7f-8925-a28961846182",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

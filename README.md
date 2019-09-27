# python2
>>> x = input("첫번째 수:")
첫번째 수:9
>>> y = input("두번째 수;")
두번째 수;28
>>> print("합은",x+y)
합은 928

x = int(input("첫번째 수:"))
첫번째 수:9
>>> y = int(input("두번째 수:"))
두번째 수:28
>>> print("합은",x+y)
합은 37

>>> name = input("당신의 이름은?")
당신의 이름은?조명아
>>> print("저는 "+name+"입니다.")
저는 조명아입니다.
>>>  name = input("당신의 이름은?")
 
SyntaxError: unexpected indent
>>> name = input("당신의 이름은?")
당신의 이름은?조명아
>>> print("저는 "name"입니다.")
SyntaxError: invalid syntax
>>> print("저는 "+name+"입니다.")
저는 조명아입니다.


print('BTS 멤버수는'+ 7)
Traceback (most recent call last):
  File "<pyshell#32>", line 1, in <module>
    print('BTS 멤버수는'+ 7)
TypeError: can only concatenate str (not "int") to str
>>> print('BTS 멤버수는' + str(7))
BTS 멤버수는7

>>> len("student")
7
len-글자수알려주는 함수

\n-줄바꿈

>>> print(r'C:ShineSon\name')
C:ShineSon\name
>>> print('C:ShineSon\name')
C:ShineSon
ame


>>> print("="*30)
==============================
>>> equal = "="*30
>>> print(equal)
==============================
*여러개 반복

>>> print("BTS는 %s명이다."%mem)
BTS는 7명이다.
>>> mem = 7
>>> memi=120
>>> print("BTS는 %s명이고 팬은 %s." %(mem, memi))
BTS는 7명이고 팬은 120.
>>> sentence = "BTS는 %s명이고 팬은 %s억 명이다."
>>> print(sentence%(7,75))
BTS는 7명이고 팬은 75억 명이다.

sent = "BTS젛이"
>>> sent[2]
'S'
>>> sent[3]
'젛'
>>> sent = "BTS 좋아"
>>> sent[3]
' '
>>> sent[11]
Traceback (most recent call last):
  File "<pyshell#69>", line 1, in <module>
    sent[11]
IndexError: string index out of range
>>> sent[-3]
' '
012345
-6-5-4-3-2-1
 
 
 오늘뭐먹지 = ['오삼불고기', '쭈꾸미 볶음', '김치찌개', '백립', '맛탕']
>>> 오늘뭐먹지
['오삼불고기', '쭈꾸미 볶음', '김치찌개', '백립', '맛탕']
>>> 오늘뭐먹지[0]
'오삼불고기'
>>> 오늘뭐먹지[3]
'백립'
>>> 오늘뭐먹지[1]='계란말이'
>>> 오늘뭐먹지[1]='계란말이'
>>> 오늘뭐먹지[1]
'계란말이'
>>> 오늘뭐먹지[4]='떡볶이'
>>> 오늘뭐먹지[4]
'떡볶이'
 
 :-아직문장안끝남
 
if value >=80 :
	print("마스크를 쓰세요")
else :
	print("미세먼지가 좋습니다.")

	
마스크를 쓰세요
>>> 

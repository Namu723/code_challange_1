없는 숫자 더하기

def solution(numbers):
    answer = 0
    num  =[]
    for i in range(10):
        num.append(i)
    numbers.sort()
    for i in range(10):
        if num[i] not in numbers:
            answer +=  num[i]
    return answer
    
   #ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
   
   
def solution(numbers):
    return 45 - sum(numbers)

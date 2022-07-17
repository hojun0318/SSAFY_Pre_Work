# SSAFY_Pre_Work

<img width="497" alt="캡처" src="https://user-images.githubusercontent.com/104968672/179360271-7d088723-87a0-412d-91ee-427bb2962850.PNG">

### 출처 : https://swexpertacademy.com/main/code/problem/problemList.do


## 사전 과제 Track 3-1번
# 1936. 1대1 가위바위보
* a, b = map(int, input().split())

* if (a == 1 and b == 2) or (a == 2 and b == 3) or (a == 3 and b == 1):
* print("B")
* else:
* print("A")


## 사전 과제 Track 3-2번
# 2063. 중간값 찾기
* n = int(input())
* data_list = list(map(int, input().split()))

* data_list.sort(reverse = True)
* print(data_list[n // 2])


## 사전 과제 Track 3-3번
# 2058. 자릿수 더하기
* dt = input()
* tot = 0

* for i in range(len(dt)):
* tot += int(dt[i])
    
* print(tot)


## 사전 과제 Track 3-4번
# 1989. 초심자의 회문 검사
* ds = int(input())

* for i in range(1, ds + 1):
*    dt = input()
*  temp = ''
*    for j in range(len(dt)-1, -1, -1):
*       temp += dt[j]
        
*    if dt == temp:
*        print('#%d %d' % (i, 1))
*    else:
*        print('#%d %d' % (i, 0))


## 사전 과제 Track 3-5번
# 1946. 간단한 압축 풀기
* ds = int(input())

* for i in range(1, ds + 1):
*    dt = int(input())
*    result = ''
*    for j in range(dt):
*        idx, count = input().split()
*        result += idx * int(count)
*    print('#{}'.format(i))
*    for k in range(1, len(result) + 1, 10):
*        print(result[k-1:k+10-1])
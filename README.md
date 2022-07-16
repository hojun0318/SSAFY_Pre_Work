# SSAFY_Pre_Work

<img width="497" alt="캡처" src="https://user-images.githubusercontent.com/104968672/179360271-7d088723-87a0-412d-91ee-427bb2962850.PNG">

### 출처 : https://swexpertacademy.com/main/code/problem/problemList.do
## 사전 과제 Track 3-1번

# 1936. 1대1 가위바위보
* a, b = map(int, input().split())

* if (a == 1 and b == 2) or (a == 2 and b == 3) or (a == 3 and b == 1):
* print("B")
* else :
* print("A")


## 사전 과제 Track 3-2번
# 2063. 중간값 찾기
* n = int(input())
* data_list = list(map(int, input().split()))

* data_list.sort(reverse = True)
* print(data_list[n // 2])
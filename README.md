# SSAFY_Pre_Work
## 사전 과제 Track 3-1번
### 출처 : https://swexpertacademy.com/main/code/problem/problemList.do

# 1대1 가위바위보
a, b = map(int, input().split())

if (a == 1 and b == 2) or (a == 2 and b == 3) or (a == 3 and b == 1) :
    print("B")
else :
    print("A")

# -1-_1
A, B = map(int, input().split()) 2 C = int(input()) 3 ​ 4 total = A * 60 + B 5 total += C 6 total %= 1440 7 ​ 8 hour = total // 60 9 minute = total % 60 10 ​ 11 print(hour, minute)

# 22610005-KARADI-SRUSHTI-PRAVIN
# Code on Quick Sort

<h3>1. Code Output</h3>

![Screenshot from 2024-07-29 19-43-28](https://github.com/user-attachments/assets/3a0d1011-e22d-49b2-a1b2-828dfd561663)

<h3>2. Profiling using Gprof output</h3>

Commands Used:
1) gcc -o quick -pg quick.c
2) ./quick
3) gprof quick gmon.out > analysis.txt
4) cat analysis.txt

![Screenshot from 2024-07-29 19-33-15](https://github.com/user-attachments/assets/2be81152-73ce-4454-934f-3724db58f082)

![Screenshot from 2024-07-29 19-34-08](https://github.com/user-attachments/assets/c5527f57-01b7-4873-93aa-f0b81fda6332)

![Screenshot from 2024-07-29 19-34-25](https://github.com/user-attachments/assets/caa02efd-28cc-442a-adb7-f0a9606aff6b)

![Screenshot from 2024-07-29 19-34-37](https://github.com/user-attachments/assets/761b4b2f-64d8-4d62-8bf4-abcd7b123173)

<h3>3. Visual of Profiling</h3>
Commands Used:
1) gprof2dot -f prof analysis.txt > call_graph.dot
2) dot -Tpng -o call_graph.png call_graph.dot

![call_graph](https://github.com/user-attachments/assets/ac7bd716-2fa5-4c35-a4eb-1f54a7b8d4df)





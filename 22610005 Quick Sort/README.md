# 22610005-KARADI-SRUSHTI-PRAVIN
# Code on Quick Sort

<h3>1. Code Output</h3>

![Screenshot 2024-08-11 205936](https://github.com/user-attachments/assets/ac1b7067-a454-4c6a-9358-a1cacfeadf80)

<h3>2. Profiling using Gprof output</h3>

Commands Used:
1) gcc -o quick -pg quick.c
2) ./quick
3) gprof quick gmon.out > analysis.txt
4) cat analysis.txt


![Screenshot 2024-08-11 205955](https://github.com/user-attachments/assets/1417c75c-8177-435a-aadd-a167a8ce95d3)

![Screenshot 2024-08-11 210014](https://github.com/user-attachments/assets/f1e66223-00b2-4852-9191-0cbe9eb55e4f)

![Screenshot 2024-08-11 210033](https://github.com/user-attachments/assets/02010b41-f563-4799-9d59-cc9e23fd38a4)

![Screenshot 2024-08-11 210051](https://github.com/user-attachments/assets/385c4a53-f53b-4be5-a0ad-ef4508241069)

<h3>3. Visual of Profiling</h3>
Commands Used:
1) gprof2dot -f prof analysis.txt > call_graph.dot
2) dot -Tpng -o call_graph.png call_graph.dot

![Screenshot 2024-08-11 210122](https://github.com/user-attachments/assets/166a83c0-152d-4cf9-be24-9b0218c738d4)

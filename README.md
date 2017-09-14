import sys
if len(sys.argv) >=  5:
    for i in range(1,5):
        sys.stdout.write(sys.argv[i] + '\n')
    for j in range(5,len(sys.argv)):
        sys.stderr.write(sys.argv[j] + '\n')
else:
    for k in range(1,len(sys.argv)):
        sys.stdout.write(sys.argv[k] + '\n')# zhiwei_hw1_1
hello world

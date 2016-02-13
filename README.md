# node-python-lua-on-7688

results of
 1. /usr/bin/perf record -o node.dat node --perf-basic-prof -e 'console.log("hello, world")'
 2. /usr/bin/perf record -o python.dat python -c 'print "hello, world"
 3. /usr/bin/perf record -o lua.dat lua -e 'print("hello, world")'

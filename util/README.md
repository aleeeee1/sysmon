# compiling
`sudo clang -O3 -shared -o /usr/lib/sysmon_cpu_cache.so -fPIC sysmon_cpu_cache.c` (you can execute sysmon anywhere) or `clang -O3 -shared -o sysmon_cpu_cache.so -fPIC sysmon_cpu_cache.c` (you can execute sysmon only in sysmon/ directory)

replace clang with gcc if you want to use gcc

# why
this method is better than the other ones. more accurate

# credit
chatgpt and [skyblueborb](https://github.com/Skyblueborb)
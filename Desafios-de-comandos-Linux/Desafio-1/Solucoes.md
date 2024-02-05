# Minhas soluções
![Print do desafio](prints/1.png)
```shell
 echo "hello world"
```  
![Print do desafio](prints/2.png)
```shell
pwd
```  
![Print do desafio](prints/3.png)
```shell
ls 
``` 
![Print do desafio](prints/4.png)
```shell
cat access.log 
``` 
![Print do desafio](prints/5.png)
```shell
tail -n 5 access.log  
```
![Print do desafio](prints/6.png)
```shell
touch take-the-command-challenge 
```
![Print do desafio](prints/7.png)
```shell
mkdir -p  tmp/files  
```
![Print do desafio](prints/8.png)
```shell
cp take-the-command-challenge tmp/files 
```
![Print do desafio](prints/9.png)
```shell
mv take-the-command-challenge tmp/files  
```
![Print do desafio](prints/10.png)
```shell
ln -s tmp/files/take-the-command-challenge take-the-command-challenge
```
![Print do desafio](prints/11.png)
```shell
rm -rf * .*
```
![Print do desafio](prints/12.png)
```shell
rm -rf **/*.doc 
```
![Print do desafio](prints/13.png)
```shell
grep "GET"  access.log 
```
![Print do desafio](prints/14.png)
```shell
grep -l 500 * 
```
![Print do desafio](prints/15.png)
```shell
ls access.log*
```
![Print do desafio](prints/16.png)
```shell
find -name access.log | grep -rh 500
```
![Print do desafio](prints/17.png)
```shell
grep -ro ^[0-9.]*
```
![Print do desafio](prints/18.png)
```shell
ls -l | wc -l
```
![Print do desafio](prints/19.png)
```shell
sort access.log
```
![Print do desafio](prints/20.png)
```shell
grep "GET" access.log | wc -l
```
![Print do desafio](prints/21.png)
```shell
cat split-me.txt | tr ";" "\n"
```
![Print do desafio](prints/22.png)
```shell
seq 1 100 | tr "\n" " " 
```
![Print do desafio](prints/23.png)
```shell
 sed -i "challenges are difficult" **/*.txt
```
![Print do desafio](prints/24.png)
```shell
 awk '{s+=$1} END {print s}' sum-me.txt 
```
![Print do desafio](prints/25.png)
```shell
 ls -R | grep ^[a-z] 
```
![Print do desafio](prints/26.png)
```shell
 mv * .* 
```
![Print do desafio](prints/27.png)
```shell
 ls  | tr " " "." 
```
![Print do desafio](prints/28.png)
```shell
 dirname **/*.tf | sort -u 
```
![Print do desafio](prints/29.png)
```shell
 ls -R | grep "^[0-9]" | grep -v dir  
```
![Print do desafio](prints/30.png)
```shell
 awk 'NR==25' faces.txt  
```
![Print do desafio](prints/31.png)
```shell
 tac reverse-me.txt 
```
![Print do desafio](prints/32.png)
```shell
cat -n faces.txt | sort -u -k 2 | sort -n | cut -f2
```
![Print do desafio](prints/33.png)
```shell
cat random-numbers.txt | factor | sort | uniq | awk 'NF==2' | wc -l 
```
![Print do desafio](prints/34.png)
```shell
 cat access.log.* | awk '{print $1}' | sort | uniq -d
```
![Print do desafio](prints/35.png)
```shell
  cat **/*access.log* | awk '/404/{print a} {a=$0}'
```
![Print do desafio](prints/36.png)
```shell
  diff *bin --to-file=base.bin | cut -d ' ' -f3 
```
![Print do desafio](prints/37.png)
```shell
  cat './.../  /. .the flag.txt' 
```
![Print do desafio](prints/38.png)
```shell
  grep -P "\t" * | wc -l 
```
![Print do desafio](prints/39.png)
```shell
  find . ! -name "*.txt" ! -name "*.exe" -delete 
```
![Print do desafio](prints/40.png)
```shell
  find . -name "-*" -delete 
```
![Print do desafio](prints/41.png)
```shell
  cat ps-* | sort -k2 -n | uniq  
```
![Print do desafio](prints/42.png)
```shell
  cat netstat.out | grep -w "LISTEN" | awk '{print $4}' | cut -d ':' -f2 | sort -nr 
```
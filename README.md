## Presto build on Hive, MapReduce    
      
## Step1--MR:    
      
after build the WordCount.jar file, then running with:    
```
$ hadoop jar WordCount.jar ../../../input1.txt ../../../output    
```      
checking result with :    
```
$ cd output/    
$ cat part-r-00000    
```        


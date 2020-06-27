# Programming language options and functional programming
> 
> Latest Submission Grade
> 
> 100%
> 
>  1.Question 1
> 
> Which programming languages can be used for using GraphX, the ApacheSpark graph processing engine? (Select all that apply)
> 
> 1 / 1 point 
> 
>  R 
> 

      Scala 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  Python 
> 
>  2.Question 2
> 
> What is the result of the following code?
> 
> <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 
> def f(x):    
> 
>   return (x+2)*2    
> 
> l = [1,2,3,4]
> 
> map(f,l)
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> Hint: "map" is the python equivalent to "apply" used in the lecture
> 
> This is an example of a correct input format (although others are accepted as well):
> 
> [3, 6, 1, 25]
> 
> 1 / 1 point 
> 

     [6, 8, 10, 12]
> 
> Check
> 
> Correct
> 
> Correct
> 
>  3.Question 3
> 
> What is the result of the following python code running on top of ApacheSpark (pyspark) ?
> 
> <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 
> sc.parallelize([1,2,3,4,5]).reduce(lambda a,b:a+b)
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> Please have a look at the following API documentation if necessary:
> 
> https://spark.apache.org/docs/latest/rdd-programming-guide.html#basics
> 
> 1 / 1 point 
> 

     15
> 
> Check
> 
> Correct
> 
> Correct
> 
>  4.Question 4
> 
> What has to be changed in an ApacheSpark program using only functions on the RDD API which has been tested on 1 KB of data if it should run on 1 PB of data?
> 
> 1 / 1 point 
> 

      Nothing 
> 
>  You have to implement it in a parallel way 
> 
> Check
> 
> Correct
> 
> Correct, ApacheSpark code is already parallel code running on top of the RDD API, it doesn't matter how bit the RDD is
> 
>  5.Question 5
> 
> In which programming languages do you find the most libraries for data science specific tasks?
> 
> 1 / 1 point 
> 
>  Java 
> 
>  Scala 
> 

      Python 
> 
> Check
> 
> Correct
> 
> Correct
> 

      R 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  6.Question 6
> 
> Data frames are the central data structure in R and also in python's Pandas. But they are not using ApacheSpark in the background, therefore what is the major limitation of data frames used in R or python's Pandas?
> 
> 1 / 1 point 
> 
>  They are not as cool as ApacheSpark 
> 

      They are not running in parallel on multiple machines 
> 
>  They are not OpenSource 
> 
>  They are very unstable 
> 
> Check
> 
> Correct
>
> -- https://www.coursera.org/learn/ds/exam/stMdg/programming-language-options-and-functional-programming/attempt?redirectToCover=true#Tunnel Vision Close

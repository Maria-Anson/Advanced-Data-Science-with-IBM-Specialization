# Data storage solutions, and ApacheSpark
> 
> Latest Submission Grade
> 
> 100%
> 
>  1.Question 1
> 
> <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> rdd = sc.parallelize(range(100))
> 
> rdd2 = range(100)
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> Please consider the following code.
> 
> Where is data in "**rdd**" stored physically?
> 
> 1 / 1 point 
> 

      In main-memory of ApacheSpark worker nodes 
> 
>  On the local Driver machine 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  2.Question 2
> 
> <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 
> rdd = sc.parallelize(range(100))
> 
> rdd2 = range(100)
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> Please consider the following code.
> 
> Where is data in "**rdd2**" stored physically?
> 
> 1 / 1 point 
> 
>  In main-memory of ApacheSpark worker nodes 
> 

      On the local Driver machine 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  3.Question 3
> 
> What is the parallel version of the following code?
> 
> <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 
> len(range(9999999999))
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> 1 / 1 point 
> 

      sc.parallelize(range(9999999999)).count() 
> 
>  parallelize(range(9999999999)).count() 
> 
>  len(sc.parallelize(range(9999999999))) 
> 
>  size(sc.parallelize(range(9999999999))) 
> 
>  count(sc.parallelize(range(9999999999))) 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  4.Question 4
> 
> Which storage solutions support seamless modification of schemas? (Select all that apply)
> 
> 1 / 1 point 
> 

      ObjectStorage 
> 
> Check
> 
> Correct
> 
> Correct
> 
      NoSQL 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  SQL/Relational Databases 
> 
>  5.Question 5
> 
> Which storage solutions support dynamic scaling on storage? (Select all that apply)
> 
> 1 / 1 point 
> 

      ObjectStorage 
> 
> Check
> 
> Correct
> 
> Correct
> 

      NoSQL 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  SQL/Relational Databases 
> 
>  6.Question 6
> 
> Which storage solutions support normalization and integrity checks on data out of the box? (Select all that apply)
> 
> 1 / 1 point 
> 
>  ObjectStorage 
> 
>  NoSQL 
> 

      SQL/Relational Databases 
> 
> Check
> 
> Correct
> 
> Correct
>
> -- https://www.coursera.org/learn/ds/exam/uzBPk/data-storage-solutions-and-apachespark/attempt?redirectToCover=true#Tunnel Vision Close

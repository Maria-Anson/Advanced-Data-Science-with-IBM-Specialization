# ApacheSparkSQL and Cloudant
> 
> Latest Submission Grade
> 
> 100%
> 
>  1.Question 1
> 
> What statements are true about cloudant? (Select all that apply)
> 
> 1 / 1 point 
> 

      Cloudant is based on ApacheCouchDB 
> 
> Check
> 
> Correct
> 
> correct
> 
>  Cloudant is a SQL database 
> 

      Cloudant is a NoSQL database 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  Cloudant is a very fast and scalable key-value store 
> 

      Cloudant is meant for storing JSON documents effectively 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  BigCouch is a tool to inflate storage on CouchDB 
> 
> 

      BigCouch is a component between the client and a set of CouchDB services used for horizontal scaling 
> Check
> 
> Correct
> 
> Correct
> 
>  2.Question 2
> 
> Please have a look at the following flow:
> 
> ![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dm68ZrjHEeaoWA59UGLCkA_cd8ce29bab88651ed25dc1eaaf9df1d7_Screen-Shot-2016-12-02-at-20.41.55.png?expiry=1593388800000&hmac=8jM_qtKUsbXo7NNJnhUTFGDGU6E8GsKicPPFgfHkdok)
> 
> Which nodes are actually simulating sensors of a hypothetical IoT device?
> 
> (Please select Fluid Simulator, Voltage Sensor Simulator, Mechanical Sensor Simulator, this is some legacy from a previous version of this course and we can't change the quiz at that point for fairness reasons)
> 
> 1 / 1 point 
> 

      Voltage Sensor Simulator 
> 
> Check
> 
> Correct
> 
> Correct
> 

      Fluid Simulator 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  Drum Data 
> 
>  Voltage Data 
> 
>  msg.payload 
> 
>  Fluid Data 
> 

      Mechanical Sensor Simulator 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  Washer01 
> 
>  3.Question 3
> 
> In the "End-to-End Scenario", where does all the data get stored in?
> 
> (Please select Cloudant (ApacheCouchDB), this is some legacy from a previous version of this course and we can't change the quiz at that point for fairness reasons)
> 
> 1 / 1 point 
> 

      Cloudant (ApacheCouchDB) 
> 
>  ApacheSpark 
> 
>  Object Storage 
> 
>  OpenStack Swift 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  4.Question 4
> 
> How does the Catalyst optimizer work internally?
> 
> Abbreviations:
> 
> AST - Abstract Syntax Tree
> 
> LEP - Logical Execution Plan
> 
> PEP - Physical Execution Plan
> 
> 1 / 1 point 
> 
>  A AST is created from an SQL LEP. This AST is transformed (optimised). Then multiple PEPs are created from the optimised LEP. Finnaly, based on cost based statistics an optimal PEP is chosen to be executed. 
> 

      A LEP is created from an SQL AST. This LEP is transformed (optimised). Then multiple PEPs are created from the optimised LEP. Finnaly, based on cost based statistics an optimal PEP is chosen to be executed. 
> 
>  A AST is created from an SQL PEP. This AST is transformed (optimised). Then multiple LEPs are created from the optimised PEP. Finnaly, based on cost based statistics an optimal LEP is chosen to be executed. 
> 
>  A PEP is created from an SQL AST. This AST is transformed (optimised). Then multiple PEP are created from the optimised LEP. Finnaly, based on cost based statistics an optimal PEP is chosen to be executed. 
> 
> Check
> 
> Correct
> 
> Correct
> 
>  5.Question 5
> 
> What is the advantage of using ApacheSparkSQL over RDDs? (select all that apply)
> 
> 1 / 1 point 
> 
>  ApacheSparkSQL bypasses the RDD interface which has been proven to be very complicated 
> 
>  SQL is simpler than RDD but has some performance drawbacks 
> 

      Catalyst and Tungsten are able to optimise the execution, so are more likely to execute more quickly than if you would had implemented something equivalent using the RDD API. 
> 
> Check
> 
> Correct
> 
> Correct
> 

      The API is simpler and doesn't require specific functional programming skills 
> 
> Check
> 
> Correct
> 
> Correct
>
> -- https://www.coursera.org/learn/ds/exam/nUMHb/apachesparksql-and-cloudant/attempt?redirectToCover=true#Tunnel Vision Close

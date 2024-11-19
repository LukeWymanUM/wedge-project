## Feedback 

Nice work on this project, you can consider it complete. I'm going to read your files in order and give you feedback
as I move through them, from Task 1 to Task 3. 

Great job on the README and the triage of the `local` null differences. Generally, speaking, you want to be _very_ careful replacing NULL with 0. Sometimes it's fine (and probably doesn't hurt here), other times it's misleading. For instance, the average of `local` between our two data sets will be very different. 



### Task 1

* Generally it's best to do one table per file rather than everything in one big file. That allows partitioning which can save money. It also means that if something goes wrong in an upload it's easy to drop-and-restart a given table. 
* Very extensive cleaning here. It's a lot of code, but you're getting very fine-grained control over what happens. 
* It's a poor choice to glue everything together and upload in one massive step. The data is too big to do that easily. Much better to do one file at a time. 
* Although maybe you didn't actually do the above? A bit unclear from the code.  

### Task 2

* Nice job on this task. 
* I appreciate that you took the time to do this with the reproducible approach. 


### Task 3

* Nice job on this, very efficient. 
* You're one of the relatively few to get the queries all correct on this one. Kudos!


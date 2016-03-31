#### psdistsysaws
#####SQS
######role of queues in dist cloud syatems
(great for decoupling)
horizontal scaling  
compute-intensive actions

(acts as a buffer)
protects downstream systems from bursts
######about sqs
single queue exists across servers  
concurrent access by multiple applications
persists messages up to 256kb in size  
at least 4 days

#####EC2
######elastic ip
will be charged when keeping idle(not using)

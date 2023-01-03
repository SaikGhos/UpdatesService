# UpdatesService

Used :  Spring Web flux(Reactive Spring REST API), Kafka(producer, consumer)

Processed the employee information consumed from "appUpdates” Kafka topic (created by producer in Assignment 1. 
Validate all required fields (None of the fields should be null). 

Once validated post the message to an employeeUpdates topic. 
If it is an invalid message, post to employeeDLQ topic.

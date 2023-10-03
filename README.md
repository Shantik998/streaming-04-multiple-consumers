# streaming-04-multiple-consumers

> Use RabbitMQ to distribute tasks to multiple workers

One process will create task messages. Multiple worker processes will share the work. 


## Before You Begin

1. Fork this starter repo into your GitHub.
1. Clone your repo down to your machine.
1. View / Command Palette - then Python: Select Interpreter
1. Select your conda environment. 

## Read

1. Read the [RabbitMQ Tutorial - Work Queues](https://www.rabbitmq.com/tutorials/tutorial-two-python.html)
1. Read the code and comments in this repo.

## RabbitMQ Admin 

RabbitMQ comes with an admin panel. When you run the task emitter, reply y to open it. 

(Python makes it easy to open a web page - see the code to learn how.)

## Execute the Producer

1. Run emitter_of_tasks.py (say y to monitor RabbitMQ queues)

Explore the RabbitMQ website.

## Execute a Consumer / Worker

1. Run listening_worker.py

Will it terminate on its own? How do you know? 

## Ready for Work

1. Use your emitter_of_tasks to produce more task messages.

## Start Another Listening Worker 

1. Use your listening_worker.py script to launch a second worker. 

Follow the tutorial. 
Add multiple tasks (e.g. First message, Second message, etc.)
How are tasks distributed? 
Monitor the windows with at least two workers. 
Which worker gets which tasks?


## Reference

- [RabbitMQ Tutorial - Work Queues](https://www.rabbitmq.com/tutorials/tutorial-two-python.html)


## Screenshot

See a running example with at least 3 concurrent process windows here:
<img width="885" alt="Screenshot 2023-09-16 at 8 18 28 PM" src="https://github.com/Shantik998/streaming-04-multiple-consumers/assets/84759571/e2ee99c4-b904-4803-a8ad-5b75409a0814">
<img width="815" alt="Screenshot 2023-10-03 at 3 26 35 PM" src="https://github.com/Shantik998/streaming-04-multiple-consumers/assets/84759571/f028061d-dc4c-4131-837e-7ff1fecea7cb">
<img width="720" alt="Screenshot 2023-10-03 at 3 28 03 PM" src="https://github.com/Shantik998/streaming-04-multiple-consumers/assets/84759571/94901a7c-c1a7-47c7-921e-001deb53e5ef">



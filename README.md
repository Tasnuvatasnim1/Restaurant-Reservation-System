# Restaurant-Reservation-System
The Restaurant Table Reservation System is a multi-threaded application designed to manage the process of customers reserving and vacating tables in a restaurant. The system utilizes semaphores and mutexes to control access to shared resources and ensure thread safety, providing a robust simulation of a real-world restaurant reservation system. 

Customers will maintain first in first service method. When all the customers get tables, they will leave after a certain time and the tables will be available again and the program wil be terminated.

Methods are:
• pthread_mutex_lock()
• pthread_mutex_unlock()
• sem_post()
• pthread_exit()
• sem_wait()
• sem_init()
• pthread_mutex_init()
• pthread_create()
• pthread_join()
• sem_destroy()
• pthread_mutex_destroy()

# Operating System: Linux
To run this “project.c” file, we used these command line arguments in terminal:

gcc project.c -lpthread

./a.out


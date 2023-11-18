This is my elevator simulation. Essentially, it runs by first creating some new passengers that are waiting on varying floors to reach other floors. 
To specify how many floors there are, structure type, passenger probability, etc I read in the property file and convert the key value pairs to variables.
I use these variables to create my elevator simulation, so it begins by making new passengers. Then, if there are passengers to be released it releases them.
Next, my simulation calculates which floor is the closest with passengers waiting. It travels to that floor first. It boards the passenger then moves towards their destination.
Then, while it is moving up or down one floor at a time, it picks up any extra passengers and adds them to the queue. It finally reaches the destination of the first passenger and reales them.
At this point, the elevator might have some extra passengers on the queue to release, but it finds the next closest floor and travels there while dropping off passengers along the way. 
At the end, it prints the longest and shortest time spent traveling for complete passengers. This simulation goes on until the duration is done.
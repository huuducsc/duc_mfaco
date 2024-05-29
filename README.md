* How to run:
  - Compile: `make`
  - Run for an intance: `./faco -p instances/INTANCE_FILE --alg ALGO_NAME"
  - Result file will be exported in folder results/ with the corresponding name

* Overview:
  - faco.cpp: main file including all algorithms
  - local_search.cpp/local_search.h: handle local search phase
  - problem_instance.cpp/problem_instance.h: load nodes and distances + export route
  - pheromone.h: handle pheromone of ant system
  - progargs.cpp/progargs.h: parameters and configs of program

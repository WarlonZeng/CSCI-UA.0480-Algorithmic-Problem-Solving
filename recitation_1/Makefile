FLAGS      = -std=c++11
CPP_DEFS   = -D=HAVE_CONFIG_H
CPP_OPTS   = -Wall -O2

default: all

all: problem_a.cpp problem_b.cpp problem_c.cpp problem_d.cpp problem_e.cpp problem_f.cpp problem_g.cpp problem_h.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_a problem_a.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_b problem_b.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_c problem_c.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_d problem_d.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_e problem_e.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_f problem_f.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_g problem_g.cpp
	g++ $(FLAGS) ${CPP_OPTS} ${CPP_DEFS} -o problem_h problem_h.cpp

clean:
	rm -f all
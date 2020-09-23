to run CNN:
 python hw3_minibatch.py -g 0 -n 20000 -m 128 --CNN data

to run CNN with shuffled label:
 python hw3_minibatch.py -g 0 -n 20000 -m 128 --CNN --shuffleCNN  data

to generate flaness plot with/ without shuffled label:

python hw3_minibatch.py -g 0 -n 20000 -m 128 --CNN --flat  data

python hw3_minibatch.py -g 0 -n 20000 -m 128 --CNN --shuffleCNN --flat data



# Bayesian_Network

Computes the probability of any combination of events given any other combination of events in a given Bayesian network with events - Burglary, Earthquake, Alarm, JohnCalls, and MaryCalls.

Examples:

To print out the probability P(JohnCalls=true and Alarm=false | Burglary=true and Earthquake=false). bnet Jt Af given Bt Ef
To print out the probability P(Burglary=true and Alarm=false and MaryCalls=false and JohnCalls=true and Earthquake=true). bnet Bt Af Mf Jt Et
To print out the probability P(Burglary=true and Alarm=false | MaryCalls=false). bnet Bt Af given Mf
To print out the probability P(Alarm=false and Earthquake=true). bnet Af Et

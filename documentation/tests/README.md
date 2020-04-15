
## Tests

These are WIP and are NOT considered sufficient for validation.  Merely for pulling useful test data.

Please submit your data in Pull Requests to `/tests/<test_name>/results/<date>-<name>-<model>/` folder with whatever relevant data you'd like to submit, the model you're testing, and the context of your test described thoroughly in a Readme.txt file (we will be standardizing this more asap...)

### Enumeration Test

Estimated Test time: 50-70 minutes:

* Intended Delivered Tidal Volume:  300-500, assess every 100 ml  (simulating patients 50-83 kg, 6 ml/kg )
* Lung Compliance:  30-150, assess every 30 ml/cmH2O
* Airway Resistance: 0-15, assess every 5 cmH2O/l/sec
* Input Pressure (from Source): 50-350, every 75 cmH2O

Record the achieved PIP, PEEP, Tidal Volume, Inhale Time, Exhale Time averages over about 3 breaths or about 15 seconds. 
(feel free to increase time/breaths for greater accuracy)

Total different max combinations:  3 * 5 * 3 * 5 = 225

Total time: ~15 seconds * 225 =  56 minutes (plus setup time)

(of course, if you don't mind getting finer grained that would be amazing)


### Driving Pressure Test

Estimated Time (complete test): ~ 4 hours

Try various calibrations of PIP and PEEP set screws to get `Driving Pressure = PIP - PEEP` of 10, 15, 20, 25 cmH2O.
Trying this with each of the above enumerations...  4 * 56 minutes = about 4 hours.

This probably does not need a complete enumeration though.  We're mostly just interested in the general effect on each parameter and finding extreme values.


### PEEP Test

Try the Driving Pressure Test but with PEEP of 5, 10, 15, 20 cmH2O

(16 hours? :)  The effects on each parameter should be obvious though and should not need iterating with all combinations)


### Quality-over-time Test

(TODO: establish the over-time max (min, average) variance of parameter combinations - particularly those close to extreme values.)

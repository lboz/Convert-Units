# Convert-Units

Given a set of pairs of conversions (kg to lb, kg to g, m to feet, etc), 
continually ask the user for input in one of the following formats:
  - "5 kg in lb" this will print the conversion to the specified unit
  - "5 kg to ALL" this will print all conversions that are possible
  - "5 kg to lb g" this will print all conversions to specified units 

Direct conversions only - if we know kg to g and g to lb,
  we won't be able to find kg to lb (unless there is a direct entry for how 
  to convert these)
User enters "q" without quotes to quit. 


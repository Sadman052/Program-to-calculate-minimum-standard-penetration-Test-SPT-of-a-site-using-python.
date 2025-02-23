# Program-to-calculate-minimum-standard-penetration-Test-SPT-of-a-site-using-python.

#Program to calculate minimum among four given N- values
#23, 18, 21 and 35 obtained from the standard penetration
#Test (SPT) of a site using python.

def calculation(n_values):
    min_n = min(n_values)
    return min_n

output = calculation(n_values = [23, 18, 21, 35])
print("The minimum SPT N-value = ", output)

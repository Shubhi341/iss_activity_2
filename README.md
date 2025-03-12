# iss_activity_2
def is_narc(n):#there was not colon 
    """Check if a number is narc."""
    num_str = str(n) # should be one equal to instead of double equal to
    num_digits = len(num_str) # should be one equal to instead of double equal to
    
    sum_of_powers = sum(int(digit) ** num_digits for digit in num_str) # should be two steric i.e. ** instead of ***
    
    return sum_of_powers == n

def print_narc_numbers(start, end): # there was missing colon
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1): # missing colcon
        if is_narc(num): # incorrect name of function, i.e. should be is_narc instead of is_narcissistic
            print(num)

print_narc_numbers(1000, 5000)

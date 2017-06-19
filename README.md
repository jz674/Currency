The primary goal in this assignment is to use the currency exchange service to write the following function:

def exchange(currency_from, currency_to, amount_from):
    """Returns: amount of currency received in the given exchange.

    In this exchange, the user is changing amount_from money in 
    currency currency_from to the currency currency_to. The value 
    returned represents the amount in currency currency_to.

    The value returned has type float.

    Parameter currency_from: the currency on hand
    Precondition: currency_from is a string for a valid currency code
    
    Parameter currency_to: the currency to convert to
    Precondition: currency_to is a string for a valid currency code
    
    Parameter amount_from: amount of currency to convert
    Precondition: amount_from is a float"""
This function will involve several steps. You will get the JSON string from the web service, break up the string to pull out the numeric value (as a substring), and then convert that substring to a float. As this is the very first assignment, we are going to take you through this process step-by-step.

This assignment might feel like you are working in reverse. You will write the functions to break up the string first, and the functions to interact with the web service last. This is because we want you to develop the following programming habit: always complete and test the helper functions before finishing the functions that use them.


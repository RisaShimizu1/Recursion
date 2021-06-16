# Recursion
def factorial(n):
    pass    # replace this line with your lines of recursive code

    if(n==0 or n==1):

        return 1

    else:

        return n*factorial(n-1)


def sum_recursively(n):
    pass    # replace this line with your lines of recursive code

    if(n==1 or n==0):
        return n 
    else:  
        return n+sum_recursively(n-1)

def sumlist_recursively(l):
    pass    # replace this line with your lines of recursive code

    if(len(l)==0):

        return 0

    else:

        return l[0]+sumlist_recursively(l[1:])

def multiply_recursively(n, m):
    pass    # replace this line with your lines of recursive code

    if m==0:
    	return 0
    if m==1:
    	return n
    else:

    	return n + multiply_recursively(n,m - 1)

def reverse_recursively(l):
    pass    # replace this line with your lines of recursive code

    if len(l) == 0: return []
    return [l[-1]] + reverse_recursively(l[:-1])

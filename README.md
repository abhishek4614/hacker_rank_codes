# hacker_rank_codes
# hackerrank code-8
# List Comprehensions
if __name__ == '__main__':
    x = int(input())
    y = int(input())
    z = int(input())
    n = int(input()) 
    x1=[p for p in range(x+1)]
    y1=[q for q in range(y+1)]
    z1=[r for r in range(z+1)]
    perm= [ [i,j,k] for i in x1 for j in y1 for k in z1]
    req = [l for l in perm if sum(l)!=n]
    print(req)
   
swap two number by third by user input.
P = int( input("Please enter value for P: "))
Q = int( input("Please enter value for Q: "))

# To swap the value of two variables
# we will user third variable which is a temporary variable
temp_1 = P
P = Q
Q = temp_1

print ("The Value of P after swapping: ", P)
print ("The Value of Q after swapping: ", Q)

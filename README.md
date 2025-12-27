# code_moveZeroToEnd
def zero_to_end(num):# code for move all zeros to the end.
    count_0=0
    li_=[]
    for i in num:
        if i==0:
            count_0+=1
        else:
            li_.append(i)
    return li_+[0]*count_0
num=[1,0,23,0,0,12,34,0,0]
print(zero_to_end(num))





    
            
    

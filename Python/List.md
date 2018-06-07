Python当中的List和JS中的Array？

Python knows a number of *compound* data types, used to group together other values. 

Lists might contain items of different types, but usually the items all have the same type.

    squares = [1, 4, 9, 16, 25]
    
Like strings (all other built-in sequence type), lists can be indexed and sliced:

    square[0] # 1
    
    square[-3:] # [9, 16, 25]
    
相应的代码在JS中是这样的：

    let squares = [1, 4, 9, 16, 25];
    
    squares[0] // 1
    
    squares.slice(-3) // [9, 16, 25]
        
All slice operation return a new list containing the requested elements.

List also support operations like concatenation:


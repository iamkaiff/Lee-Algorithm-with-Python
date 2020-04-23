# Lee-Algorithm-with-Python
What is Lee Algorithm? 
Basically Lee Algorithm is a possible solution for maze routing problems which is based on BFS (Breadth First Search) which always gives an optimal solution of it, if exists.
Time and Space Complexity of it is O(mxn).

    Algorithm:-   
    Step 1 : - Initialize start point, mark it with 0 in the **cost** matrix.
    Step 2 : -
    REPEAT - Mark all unlabeled neighbors of points marked with i with i+1
    - Set i := i+1 
     UNTIL ((target reached) or (no points can be marked)) 
    Step 3:- go to the target point REPEAT 
    - go to next node that has a lower mark than the current node
    - add this node to path UNTIL (start point reached)
     Step 4: - Block the path for future wirings 
    - Delete all marks

Now we will write  the Python code for Lee Algorithm in Python 3.8.0 (lee.py)

And now we will make our maze or board in Python (board.py)

After writing the whole code now we will run our file lee.py, we get

implementation of Lee Algorithm in Python 3.8.0

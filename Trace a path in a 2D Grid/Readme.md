## Trace a path in a 2D Grid

Two points are given on a grid() represented by a 2D list along with hurdles. Make moves-Left, Right, Up, Down to trace path from one point to another. Make sure not to go out of boundaries of grid or pass throught hurdles. '+' denoted current position and '*' denotes traversed path.

    Example:
    Given Grid:
    Starting Point: (2,0)
    End Point: (0,2)
    Hurdles are marked by 0
    [
    [   ,   , 2 ]
    [   , 0 ,   ]
    [ 1 ,   ,   ]
    ]
    Trace a path from 1 to 2
    Enter one of the options- Up, Down, Right, Left: Up
    [
    [   ,   , 2 ]
    [ + , 0 ,   ]
    [ 1 ,   ,   ]
    ]
    Enter one of the options- Up, Down, Right, Left: Right
    Encountered a hurdle, choose another option: Up
    [
    [ + ,   , 2 ]
    [ * , 0 ,   ]
    [ 1 ,   ,   ]
    ]
    Enter one of the options- Up, Down, Right, Left: Left
    Going out of grid, choose another option: Right
    [
    [ * , + , 2 ]
    [ * , 0 ,   ]
    [ 1 ,   ,   ]
    ]
    Enter one of the options- Up, Down, Right, Left: Right
    [
    [ * , * , 2 ]
    [ * , 0 ,   ]
    [ 1 ,   ,   ]
    ]
    Well done you reached 2.

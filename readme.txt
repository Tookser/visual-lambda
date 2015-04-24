
Run:

python manipulator.py




--------------------------------------------------------
Interface



Items
    Input from console                  I
        Examples:
            >> \\x y. (\\x. x)
            >> FACT 3                   (see library.txt)
            >> "Label"
    
    Select, Drag                        Left mouse button
    
    With selected item
        Delete                          D
        Copy                            C

    Add Free Variable                   V


Zoom View                               Mouse Wheel
Refresh View                            F5


Reduce Selected                         Enter
Nonstop reduction                       Ctrl+Enter


Modes of reduction
    Applicative/Normal                  Alt+A
    Lazy/Pure                           Alt+L, Alt+P
    Inside selection                    Alt+S
    
    Quick Mode                          Q
        Pick for reduction


Construction of terms
    Expand selection                    Space
    
    Add Free Variable                   V
    
    With selected sub-term
        Delete                          Delete
        Insert Application before       Insert,      A
        Insert Application after        Ctrl+Insert, Ctrl+A
        Insert Lambda                   Alt+Insert,  L
        Bind Variable/Lambda with 
          selected Lambda/Variable      Right Mouse Button
          
    Applicate                           Drop Item onto another

    Substitute for free variable 
        with Item                       Drop Item onto free variable

    

History
    Undo                                Ctrl+Z, Alt+Left, Backspace
    Redo                                Ctrl+Y, Alt+Right           

Workspace
    Save                                Ctrl+S
    Load                                Ctrl+O
    


Zoom                                    Wheel



Save screen to bmp                      F12
Mode of export frames                   Alt+E

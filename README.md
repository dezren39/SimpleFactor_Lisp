# SimpleFactor_Lisp
Trying out a new language for me.

    (defun ^ (base exponent &optional (total 1))
        (loop for exponent from 1 to exponent do
            (setf total (* base total)))
        total)

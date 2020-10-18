# 8. (Challenging!) Find a predicate and a set of additional constraints so that CACC is infeasible with respect to some clause, but GACC is feasible.

- Thuộc tính ``a ^ (b <-> c)`` là tập GACC đạt được nhưng bị giới hạn nhưng CACC thì không.
		 +) Các mệnh đề đó l à:  ``a = (x<y),   b = odd(x), c = odd(y)``
		 +) ``x+y`` là các số chẵn bị giới hạn
		 
- Bộ GACC thỏa mãn và liên quan tới c but không thỏa mãn CACC là ``{(TTT,TFF)}`` or ``{(1,3),(2,4)}``

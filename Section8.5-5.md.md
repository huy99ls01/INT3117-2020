# 5. Consider the following deterministic finite state machine: .... (more in book)

- Các điều kiện để có thể quay trở lại:
	+ Idle: ``!a ^ !b``
	+ Active: ``!a ^ b``
	+ WindDown: ``!a``
- CACC tìm kiểm thử chuyển đổi cho trạng thái Active
	+ Active -> Idle: ``a ^ b, (a, b) = (T,F), (F,T), (T,F)``
	+ Active -> Idle: ``!b, (a, b) = (x, T), (x, F)``
	+ Active -> Active: ``!a ^ b, (a, b) = (F, T), (T, T), (F, F)``

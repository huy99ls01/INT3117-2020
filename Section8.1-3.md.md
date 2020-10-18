# 3. Write the predicate (only the predicate) to represent the requirement:“List all the wireless mice that either retail for more than $100 or for which the store has more than 20 items. Also list non-wireless mice that retail for more than $50.”

Nhận định thoả mãn: ``((mouseType = wireless) ^ ((retail > 100) v (stock > 20))) v (not(mouseType = wireless) ^ (retail > 50))``

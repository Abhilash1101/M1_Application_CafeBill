# Test Plan
|  Test ID | Description  | Expected Input  | Expected Output  | Actual Output  | Pass/Fail |
|---|---|---|---|---|---|
| TID_01  | Signup  | Username: XYZ<br />Password: xyz@123| 1  |1| PASS  |
| TID_02  | Login  | Username: XYZ<br />Password: xyz@123| 1  |1| PASS  |
| TID_03  | Login  | Username: XYZ<br />Password: xyz123| -1  |-1| PASS  |
| TID_04  | Adding Meals  |Food Code: 1.01<br />Food Name: Chicken Manchurian<br />Quantity: 1<br />Price: 100| SUCCESS  |SUCCESS| PASS  |
| TID_05  | Modifying Meals  |Food Code: 1.01<br />Food Name: Gobi Ka Paratha <br />Quantity: 1<br />Price: 200| SUCCESS  |SUCCESS| PASS  |
| TID_06 | View Menu  | Structure Address| SUCCESS  |SUCCESS| PASS  |
| TID_07  | Order Food  |Structure Address<br />Food Code<br />Quantity| SUCCESS  |SUCCESS| PASS  |
| TID_08 | View Previous Orders  | Structure address| SUCCESS  |SUCCESS| PASS  |
| TID_09 | Total Bill  |Food Code: 1.01<br />Quantity: 2 | 400  |400| PASS  |

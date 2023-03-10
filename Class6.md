**复合关系(composition of relations)**: R 是 A 到 B 的二元关系，S 是 B 到 C 的二元关系，则 R 与 S 的符合关系计为 `R੦S`

A B C 三个集合, A*R*B, B*R*C
a1 -> b2 -> c1
a1 -> b2 -> c3
a2 -> b4 -> c1

则 `R੦S = {(a1, c1), (a1, c3), (a2, c1)}`

`Matrix(R੦S) = Matrix(R) * Matrix(S)` 其中的乘法为布尔乘

关系的复合满足结合律: `(R੦S)੦T = R੦(S੦T)`

若 R,S 都是自反的，则 R੦S 是自反的
若 R,S 都是反自反的，但 R੦S 未必是反自反的
若 R,S 都是对称的，但 R੦S 未必是对称的
若 R,S 都是反对称的，但 R੦S 未必是反对称的
若 R,S 都是传递的，但 R੦S 未必是传递的

**逆关系(inverse relation)**: `R^-1`

`Matrix(R^-1) (Matrix(R))^T`

R = {(a1, b2), (a2, b1)}
R^-1 = {(b2, a1), (b1, a2)}

若 R 是自反的，则 R^-1 是自反的
若 R 是反自反的，则 R^-1 是反自反的
若 R 是对称的，则 R^-1 是对称的
若 R 是反对称的，则 R^-1 是反对称的
若 R 是传递的，则 R^-1 是传递的

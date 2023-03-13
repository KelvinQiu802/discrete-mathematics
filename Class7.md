**函数**:

f 是集合 A 到 B 的二元关系，且 A 中每个元素 a，存在 B 中唯一的元素 b 使得(a, b)属于 f, 记作 f(a) = b

- **a**: 自变量，原象 preimage
- **b**: 函数值，映象 image
- **集合 A**: 定义域 domain
- **集合 f(A)**: 值域 range

f 是 A 到 B 的函数表示为`f: A -> B`

**单射函数 injection**：一个 b 只对应一个 a，不存在一对多 |A| <= |B|, 可能有落单的 b

**满射 surjection**: 没有落单的 b，每个 b 都能对应到 a, |A| >= |B|, 可能存在 b 一对多

**双射 bijection**: 即是单射，又是满射。一一对应，|A| = |B|

**复合函数 composition of functions**:
f 是 A 到 B 的关系，g 是 B 到 C 的关系，则他们的复合函数是 g ੦ f，但他们的复合关系表示为 f ੦ g

若 f，g 都是单射，则 g ੦ f 也是
若 f，g 都是满射，则 g ੦ f 也是
若 f，g 都是双射，则 g ੦ f 也是

**逆函数 inverse function**: f ^ -1

**恒等函数**: I_A: A -> A
若 f: A -> B 为双射，则 f^-1 ੦ f = I_A, f ੦ f^-1 = I_B

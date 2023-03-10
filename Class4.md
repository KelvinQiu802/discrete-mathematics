**等价关系 equivalence relation**: 即自反，又对称，还传递

**等价类 equivalence class**: R 是等价关系, `[a]R = {b ∈ A: aRb}`

`[1]R` 代表所有在 A 中和 1 满足 R 关系的值组成的集合

**商集 quotient set**: 集合 A 上关于**等价关系** R 的不同**等价类的集合**

商集大，意味着，不同的等价类尽量多，也就是一个等价类里面的元素尽量的少

---

**偏序关系 partial order**: 即自反，又反对称，还传递，此时(A, R)为偏序集合 partial set，记作`(A, ≤)`

哈斯图 hasse diagram

**极大元**：没别的人管的
**级小元**：不管别人的
**最大元**：必须管住所有的元素
**最小元**：被所有元素管住

- 定理：

  - 最小元必为级小元
  - 最小元若存在，必唯一

- 给定偏序集 A，为有限集，
  - 则极小和极大元一定存在
  - 最小元不存在当且仅当存在至少两个极小元
  - 最小元存在当且仅当有一个极小元

**上界(upperbound)**：A 是偏序集，B 是 A 的子集，只要 A 中的一个 a 能管住 B 里的所有元素，则称 a 为子集 B 的上界

**上确界(supremum)**: 所有上界中，序最靠前的

**下界(lowerbound)**：A 是偏序集，B 是 A 的子集，只要 A 中的一个 a 能被 B 里的所有元素管住，则称 a 为子集 B 的下界

**下确界(infimum)**: 所有下界中，序最靠后的

**全序集(totally ordered set)**：任何两元素**可比**`(a ≤ b or b ≤ a)`的偏序集

**良序集(well-oredered set)**：任何非空子集都有下界的全序集

- 定理：
  - 给定二元关系 R：若是反自反和传递，则也一定是反对称

# baduk-opening-book
This repository contains opening books for the game of go/baduk/weiqi. Books can be especially useful for matchmaking of engines removing duplicate games while preventing any temperature induced potential imbalance due to different levels of policy sharpness between engines.

## 4-move opening books
These opening books consist of 4 corner moves, which is considered fairly balanced whichever the engine is. 
* 4m_nosymm_with33: 512 openings. Allowed corner moves are [4-4, 3-4, 4-3, 3-3], and symmetrically duplicate openings are included.
* 4m_nosymm_without33: 162 openings. Same as above, but without 3-3.
* 4m_symm_with33: 212 openings. Allowed corner moves are [4-4, 3-4, 4-3, 3-3], and each opening is unique under symmetry operations.
* 4m_symm_without33: 69 openings. Same as above, but without 3-3.
* 4m_symm_without33_handpicked: 37 openings. A hand-picked subset of 4m_symm_without33.

Origin source: JM Reference Software 19.0

# About this prj
- This prj modify the open source: 
  - Add 4 intra mode decision in order to improve compress performance
  - Add an algorithms for quick selection mode for intra coding
# Result
- With add intra mode: lightly improve compress performance
- With quick select alg:
  - `With input=foreman, QP <= 28, the result shows that the time to encode reduce up to 20%, while the bitrate only increase <= 4.62%. This is very good tradeoff between birate & time(also comtutational complexity)`
  ![Picture2](https://github.com/Truongdhvnu/JM_modify_intra/assets/122275694/952f1b37-9fe1-4713-a3ae-d0a13c9d22bc)
  - `tradeoff with other input files, you may find this test file in this source code`
  ![Picture1](https://github.com/Truongdhvnu/JM_modify_intra/assets/122275694/8134b63d-3af8-46f2-b1b6-14a8066f5d65)


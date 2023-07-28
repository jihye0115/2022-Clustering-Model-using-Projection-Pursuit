# 2022-Clustering-model-using-Projection-Pursuit

### 이화여대 통계학 석사 학위 논문 
- Paper 스터디 : 2022.01 ~
- 모델 : Projection Pursuit (사영 추적)
- Tool : R 
- 관련 Skill : 차원축소, Clustering

<br> </br>
💡 주제 <br>
차원축소 방법론인 Projection Pursuit(PP)을 이용하여 고차원 데이터를 원하는 정보를 담고있는 방향의 저차원으로 투영시켜가며, 반복적으로 클러스터링하는 기법을 제안한다.


💡 강점 <br>
PP는 Index를 통해 원하는 정보를 반영하여, 고차원 데이터를 원하는 정보에 따라 다양한 방향으로 클러스터링하여 결과를 비교할 수 있다.

<br>
(예시) 4개의 클래스로 이루어진 2차원 데이터 -> 중심이 모여있는 방향을 찾는 Holes Index를 통해 클러스터링
![image](https://user-images.githubusercontent.com/77092027/189475034-b6c4bece-cd73-4dee-9e68-ada29eb94103.png)


## Study Reference Paper
[1주차] :page_with_curl: Nanga, Salifu, et al. "Review of Dimension Reduction Methods." Journal of Data Analysis and Information Processing 9.3 (2021): 189-231. <br>
[2주차] <br>:page_with_curl: Jolliffe, Ian T., and Jorge Cadima. "Principal component analysis: a review and recent developments." Philosophical Transactions of the Royal Society A: Mathematical, Physical and Engineering Sciences 374.2065 (2016): 20150202. <br>
:page_with_curl: Modarresi, Kourosh. "Unsupervised feature extraction using singular value decomposition." Procedia computer science 51 (2015): 2417-2425. <br>
[3주차] :page_with_curl: Friedman, Jerome H., and John W. Tukey. "A projection pursuit algorithm for exploratory data analysis." IEEE Transactions on computers 100.9 (1974): 881-890. <br>
[4주차] :page_with_curl: Cook, Dianne, Andreas Buja, and Javier Cabrera. "Projection pursuit indexes based on orthonormal function expansions." Journal of Computational and Graphical Statistics 2.3 (1993): 225-250. <br>
[5주차] :page_with_curl: Espezua, Soledad, et al. "A Projection Pursuit framework for supervised dimension reduction of high dimensional small sample datasets." Neurocomputing 149 (2015): 767-776. <br>
[6주차] <br>:page_with_curl: Lee, Eun-Kyung, and Dianne Cook. "A projection pursuit index for large p small n data." Statistics and Computing 20.3 (2010): 381-392. <br>
:page_with_curl: Lee, Eun-Kyung. "PPtreeViz: An R package for visualizing projection pursuit classification trees." Journal of Statistical Software 83 (2018): 1-30. <br>
[7주차] :page_with_curl: Grochowski, Marek, and Włodzisław Duch. "Constrained learning vector quantization or relaxed k-separability." International Conference on Artificial Neural Networks. Springer, Berlin, Heidelberg, 2009. <br>
[8주차] :page_with_curl: Thrun, Michael C., and Alfred Ultsch. "Using projection-based clustering to find distance-and density-based clusters in high-dimensional data." Journal of Classification 38.2 (2021): 280-312. <br>
[10주차] :page_with_curl: Laa, Ursula, et al. "Hole or grain? a section pursuit index for finding hidden structure in multiple dimensions." Journal of Computational and Graphical Statistics (2022): 1-14.

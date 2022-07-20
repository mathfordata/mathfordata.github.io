# Errata

Send information on any mistakes found to *mathfordata /at/ gmail.com*

---
* page 3 : line 14 should have condition "0.1 <= y <= 0.6" instead of "0.1 <= 0.6" in the definition of set B.  

* page 43 : vector v should be [v1;...;vd] 
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 46 :  "Example: Adding Vectors" -> "Example: Adding Matrices"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* page 47 : The last sentence in example box, "upper right corner" should be "upper left corner"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* page 54 : in Example box: "eigenvector \lambda_2" should be "eigenvalue \lambda_2"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* page 54 : the determinant section:  the vectors b-a and d-c should be (b,a) and (d,c)
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
 
* page 64 : second paragraph of 4.2.3: d_cos(A,B) should be d_cos(alb)
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* pages 73, 151, 244 : A code block invokes "SciPy" when it should invoke "scipy" with all lower case letters.  

* page 84 : the second paragraph of 4.6.3 should discuss "false negatives" not "false positives"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 104 : last element of y should be y_n not v_n
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 108 : the right term of SS_{reg} should be ||r||^2
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 117 : the first X_6^T in the third paragraph should be X_4^T
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 148 : "non-decreasing" should be "non-increasing"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* page 154 : For matrices U, V from the SVD the book states the Frobenious norm of these matrices is 1 (that is, \|\|U\|\|_F=1 and \|\|V\|\|_F=1).  It should state the spectral norm is 1 (that is, \|\|U\|\|_2=1 and \|\|V\|\|_2=1), and point out they are norm-preserving under multiplication.  [h/t David R. Gurney](https://www.maa.org/press/maa-reviews/mathematical-foundations-for-data-analysis)

* page 156 : the formula on the bottom should have sigma_j^2 instead of sigma_i^2
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 156 : footnote: "the right n-d rows of U" should be "the right n-d columns of U"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* page 160 : the "top k right singular values V_k" should be "top k right singular vectors V_k"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* page 163 : Let E_i be an nxn matrix that is all 0s except the ith column which is all 1s, and Z an nxn matrix.  The books states E_i Z has each column as the ith column of Z, and Z E_i^T has each row as the ith row of Z.  It should almost be the reverse where E_i Z has each row as the ith row of Z, and Z E_i^T has each row as the ith column of Z.   [h/t David R. Gurney](https://www.maa.org/press/maa-reviews/mathematical-foundations-for-data-analysis)

* page 243 : Ergodic Markov Chains box should have q_* not q^*
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 252, 254 : different implementation of the eigen-decomposition give somewhat different outputs for laplacians L_0 and L in the examples.  These are computed with octave's eig function.  Moreover, an eigenvalue/eigenvector pair is missing for the decomposition of L_0.  
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

* page 263 : second last line has an extra "m'+1"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
* page 272 : Algorithm 11.2.4 should say "Count Sketch" not "Count-Min Sketch"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)
  
page 272 : the last formula "C_{i,h_i}(q)" should be "C_{i,h_i(q)}" where (q) is in the subscript.  
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

page 274 : the second to last paragraph should say "the eigenvalues of C are the squared singular values of A" not "of C"
  [h/t Bolin Chen](https://teacher.nwpu.edu.cn/m/en/2015010039.html)

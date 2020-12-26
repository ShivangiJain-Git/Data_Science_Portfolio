#  DOMAIN : HEALTHCARE


- ### CONTEXT 
  Predict the type of Breast Cancer (M = malignant and B= benign) in the Breast Cancer Wisconsin(Diagnostic)Data Set.

 
- ### OBJECTIVE
  To detect Breast Cancer using KNN 


- ### DATASET 
  wisc_bc_data.csv

Variable - Description 

a) radius (mean of distance from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2/ area - 1.0)

g) concavity (severity of concave portions of the contour 

h) concave points(number of concave portions of the contour)

i) symmetry

j)fractal dimensions ("coastline approximation" -1)

The mean,standard deviation and worst or largest (mean of three largest values) of these features were computed for each image , resulting in 30
features. For instance , field 3 is mean radius , field 13 radius standard deviation etc. 


1. id

2. diagnosis

3. radius_mean

4. texture_mean

5. perimeter_mean

6. area_mean

7. smoothness_mean

8. compactness_mean

9. concavity_mean

10. points_mean

11. symmetry_mean

12. dimension

13. radius_se

14. texture_se

15. perimeter_se

16. area_se

17. smoothness_se

18. compactness_se

19. concavity_Se

20. points_se

21. symmnetry_se

22. dimension_se

23. radius_worst

24. texture_worst

25. perimeter_worst

26. area_worst

27. smoothness_worst

28. compactness_worst

29. concavity_worst

30. points_worst

31. symmetry_worst

32. dimension_worst


- ### Notebook
  KNN_Breast_Cancer_Detection.ipynb

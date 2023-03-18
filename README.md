# lab_2_ImageArea__polymorphism-_and_-bstraction
Create a class called ImageArea which will store the width and the height of an image. Create a method called get_area() which will return the area of the image. We have also to implement all the magic methods for comparison of two image areas (>, >=, <, <=, ==, !=), which will compare their areas.

Test Code

a1 = ImageArea(7, 10)
a2 = ImageArea(35, 2)
a3 = ImageArea(8, 9)
print(a1 == a2)
print(a1 != a3)

Output
True
True

## Time Table Allocation

### Expected inputs

- Course list along with faculty.
- Data about each Course(is IC course, and special list of course which should not clash).
- Course registration list of each student.

### Clash weights

- Clash b/w courses of same faculty: INF.
- Clash b/w course have same students: Sigmoid function (1)/(1+e^(-x))

### Expected Output

- Assign course to slot from A-H(8 slots), so as to minimize the clashes.

### Technology stack

- Web interface in django.
- Allocation algorithm will be written in java.
- Django(python) with the required java code.

# EX-No.6.1. DESIGN THE VARIOUS PARTS OF A MECHANICAL COMPONENT AND ASSEMBLE

## DATE:

## AIM: 
To Design the various parts of a mechanical component and assemble it using a bottom-up approach then convert it into the orthographic view

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 4 GB of RAM (integrated graphics recommend 6 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## COMMANDS USED:
### Align: 
The Align tool allows you to align, distribute or organize selected elements, annotations, tags and text along the axis you specify. Furthermore, the Arrange feature will automatically neatly place your tags around the current view.
The Align plug-in for Autodesk® Revit® can help to save time while producing complex drawings with large sets of annotation.
Just select a few elements and the Align tool will sort them for you.

### Derive:
Insert design elements such as Components, Bodies, Sketches, Work geometry, Flat patterns or parameters from another design.
The inserted elements update with changes to the original design

### Move: Moves the selected face, body, sketch, or construction geometry a specified distance or angle.
Select the objects to modify then specify the distance or angle. Use set pivot to reposition the manipulator

## PROCEDURE:
### STEP 1: 
 Identifying the given model.

### STEP 2: Importing the components.
Firstly, we import all the necessary parts into the assembly project. Here, we use Finger, gear linkage, Secondary Linkage, Base. For, Importing the components into the project, we use the insert derive option in the Insert>Insert Derive.

### STEP 3: 
We place the base model onto the X-Y plane.

### STEP 4: Aligning the components
Then we align the imported, Gear linkage model, in its respective slot of the base.
For aligning the component onto the base, we use the align option, available in Modify>Align.
For aligning the component onto the base, we first select the “from” coordinates then we select the “To” coordinates in the given base model. At first, the model might not align properly, so, we use the flip option to bring the component to the desired position.

### STEP 5: 
We follow the same steps for aligning the components onto their respective      slots on the base component.

### Note: 
If the components do not fit properly into the slots, it can be moved into the slot using the Move option.

## INPUT: 

#### LINKAGE
![image](https://user-images.githubusercontent.com/113594316/199413513-8fa5b9db-0546-49d0-ad4c-230b22984d3c.png)

#### BASE PLATE  
![image](https://user-images.githubusercontent.com/113594316/199413545-3b2fd515-6e27-4d28-9da3-c9ce20cb2a42.png)

#### GEAR LINKAGE
![image](https://user-images.githubusercontent.com/113594316/199413566-05708531-fc78-44c9-ab98-4f8a9066d318.png)

#### FINGER
![image](https://user-images.githubusercontent.com/113594316/199413594-5de9578e-5800-4e69-8c76-6a5749e31805.png)

#### ASSEMBLED VIEW
![image](https://user-images.githubusercontent.com/113594316/199413636-df0a61ce-964f-490d-9a16-e5986ebbf403.png)

## OUTPUT:
```python
def f(x):
return x**3-x-2
def f1(x):
return 3*x**2-1
xo=float (input ("Enter the initial approximation: "))
for i in range (1,10):
xn=xo-f(xo)/f1(xo)
xo=xn
print ("The approximate root using Newton-Raphson method is %.4f"%xn)
```
```python
def f(x):
return x**3-x-2
def f1(x):
return 3*x**2-1
xo=float (input ("Enter the initial approximation: "))
for i in range (1,10):
xn=xo-f(xo)/f1(xo)
xo=xn
print ("The approximate root using Newton-Raphson method is %.4f"%xn)
```
```python
x= [0,1,2,4,5,6]
y= [1,14,15,5,6,19]
s=float (input ("Enter the value of x to be in: "))
sum=0
for i in range (0,6):
prod=1
for j in range (0,6):
if i!=j:
prod=prod*(s-x[j])/(x[i]-x[j])
sum=sum+prod*y[i]
print ("The functional value is %.4f"%sum)
```python
def f(x):
return 1/(1+x**2)
a=float (input ("Enter the lower limit: "))
b=float (input ("Enter the upper limit: "))
h=float (input ("Enter the step size: "))
n=int((b-a)/h)
sum=0
for i in range (1, n):
sum=sum+f(a+i*h)
trap=h/2*(f(a)+f(b)+2*sum)
print ("The Integral value is %.5f"%trap)
```
```python
def f (x, y):
return x+y**2
x0=float (input ("Enter initial point of x: "))
y0=float (input ("Enter initial point of y: "))
h=float (input ("Enter step value h: "))
k1=h*f (x0, y0)
k2=h*f (x0+h/2,y0+k1/2)
k3=h*f (x0+h/2,y0+k2/2)
k4=h*f (x0+h,y0+k3)
y=y0+(k1+2*k2+2*k3+k4)/6
print ("The value of y using RK method is %.4f"%y)
```
```python
def f (x, y):
return x**2*(1+y)
x0=float (input ("Enter x0: "))
y0=float (input ("Enter y0: "))
x1=float (input ("Enter x1: "))
y1=float (input ("Enter y1: "))
x2=float (input ("Enter x2: "))
y2=float (input ("Enter y2: "))
x3=float (input ("Enter x3: "))
y3=float (input ("Enter y3: "))
h =0.1
y4p=y3+(h/24) *(55*f(x3,y3)-59*f(x2,y2)+37*f(x1,y1)-9*f(x0,y0))
x4=x3+h
y4c=y3+(h/24) *(9*f(x4,y4p) +19*f(x3,y3)-5*f(x2,y2)+f(x1,y1))
print ("Approximate soln is %0.4f"%y4c)
```

## RESULT:
Thus, a design of various parts of a mechanical component and assemble it using a bottom-up approach in orthographic view has been done

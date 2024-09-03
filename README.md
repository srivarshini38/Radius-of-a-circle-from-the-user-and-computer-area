# Radius-of-a-circle-from-the-user-and-computer-area
Accept the radius of the circle and compute its area
def calculate_circle_area():
    radius = float(input("Input the radius of the circle: "))
    area = math.pi * (radius ** 2)
    print(f"The area of the circle with radius {radius} is: {area}")

calculate_circle_area()

- 👋 Hi, I’m @Farhan111222
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Farhan111222/Farhan111222 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class Circle:

    def __init__(self):
        self.radius = 0
        self.diameter = 0
        self.cirumference = 0
        self.area = 0

    def set_radius(self, r):
        self.radius = r

    def set_diameter(self):
        self.diameter = 2 * self.radius

    def set_circumference(self):
        self.cirumference = 2 * 3.14 * self.radius

    def set_area(self):
        self.area = 3.14 * (self.radius ** 2)

    def get_radius(self):
        return self.radius

    def get_diameter(self):
        return self.diameter

    def get_circumference(self):
        return self.cirumference

    def get_area(self):
        return self.area


c1 = Circle()
c1.set_radius(12)
c1.set_diameter()
c1.set_circumference()
c1.set_area()

print('RADIUS:  ', c1.get_radius())
print('DIAMETER:  ', c1.get_diameter())
print('CIRCUMFERENCE:  ', c1.get_circumference())
print('AREA:  ', c1.get_area())

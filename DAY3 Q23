import matplotlib.pyplot as plt
with open('test.txt', 'r') as file:
    data = file.readlines()
x_values = [float(line.split()[0]) for line in data]
y_values = [float(line.split()[1]) for line in data]
plt.plot(x_values, y_values)
plt.xlabel('X Axis Label')
plt.ylabel('Y Axis Label')
plt.title('Title of the Plot')
plt.show()

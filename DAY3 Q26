import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(0, 10, 100)
y1 = np.sin(x)
y2 = np.cos(x)
fig, axs = plt.subplots(2)  # 2 rows of plots
axs[0].plot(x, y1, color='blue', label='sin(x)')
axs[0].set_title('Plot of sin(x)')
axs[0].set_xlabel('x')
axs[0].set_ylabel('sin(x)')
axs[0].legend()
axs[1].plot(x, y2, color='red', label='cos(x)')
axs[1].set_title('Plot of cos(x)')
axs[1].set_xlabel('x')
axs[1].set_ylabel('cos(x)')
axs[1].legend()
plt.tight_layout()
plt.show()

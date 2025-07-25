```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.scatterplot(x='distance_km', y='fare_amount', data=data, alpha=0.3)
plt.title('Fare Amount vs. Distance')
plt.xlabel('Distance Traveled (km)')
plt.ylabel('Fare Amount ($)')
plt.show()
```
#screenshoot
![](sceenshot/img.png)

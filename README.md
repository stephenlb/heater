# PyTorch Heatmap Visualizer for 1D Vectors and 2D Matrix Tensors

```python
a = torch.rand(40,20)
heater.plot(a, theme='heatmap')
```

![Example Heatmap](images/example1.png)


```python
b = torch.linspace(0,1, steps=800).view(40,20)
heater.plot(b, theme='heatmap')
```

![Example Heatmap](images/example2.png)


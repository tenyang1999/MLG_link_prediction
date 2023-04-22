# 社群網路與推薦系統作業二：MLG_link_prediction

- 社群網路與推薦系統作業二：針對給定的資料集去預測link

## 功能

- 透過Encoder&Decoder的方式去取得link probability
- loss取用BCEloss()
- 
## 安裝
- 本次執行上會需要用到的package

```python
pip install torch
pip install torch_scatter torch_sparse torch_cluster torch_spline_conv torch_geometric -f https://data.pyg.org/whl/torch-1.13.0+cu117.html
```

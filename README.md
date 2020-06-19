File | # Train Images | # Epochs | Data Augmentation | Continue Trained On 
:--------:|:--------------:|:--------:|:-----------------:|:---------------:|
UN_600_50e.ipynb | 600 | 50 | HFlip | × 
UN_1000_50e.ipynb | 1000 | 50 | HFlip | ×
UN_2000_30e.ipynb  | 2000 | 30 | HFlip | UN_600_50e.ipynb
UN_8000_30e.ipynb  | 8000 | 30 | HFlip | UN_2000_30e.ipynb 
UN_10000_20e_aug.ipynb  |  10000   |   20   |     <font color=red>HFlip, VFlip, ColorJitter</font>      |   UN_1000_50e.ipynb
UN_10000_20e_aug2.ipynb |  10000   |   20   |     HFlip, VFlip, ColorJitter      |   UN_10000_20e_aug.ipynb<br>

`UN_600_50e --> UN_2000_30e --> UN_8000_30e`<br>
`UN_1000_50e --> UN_10000_20e_aug --> UN_10000_20e_aug2`

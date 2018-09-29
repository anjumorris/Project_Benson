# Project_Benson
### Team Jaguars

> #### Datasets
>
>  	1. MTA Turnstile data - 3 months - from 4/28/2018 to 07/27/2018
>  	2. Tech ... please fill 



> #### Tools
>
> 1. Numpy
> 2. Pandas
> 3. Matplotlib
> 4. Seaborn
> 5. Google ... please fill 



#### How to run ?

Ensure that output_stage2.csv file is generated before running the rest of the notebooks

``` mermaid
graph TB
A[read_data.ipynb]-->B(DATA: output_stage1.csv)
B-->C[clean_data.ipynb]
C-->D(DATA: output_stage2.csv)
D-->E[select_top_10_stations.ipynb]
E-->F[week_top_10.ipynb] 
F-->G[heatmap.ipynb]
```



>
>
>
>
>
>
>
>
> ``` flow
> read=>operation: read_data.ipynb
> stage1=>start: output_stage1.csv
> clean=>operation: clean_data.ipynb
> stage2=>start: output_stage2.csv
> top=>operation: select_top_10_stations.ipynb
> week=>operation: week_top_10.ipynb
> heat=>operation: heatmap.ipynb
> 
> read->stage1->clean->stage2->top->week->heat
> ```
>
>




# Python Data Visualization

Python + 데이터시각화로 할 수 있는 다양한 팁들과 튜토리얼을 만드는 것을 목표로 합니다.

## Libraries

> `use`는 제가 사용해본 라이브러리 체크를 위해 만들었습니다

### Static

범용적으로 사용하는 정적 데이터 시각화 라이브러리입니다. 

matplotlib의 경우에는 인터랙티브하게 사용할 수 있으나 보통 정적 데이터 시각화에 많이 활용합니다.

| Name           | Description                                | Documentation                                          | Github                                             | use |
| -------------- | ------------------------------------------ | ------------------------------------------------------ | -------------------------------------------------- | --- |
| **matplotlib** | 가장 기본적이고 범용적인 시각화 라이브러리 | [matplotlib](https://matplotlib.org/)                  | [github](https://github.com/matplotlib/matplotlib) | O   |
| **seaborn**    | matplotlib을 베이스로하는 통계 시각화      | [seaborn](http://seaborn.pydata.org/)                  | [github](https://github.com/mwaskom/seaborn)       | O   |
| **plotnine**   | ggplot2을 사용할 수 있는 라이브러리        | [plotnine](https://plotnine.readthedocs.io/en/stable/) | [github](https://github.com/has2k1/plotnine)       | X   |

- [Matplotlib Tutorial](/matplotlib/README.md)
- [Seaborn Tutorial](/matplotlib/README.md)

### Interactive

인터랙티브 시각화 라이브러리 입니다. 위의 툴들보다 훨씬 다채로운 시각화를 진행할 수 있습니다.

이 라이브러리들도 다양한 시각화를 지원합니다. (네트워크, 지도, 등등)

| Name          | Description | Documentation                            | Github                                            | use |
| ------------- | ----------- | ---------------------------------------- | ------------------------------------------------- | --- |
| **plotly**    |             | [plotly](https://plot.ly/python/)        | [github](https://github.com/plotly/plotly.py)     | O   |
| **bokeh**     |             | [bokeh](https://bokeh.org/)              | [github](https://github.com/bokeh/bokeh)          | O   |
| **altair**    |             | [altair](https://altair-viz.github.io/)  | [github](https://github.com/altair-viz/altair)    | O   |
| **pygal**     |             | [pygal](http://www.pygal.org/en/stable/) | [github](https://github.com/Kozea/pygal)          | X   |
| **pyecharts** |             | [pyecharts](https://pyecharts.org/)      | [github](https://github.com/pyecharts/pyecharts/) | X   |

### Network

관계를 시각화하는 라이브러리 입니다. 

| Name              | Description | Documentation                                                | Github                                            | use |
| ----------------- | ----------- | ------------------------------------------------------------ | ------------------------------------------------- | --- |
| **networkx**      |             | [networkx](https://networkx.github.io/documentation/stable/) | [github](https://github.com/networkx/networkx)    | O   |
| **python-igraph** |             | [python-igraph](https://igraph.org/python/)                  | [github](https://github.com/igraph/python-igraph) | X   |

### Geo

지도/지리 데이터 시각화 라이브러리입니다.

| Name           | Description                      | Documentation                                                                          | Github                                                                                 | use |
| -------------- | -------------------------------- | -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | --- |
| **folium**     | leaflet.js                       | [folium](https://python-visualization.github.io/folium/)                               | [github](https://github.com/python-visualization/folium)                               | O   |
| **geopandas**  |                                  | [geopandas](https://geopandas.readthedocs.io/en/latest/)                               | [github](https://github.com/geopandas/geopandas)                                       | X   |
| **googlemaps** | 구글 지도 API                    | [googlemaps](https://googlemaps.github.io/google-maps-services-python/docs/index.html) | [github](https://github.com/googlemaps/google-maps-services-python)                    | X   |
| **kepler.gl**  | Jupyter Widget으로 사용가능 (3D) | [kepler.gl](https://docs.kepler.gl/docs/keplergl-jupyter)                              | [github](https://github.com/keplergl/kepler.gl/tree/master/bindings/kepler.gl-jupyter) | X   |

### ETC

특수한 목적의 시각화 라이브러리입니다. 이 라이브러리는 Matplotlib을 기반으로 만들어졌습니다.

| Name          | Description   | Documentation                                          | Github                                               | use |
| ------------- | ------------- | ------------------------------------------------------ | ---------------------------------------------------- | --- |
| **missingno** | 결측치        |                                                        | [github](https://github.com/ResidentMario/missingno) | O   |
| **pywaffle**  | 와플 차트     | [pywaffle](https://pywaffle.readthedocs.io/en/latest/) | [github](https://github.com/gyli/PyWaffle)           | O   |
| **wordcloud** | 워드 클라우드 | [wordcloud](https://amueller.github.io/word_cloud/)    | [github](https://github.com/amueller/word_cloud)     | O   |
| **squarify**  | 트리맵        |                                                        | [github](https://github.com/laserson/squarify)       | O   |

- [ETC Tutorial](/etc/README.md)

### Interpretable AI

머신러닝 모델의 해석을 위해 만들어진 라이브러리입니다. (제 목표이기도 합니다.)

| Name         | Description     | Documentation                                                 | Github                                      | use |
| ------------ | --------------- | ------------------------------------------------------------- | ------------------------------------------- | --- |
| **SHAP**     | Shapley + @     | [SHAP](https://shap.readthedocs.io/en/latest/#)               | [github](https://github.com/slundberg/shap) | O   |
| **dtreeviz** | 결정트리 시각화 | [dtreeviz](https://explained.ai/decision-tree-viz/index.html) | [github](https://github.com/parrt/dtreeviz) | O   |
| **LIME**     |                 | [LIME](https://lime-ml.readthedocs.io/en/latest/lime.html)    | [github](https://github.com/marcotcr/lime)  | X   |


### 데이터를 다루는 라이브러리

| Name       | Description                  | Documentation                         | Github                                             | use |
| ---------- | ---------------------------- | ------------------------------------- | -------------------------------------------------- | --- |
| **numpy**  | 벡터 및 행렬 연산 라이브러리 | [matplotlib](https://matplotlib.org/) | [github](https://github.com/matplotlib/matplotlib) | O   |
| **pandas** | 데이터 분석 라이브러리       | [seaborn](http://seaborn.pydata.org/) | [github](https://github.com/mwaskom/seaborn)       | O   |

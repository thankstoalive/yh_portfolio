# Batch effect correction

프로젝트 기간: 2022.05~2022.08 (4개월)  

본 프로젝트의 목표는 순수한 생물학적 정보를 얻기 위해 대사체 분석에서 여러 종류의 에러를 탐색하고 교정하는 것입니다. 에러는 실험일, 분석기기, 실험자, 균주 로트, human error 등이 포함되어 있습니다. 

탐색 결과, 실험일이 가장 큰 에러로 판단되어, 이를 배치로 취급하여 correction을 진행하였습니다. 교정 방법으로는 QC-based normalization 중에서 batch ratio, batch loess, SERRF, TIGER 방법을 적용하였고, SERRF가 가장 잘 교정되었습니다. 기존 데이터 대비 RSD가 94% 감소하여 신뢰성이 높은 데이터를 얻을 수 있게 되었습니다.


## Example. SERRF normalization
![](./img/3_1.png)

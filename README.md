# folium_project

## Prerequisites

- Python 3.6+
- folium
- pandas
- selenium

## Process

The `directory` should look like:

    folium_project
    ├── cafemap
    │   ├── navermap_crawling.ipynb
    │   └── 영통카페정보.xlsx
    │   └── cafe_map.html
    │       
    └── 교통사고map
        ├── Cluster_교통사고지역.ipynb
        └── 도로교통공단_교통사고다발지역_20191010.csv
        └── cluster_accident.html

### 0. 개요

- 혁신적인 서비스를 제공하기 위한 접근성이 좋은 방법이 **시각화**라고 판단함<br>
- 핵심 데이터 시각화, 지도 시각화 등 인사이트 제공 가능


### 1. cafemap 프로젝트


- selenium 사용하여 원하는 정보의 위도 경도를 csv파일로 저장
- 카페, 음식 등 모든 검색어 가능 (selenium으로 자동화)

- 저장된 csv를 folium 패키지로 지도 시각화

### 2. 사고다발지역 프로젝트

- 교통사고다발지역 클러스터 지도 ( folium 패키지의 marketcluster 활용)
- 원하는 지역의 최근 교통사고 다발지역 표시

## References

- folium github

## Author

HyoJun Kim / [blog](http://rlagywns0213.github.io/)

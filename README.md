# KoreanNERCorpus
origianl 폴더에는 HLCT 2016에서 제공한 데이터셋 원본이 있습니다. 

modified 폴더에는 평가셋의 오류 41곳을 수정한 데이터셋이 있습니다.


dev_chg.txt에는 몇번째 줄을 수정하였는지와 어떤 정보를 수정하였는지에 대한 정보를 포함하였습니다.



다음은 수정한 오류의 예시입니다.
- 명백히 개체명인데 태그가 되어있지 않은 경우. 
	예를 들어 ‘<LG:OG>는 <7일:DT> 잠실구장에서 계속된’에서 잠실구장을 LC로 수정하였다. 
- POS 태그 수정.
	예를 들어 ‘태어난’이 ‘태 NNP 어 NNP 난 NNP’로 태그 되어있어 ‘태어나 VV ㄴ ETM’으로 수정하였다.
- 개체명이 아닌데 태그 되어있는 경우.
	예를 들어 ‘비디오점 <체인 씨네타운:OG>이’에서 체인은 개체명이 아닌데 씨네타운 기관명에 포함되어있어 O로 수정하였다. 

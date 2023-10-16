# Motion_recognition 
Posture evaluation and correction algorithm

![image](https://github.com/yoondev23/Motion_recognition/assets/128372198/1c429f35-83bc-4a98-9312-ef308a6c0f81)

* 건강상태에 따른 개인별 운동 추천 알고리즘: <br>
        - 개인별 건강상태 정보에 따라 상체/하체/전신 등 운동이 요구되는 부위에 해당하는 운동 추천 알고리즘

* 모션 인식 모델: <br>
        - 모바일 환경에 최적화된 모션 인식 모델을 이용하여 사용자의 모션을 인식

* 자세 평가 및 교정 알고리즘: <br>
        - 사전에 설정된 기준 운동 동작과의 유사도 분석을 통하여 관절별 자세 교정 데이터 추정 알고리즘
	ex)  “오른팔 위로 더 올리세요” 


![image](https://github.com/yoondev23/Motion_recognition/assets/128372198/bf0a655b-8cac-4a81-b40a-3fb49a0232ba)


* 다양한 신체의 모습을 세밀하게 분석할 수 있어야 하는 운동동작의 특징에 맞춰 기존에 널리 사용되던 17 keypoint에서 neck, palm, spine1/2, instep 등을 추가하여 24keypoint로 annotation

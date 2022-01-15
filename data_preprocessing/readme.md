### 데이터 전처리
data 파일에 필요한 파일 다 넣고, ipynb 넘버링 순서대로 돌리면 되도록 작업

ex) 1에서 전처리한 데이터를 data 파일에 저장하고, 2에서 불러와서 다시 작업할 수 있는 방식

<br>
넘버링 순서:


1_survey_data

2_scc_table : scc_user_doll_group, scc_doll, scc_doll_option, scc_agency

3_log_data: log_doll_drug_consume, log_emergency_push, scc_ear_function_log, log_doll

4_survey_modeling_data: 기존 데이터 이용하여 설문지 모델링용 데이터 생성
<br><br>

만들어지는 데이터: 

1: survey_preprocessed

2: merge_v5, merge_s_v5

3: log_merge1_v1, log_merge1_v2, log_merge2_v1, log_merge2_v2

4: surveydata_md, surveydata_md2

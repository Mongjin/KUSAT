# KUSAT

2020 국어정보시스템 경진대회 지정분야 감성분석 모델


nsmc 테스트 데이터 성능 : 90.81%


실행 환경 : Google Colab

실행 방법 : KUSAT 사용법.pptx

모델 코드: src/model/model.py

테스트 실행 파일 : https://drive.google.com/drive/folders/1-Yv6rszQy6r07zIODC3XpNliAEJORRGY?usp=sharing
<p>링크에 있는 ELECTRA_SA 폴더를 다운받으신 후에,
구글 드라이브 -> 내 드라이브에 업로드 하신 다음, SA_model.ipynb 파일을 구글 코랩에서 실행하시면 됩니다. 자세한 실행방법은 사용법 pptx 파일을 참고하세요</p>

<p> 데이터 포맷: txt 파일</p>
<p> 문장 \t(tab) 0 or 1 </p>
<p> 예시: 진심 엄청재밌다 이런 영화를 본적이 없었다. \t 1
<p> 0: 부정, 1: 긍정 </p>
<p> 위와 같은 데이터 포맷을 맞추어 주기 바랍니다. </p>




2차 접수

<p> 실행 방법은 동일합니다. 1차 접수때와 모델 파일이 변경되었으니 링크에 있는 최신 버전의 ELECTRA_SA 폴더를 다운받으시면 됩니다. 실행 방법은 pptx 파일을 참고하세요 </p>

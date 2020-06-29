# FoodRecommend

# foodList_utf:
식품안전정보포탈(식품정보나라)의 식품영양성분DB를 csv 파일로 변형한 dataset입니다. foodres.zip 안에 내재되어 있습니다.


# foodres: 
 python flask이용, 설문값과 식단입력정보가 들어오면 음식추천 및 식단결과페이지 출력하는 source
 foodres 내 main에서 실행 후 메인 프로젝트()에서 식단입력하면 결과페이지가 전송됩니다. 
 (IDE ECLIPSE jee-pydev, mysql workbench 8.0 CE사용) 


# spring_python2:
 python flask를 이용. 회원가입후->ID접속->영상쪽에서 자가진단(카테고리별Item) 입력정보가 들어오면
 파이썬 main에서 실행 이후 ID값이 들어오고 분석을 통해 콘솔값이 출력되면서 spring내의 mp4파일과 매칭됩니다. 
 (IDE ECLIPSE jee-pydev, mysql workbench 8.0 CE사용)

# 프로젝트 메인(업로드X):
 tomcat apache8.5, java1.8를 이용한 메인 프로젝트, 위에 있는 두 가지 python project 각 main에서 flask server 구동 후 2nd_Project index.jsp 실행하면 웹사이트 실행. 이후 Food탭의 식단입력과 working-out탭의 자가진단 제출시 flask server로 넘어온 객체 혹은 데이터를 전달합니다.  (IDE Spring sts, mysql workbench 8.0 CE사용)

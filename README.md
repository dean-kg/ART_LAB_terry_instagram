# ART_LAB_terry_instagram
* * *
## Art_lab 크롤링 파트 인턴 지원자료 만들기와 대표님에 대한 이해를 위해    
##        인스타를 크롤링 및 간단한 전처리와 데이터 분석 진행
* * *
* 1. 게시글 분석    
    #### 1.주차별 포스팅 숫자    
        
    <img src="/img/1.png" width="70%" height="70%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>    
    
    
    
    #### 2. 년도별 각 시간대의 포스팅 숫자   
        
    <img src="/img/4.png" width="70%" height="70%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>  
    
    
    #### 3. 전체 게시글 워드 크라우드   
        
    <img src="/img/5.png" width="70%" height="70%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>  


    #### 4. 해쉬태크   
        
    <img src="/img/2020-10-30_15_56_37_terr.png" width="70%" height="70%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>  


    #### 5. 인싸....   
        
    <img src="/img/insa.jpg" width="50%" height="50%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>  




* * *    
### 작업하며 느낀 소소한점들    
1. 인스타그램 은 미쳤다.. 이미지 크롤링을 위해 html tag 확인해보려고 하는데 인스타그램에서 사진에 대한 카테고리 분류를 다 해놓는것을 보고 충격먹었다.    
   인스타내부에서는 엄청난 AI데이터가공 소스가 있겠구나 생각    

<img src="/img/insta_power1.PNG.png" width="50%" height="50%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
<img src="/img/insta_power2.PNG.png" width="70%" height="70%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>

    
2. facebook api는 구글 api 만큼 친절하지 못하다. (단기간 완성 어려워서 보류)    
3. selenium을 이용한 수동노가다 작업으로 진행    
4. 오래 지난 게시글의 경우 작성시간 확인에 어려움이 있을것으로 초기 판단했지만 html상에아주 구체적으로 표시 되어있음 timezone은 utc-0 기준    
5. 한국의 경우 시간대 utc +9 ,캐나다 워털루의경우 시간대 utc -4    


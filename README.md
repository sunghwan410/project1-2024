
 # project1-2024
 2024-2학기 캡스톤 프로젝트 수업
 OpenAPI를 사용한 인공지능 시스템 실습

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)



<a href='https://ifh.cc/v-ybys4P' target='_blank'><img src='https://ifh.cc/g/ybys4P.jpg' border='0'></a>




 # openweathermap

    지정된 장소의 현재 날씨를 표시
'https://api.openweathermap.org/data/2.5/weather?q=london&units=metric&appid=7d96bc5108f52b80e2d9075a369b9f35'

```javascript
$.ajax({
         type: "GET",
         url: 'https://api.openweathermap.org/data/2.5/weather?q=london&units=metric&appid=7d96bc5108f52b80e2d9075a369b9f35',
      }).done(function(response) {

            console.log(response)
            }).fail(function(error) {
         alert("!/js/user.js에서 에러발생: " + error.statusText);
      });
```
    
 # openAI

 # google cloud vision

 개발순서

    1.소스수정
    2.소스 저장
    3.스테이지
    4.커밋에 푸쉬
    5.커밋메시지




=======
# project1-2024
2021143009_정성환

2024-2학기 캡스톤프로젝트1 중간시험 대체 과체

구글 비전 API를 사용하여 이미지를 업로드하고 얼굴 감지 및 감정 분석을 수행하는 HTML, JavaScript, CSS를 포함시켜 만든 웹 페이지 입니다.
이미지 분석을 하면 analyze 함수가 구글 비전 API에 POST 요청을 보내 얼굴 감지 결과를 받아와 분석하여 결과를 출력하게끔 했습니다.
그리고 밋밋하지 않게 css 코드를 넣어 파란색을 메인으로 깔끔하게 꾸며 봤습니다.
사진은 제가 좋아하는 걸그룹 에스파 한장,웃는 사진 한장 넣어봤습니다.

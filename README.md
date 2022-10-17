# foodmapsearch
## Purpose
This program was developed in order to find where the which restaurant has a best review about a certain keyword. This could be used to see where you should eat certain types of food that you want to eat based on customer reviews. Also, the reviews are collected from restaurants that are close to the user, which makes foodchoice very convenient. Even though this program was designed to search restuarants, it could also be used to search any place such as amusement park, stores, and more. 

## Parameter
<pre>
<code>
    # srch: search on map
    # menu1: review search 1
    # menu2: review search 2
    # sut: how many times are you going to press the 'view more' button

    srch = '꿔봐로우' 
    menu1 = '가지튀김'
    menu2 = '가지 튀김'
    sut = 3   
</code>
</pre>

   * The 'srch' value is what you are going to search on the map. For example, if you search steak, various steakhouses will appear. 
   * 'menu1' is what you want keyword in the review of restaurants that you are going to look for through the program. 
  * 'menu2' is additional keyword that the program is going to look for from the reviews in addition to menu1. This could also be used to search a keyword with space in between. For example, when you want to search up frenchfries and french fries, each keyword could be input in menu1 and menu2
  * 'sut' is how many times you want to press on the 'view more' button in the review tab to see more reviews. 

## Mechanism
1. The program opens the map online.
2. Search the inputted "srch" value on the map.
3. Looknig through restaurants that are relevent to the inputted "srch" value, the program finds any reviews from those restaurants that contain the word "menu1" or "menu2". The view more button on the review section will be pressed "sut" amount of times. As the "sut" value increase, there will be more reviews. 
4. The program will list all reviews related to your keyword and which restaurant eacch review is from. 

## Example
When I used parameter valued mentioned in the description, the results came out successfully.
<pre>
<code>
    Restaurant:  애정마라샹궈
    와 마라탕이랑 마라샹궈 우선 넘 맛나는데요!! 가지 튀김 꼭 드세요!!! 2번 3번 4번 드세요!!!!! 진짜 마라먹 고싶어서 방문했는데 가지튀김에 치이고 갑니...
    짜요짜요ᆢ가지튀김은 맛있게 먹었어요~^^
    덜짜게 해달랬는데 그래도 짜~~
    Restaurant:  상관양꼬치
    가지튀김 너무 맛있고 양꼬치도 맛있어요~~
    자주 방문했는데 리뷰는 첨 남기네용 항상 꿔바로우
    시켜먹는데 여긴 무조건 가지튀김 시켜요 메뉴에 시
    그니쳐라고 표시해도 될것 같아요 ^~^잘 먹고...
    Restaurant:  마라공방 성신여대점
    Restaurant:  마라삼국지
    Restaurant:  마라탕전문점 샹츠마라 성북구점
    없음
</code>
</pre>

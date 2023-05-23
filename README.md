# UNTERSEEBOOT
2015년 만든 3d 잠수함 횡스크롤 게임입니다<br>


https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/43b05ee1-efb7-42ff-a084-6505eca76f8d

 

# 게임 개요
## 장르
횡 스크롤 액션 게임<br>
## 플랫폼
모바일(Android)<br>
## 컨셉
잠수함을 통해 여러 임무를 진행하는 게임<br>
## 게임 특징
3D로 제작된 함선들을 사용하여 잠수함을 이용한 해전의 퀼리티를 높임<br>


# 플레이 화면
## 컨셉 이미지	 
 ![그림1](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/3a24cfe6-e459-4059-93c9-8a7fba005c36)<br>
## 플레이 화면의 UI구성도(임시, 하단의 직접적인 플레이용 UI만 완성)
 ![그림2](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/ab3faf52-0f64-4acd-be5d-075a1ad3ac2f)<br>
## 자세한 것은 시스템에서 설명


 

# 이동
버튼 구조	 
![그림3](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/fb62b6eb-0255-4263-97e7-a214f3fff434)<br>
## 이동관련 각 버튼 설명
전진 / 후진
![그림4](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/d4de4c44-6b63-4560-b798-f7bf04e7695d)<br>
![그림5](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/bc58c318-7ac5-425b-ac56-0da952d92161)<br>
## 파란 상자: 현재 기어가 들어가 있는 위치
시작시 기본적으로 기어는 정지 상태에 위치해 있으며, 출력버튼을 사용하여 기어의 위치 및 잠수함의 속력을 조절할 수 있다.<br>
기어는 출력버튼을 한번 누를때마다 위치가 이동하며, 여러번 터치하여 빠르게 기어의 위치를 바꿀 수 있다.<br>
![그림6](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/33aab2d8-044d-451b-86b7-83832b7efb4a)<br>
![그림7](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/75a2e56d-ae30-411f-b1a7-31d63cd400ee)<br>
출력UP버튼을 눌러 저속 이상의 출력에 기어가 올라가면 잠수함이 앞으로 전진한다.<br>
잠수함이 출력DOWN버튼을 눌러 후진에 기어가 위치하게 되면 잠수함이 뒤로 후진한다.<br>
![그림8](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/543e613d-9f6d-4968-bdf1-56676af12299)<br>
 각 기어의 출력 비율(사용 잠수함의 최대 출력을 기준으로)<br>

좌우 회전
![그림9](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/2298da64-509d-4d50-bdf4-0f29782b77c1)<br>
방향 조절을 위한 키(모양의 뭔가)가 있으며, 플레이 시 기본적으로 오른쪽에 위치해 있다.<br>
배가 바라보는 방향을 바꾸는 일종의 조타 버튼으로 왼쪽과 오른쪽으로 방향이 나뉜다.<br>
플레이어가 조타 버튼을 중앙 기준으로 왼쪽을 향하게 하면 그 후 키 버튼을 놓아도 가장 왼쪽으로 조타 버튼의 기어가 이동하게 된다. (단, 정지상태에서는 불가능 하며 전진 시 사용 가능)<br>
잠수 / 부상	 
![그림10](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/f0013750-4fda-40b5-9b1e-59205a0c3c24)<br>
심도 조정 버튼은 3단으로 나뉘어 있으며, 각각 위와 같은 역할을 가지고 있다.<br>
  ![그림11](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/d2852f21-86c5-454b-a922-135ad3a7a53e)<br>
 ![그림12](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/23361470-1ced-4783-91df-f4331ee92e82)<br>
![그림13](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/b0c973f6-b6d5-4be8-a81a-d1e54ceebe38)<br>
![그림14](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/21ba774b-f591-4009-89f1-70351d52d79c)<br>

(잠수함이 정지된 상태에서)심도 조정 버튼을 위로 향하게 하면 잠수함이 수직으로 상승하고, 아래로 향하게 하면 수직으로 하강하게 된다.(단, 잠수함은 수면 이상으로 상승하지 못한다.)<br>
  
잠수함을 전진 시키며 부상이나 잠수를 시킬 경우 위와 같이 잠수함이 그 방향으로 약간 경사를 지며 비스듬히 이동하게 된다.<br>
# 상태 창
## UI 구조	 
![그림15](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/79087348-7f91-476c-bb89-d7508479a08f)<br>
## 상태창의 구조 및 구성
 ![그림16](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/1652f613-6b19-4565-b1f3-66fcc5065784)<br>

상태 창의 특수 기능 및 아이템 사용 버튼은 기본적으로 UI에 보이지 않지만 상태 창을 클릭 시, 모든 상태 창들이 올라가며 특수 기능 및 아이템 사용 버튼이 위로 올라오며 기존의 상태 창들은 위로 밀려 올라가게 된다. 반대로 특수 기능(중략) 버튼이 위로 올라간 상태에서 터치하게 되면 상태 창 전체가 아래로 내려가게 된다.<br>
속력과 심도 계기판은 기본적으로 0에서 시작함으로 바늘이 왼쪽에서부터 오른쪽으로 이동하지만, 체력 및 잔여 산소량 계기판은 100%에서부터 시작함으로 바늘이 오른쪽에서부터 왼쪽으로 이동하는 방식을 가진다.<br>
 ![그림17](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/46874bb4-3045-4789-9056-c57149888692)<br>
  ![그림18](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/2995d50e-0f39-42fd-9c58-ef28147ad17e)<br>

## 상태이상 알림 창 구성 및 점등됐을 때 예시
이 게임 내에 들어 있는 3가지 상태이상을 나타내며, 각각의 문제 발생 시 상태이상 창이 점등된다. 반대로 문제를 해결했을 시 점등된 상태이상 창이 꺼지게 된다.<br>
각 상태이상 알림 창에는 각각의 이니셜이 있으며, 점등되지 않은 상태에서는 흐릿하지만 점등이 되면 하얀색의 이니셜 라인이 선명이 보이게 된다.<br>
 ![그림19](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/f117eb16-5d90-474d-93d8-ad8bec24d10f)<br>
# 무기 버튼
## UI 구조	  
![그림20](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/09b92e3b-7a98-4464-9331-f5f15722b49f)<br>
## 무기 버튼의 기본 구조 및 무기 발사 버튼 클릭 시 무기(어뢰)가 발사되는 모습 예시

## 무기 발사와 관련된 내용은 이후 좀더 자세히 설명할 것임
  
기본적으로 무기 변경 버튼은 사용할 무기를 클릭하면 변경한 무기로 바뀌지만, 수중에서는 사용이 불가능한 무기의 경우(ex: 함포) 수중에 들어갈 시 회색으로 무기 버튼이 잠기게 된다.<br>
이런 사용 불가능한 무기는 수면 등 사용이 가능한 곳으로 함이 이동하면 자동으로 무기의 잠금이 풀리게 된다.<br>
 ![그림21](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/7b7e1a9b-dc3e-44d6-8c27-1e4eb90098c5)<br>
![그림22](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/38661956-c7e5-4bdc-bcbc-c677e789c2b9)<br>
![그림23](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/f144daf0-205b-42f4-b3fa-c697cc054873)<br>
## 무기 탄약이 부족할 시 나오는 무기 사용 불가능 효과
무기의 사용이 위치가 아니고 탄약의 유무로 인해서 불가능이 되는 경우에는 이처럼 각 무기의 탄약이 0이라는 효과가 무기 버튼에 나오게 된다. 이 효과 또한 탄약을(보급 할 수 있으면) 재 보급 할 시 풀리게 된다.<br>
 
 

# 각 함 비교
크기 비교	 
![그림24](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/b1787fc0-27a4-4316-a9d2-a67d060d5ca8)<br>
## 대략적인 각 함들의 크기 비교
## 속력 비교	 
![그림25](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/fdf758e0-0985-4a9c-b7c1-6bd9e8625503)<br>
## 잠수함의 파란색 부분은 잠수 시 속력
## (전함의 이동속도가 없는 이유는 전함은 한 지역에 고정시켜 이동하지 않을 것이기 때문)
체력 비교	 
![그림26](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/5d19c78d-9b5a-4723-a4e1-de549a27d596)<br>

방어력 비교	 
![그림27](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/0cab03ea-2ca1-4c6e-a48b-f8e5cb1ad756)<br>

 
# 잠수함
이미지		
 ![그림28](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/456e401f-b1fa-4c23-a1c6-37f5fd9cba17)<br>
## 잠수함 3D 모델링(임시)
체력	보통<br>
속력	느림<br>
탑재 무기	(기본) 선수 77mm 함포 / 어뢰 발사관 2문(어뢰 종류 미정) / 대공포 / 기뢰(시스템 상 미정)<br>
기능	10m잠항시 10m이내는 잠망경이 내려오는 자동 기능 설명<br>
 
# 3)	구축함
## 컨셉 이미지		
 ![그림29](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/a96b2274-389f-451d-817f-edfd3218d7f6)<br>

## 구축함 3D 모델링(임시)
체력	낮음<br>
속력	매우 빠름<br>
탑재 무기	5인치 이연장 포 5문(선수 2문, 선미 3문탑재), 폭뢰 및 폭뢰 투사기 1문~2문(미정)<br>

 
 

# 어뢰
## 컨셉 이미지		
 ![그림30](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/2cf00995-1b62-4c56-a8bf-b8b97eb9850c)<br>

## 기본 어뢰 3D 모델링 (임시)
장비 함선	잠수함<br>
공격력	매우 높음<br>
공격 방식	<br>

# 폭뢰/폭뢰 투사기
## 컨셉 이미지	
  ![그림31](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/c6015054-34fd-4fc1-a361-5f490b381849)<br>
![그림32](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/79732bbc-e796-4a93-a94d-1be0da15d866)<br>
## 폭뢰 및 폭뢰 투사기 3D 모델링 
장비 함선	구축함<br>
공격력	높음<br>
공격 방식	<br>
 
# 5인치 이연장 함포
## 컨셉 이미지	
  ![그림33](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/8b264669-eae9-4cd3-ab99-8be95c923a0b)<br>
![그림34](https://github.com/ChartaP/UNTERSEEBOOT/assets/20767587/fc04d6de-70d6-4ed6-8766-6a5a2cf935ad)<br>
## 5인치 이연장 함포 및 포탄 3D 모델링
장비 함선	구축함<br>
공격력	높음<br>
공격 방식	<br>
 


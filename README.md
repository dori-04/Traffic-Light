친구 기말과제 심심해서 만들어 봄 

언어: 프로세싱

setup() 함수에서 noCursor()를 호출하여 기본 마우스 포인터를 숨깁니다. -> 자동차로 대체합니다.
draw() 함수에서 배경, 도로, 횡단보도, 신호등, 그리고 자동차를 그립니다.
drawRoad() 함수는 화면 중앙에 수직 도로를 그립니다.
drawCrosswalk() 함수는 화면 중앙에 횡단보도를 가로로 그립니다. -> 이때 stroke함수로 인해서 신호등과 자동차에도 영향이 갔는데, 횡단보도를 그린 뒤에 noStroke를 사용하여 해결합니다. 
drawTrafficLight() 함수는 오른쪽 상단에 신호등을 그립니다.
drawCar() 함수는 주어진 위치에 자동차를 그리며, 자동차가 도로 내에 위치하도록 제한합니다.
draw() 함수에서 도로 중심(x 좌표 200)과 마우스 위치 간의 거리를 계산하고, 거리에 따라 신호등의 상태를 변경합니다.


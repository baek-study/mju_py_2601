# 파이썬 프로그래밍 입문 - 화 10:00
자연 교양 학생 대상 파이썬 입문 수업시간의 요약 및 코드 배포를 위한 학습 공간입니다. 
<hr size = "10px", width ="500px">


## [📋4주차 강의&nbsp;-&nbsp;리스트]()

### [🔹 리스트 기본 구조]()
<ul>
<li> 여러 데이터를 하나로 묶어 순번에 따라 저장  </li>   
<li> temps=[28, 31, 33, 35, 27] # 대괄호사용 </li>
<li> 양의 인덱스: 첫요소부터 0부터 시작 </li>
<li> 음의 인덱스: 끝요소부터 0-1터 시작 </li>
</ul>

### [🔹 리스트 인덱싱&슬라이싱]()
<ul>
<li>인덱싱: temps[3], temps[-1]  </li>
<li>슬라이싱: temps[2:5]  &ensp;#시작에서 끝-1 까지 </li>
<li>수정1: temps[3] = 5 &ensp;# 인덱싱 이용한 수정 </li>  
<li>수정2:  temps[2:5] = [1, 2] &ensp;# 슬라이딩 이용힌 수정 </li>    
<li>단순할당 : list1 = temps &ensp;# 같은것 가리킴</li>  
<li>복사 : list2 = list(temps) &ensp;# temps[:] 새로운 리스트 </li>  
</ul>

### [🔹 리스트 연산&메소드]()
<ul>
 <li> 연산 (+, *, in, == )<br>
   - 결합 : [1,2]+[3,4,5] <br>
   - 반복 : [1,2]*3 <br>
   - 멤버쉽 1 in [1,2]  &ensp;# not in<br>
     </li> 
  <li> 추가 : temps.append(5)  </li>  
  <li> 삽입 : temps.insert(1, 100)   </li>  
  <li> 삭제 : temps.remove(100)   </li>  
  <li> 삭제 : t = temps.pop(0)   </li>  
  <li> 검색 : temps.index(31) </li>
</ul>
<br>

## [🐍1주차 강의 &nbsp;-&nbsp; 파이썬 소개 및 첫걸음](https://github.com/baek-study/mju_py_2601/blob/main/source/week1_mju.ipynb)

### [🔹 파이썬 소개](https://github.com/baek-study/mju_py_2601/blob/main/source/week1_mju.ipynb)
<ul>
<li><b>특징:</b> 인터프리터 언어, 객체지향 언어 </li>
<li><b>통합 개발 환경:</b> IDLE, Colab, Jupyter Notebook 등 </li>  
</ul>

### [🔹 실습 환경 세팅 (Google Colab)](https://github.com/baek-study/mju_py_2601/blob/main/source/week1_mju.ipynb)
<ul>
<li>구글 코랩(Colab): 웹 브라우저 바로 코드를 작성하고 실행 </li>
<li>구글 드라이브와 연동되어 실습 파일(사본) 자동 저장</li>  
</ul>

### [🔹 실습 파일 및 배포 코드](https://github.com/baek-study/mju_py_2601/blob/main/source/week1_mju.ipynb)
<ul>
<li>1주차 실습: "hello world" 출력 (수업 후 배포)  </li>
</ul>

<br>

## [📦2주차 강의&nbsp;-&nbsp;변수와 자료형](https://github.com/baek-study/mju_py_2601/blob/main/source/week2_exam.ipynb)

### [🔹 변수(variable)](https://github.com/baek-study/mju_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
  <li><b>변수</b> : 데이터를 저장하는 공간 </li>
  <li>이름 규칙 : 알파벳, 숫자, 밑줄(_)로 구성 <br>
  - 시작시 숫자 안됨, 공백/예약어 안됨 </li>
   <li><b>변수이름 = 값</b> <br>
     ex) x = 100 &ensp; #변수이름은 왼쪽
    </li> 
</ul>

### [🔹 자료형(Data Type)](https://github.com/baek-study/mju_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
  <li> 정수형(<b>int</b>): 123</li>
  <li> 실수형(<b>float</b>): 3.14</li>
  <li> 문자열(<b>str</b>): "hi", 'hi'</li>
  <li> 논리형(<b>bool</b>): True, False</li>
  <li> 자료형 확인 함수: <b>type</b>(1234) </li>
</ul>

### [🔹 표준출력함수 print()](https://github.com/baek-study/mju_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
    <li> 문자열 출력: print('hello') </li>
    <li> 다양한자료형: print(1004); print(3.14);</li>
    <li> 여러개 값: print(2, '+', 3)&ensp;#<b>콤마</b> 이용</li>
    <li> 출력제어문자: print('탭키 <b>\t</b> 줄바꿈 <b>\n</b> ')</li>
  </li>
</ul>

### [🔹 산술 연산자](https://github.com/baek-study/mju_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
  <li> + - * / (사칙연산) <br> 
  - 나눗셈 결과는 실수 &ensp; ex) 2/2 = 1.0 </li>
 <li> //(몫), %(나머지), **(제곱) <br>
  - 몫(정수)&ensp; <b>//</b> &ensp; ex) 5//3 = 1<br>
  - 나머지&ensp; <b>%</b> &ensp; ex) 5%3 = 2</li>
</ul>

<br>

## [🔄3주차 강의&nbsp;-&nbsp;입력과 형변환]()

### [🔹 표준 입력함수 input()&형변환]()
<ul>
   <li>키보드를 통해 입력한 값을 '문자열'로 반환</li>
    <li> msg = input('안내메시지')&ensp;#문자열로 반환</li>
    <li> age = int(msg)&ensp;#정수변환</li>
    <li> fage = float(msg)&ensp;#실수변환</li>
</ul>

### [🔹 대압/복합대입 연산자](h)
<ul>
  <li> x = 10 # 왼쪽 변수공간에 오른쪽 값 할당 </li>
  <li>다중 할당 : x=y=z=1 <br>
    -  x,y = 1, 2 # 여러 개 값을 각 변수에
  </li>
  <li>자기 할당 : x = x + 3  </li>
  <li>복합대입 : x += 3 &ensp;# x=x+3 <br>
  - 할당과 산술/기타 연산자 결합 
  </li>
</ul>

### [🔹 서식 : f-문자열]()
<ul>
  <li> f'..{표현식}..' # 중괄호 사용  <br>
    ex) print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li> 
</ul>
<br>

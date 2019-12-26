# 매운맛 C 언어 입문
환영합니다! 이 레포지토리에는 말 그대로 _매운맛_ 으로 C언어를 입문하고자 하는 분들을 위해 한땀한땀 적어낸 문서들이 모여있습니다. 여타 입문서와는 달리, 매우 원론적이고 빡센 내용들만을 담아내었으므로 각오하고 보지 않는 이상 쉽게 질려버릴 수 있습니다.

## 유의사항
매운맛 C는 단순히 제가 가진 지식을 공유할 뿐만이 아닌, 제가 공부하고자 하는 분야에 대한 복습의 의미로 진행하고 있는 프로젝트입니다. 만일 틀린 부분을 발견하셨을 경우 이슈트래커 등으로 지적하여주시면 감사하겠습니다.

## 목차
매운맛 C는 다음과 같이 구성됩니다. (변경될 수 있음!) 작성 완료된 챕터는 ![](https://img.shields.io/badge/status-complete-brightgreen) 로 표시되어 있습니다. 장기간 예상하고 천천히 작성될 예정이므로 양해 바랍니다.


 1. **컴퓨터 프로그램의 본질** ![](https://img.shields.io/badge/status-writing-red)
    
    앞으로 작성하게 될 C 소스코드와 프로그램이 실제 어떤 형태인지, 어떤 식으로 사용되는지 다룹니다. 컴파일러, 링커, 어셈블러에 대한 설명이 포함되어 있습니다.
    
 2. **기본 자료형** ![](https://img.shields.io/badge/status-writing-red)
 
    C언어가 기본으로 제공하는 자료형과 이들 간의 연산에 대해 알아봅니다. 자료형이 되도록 일치되어야 하는 이유, 그리고 signed, unsigned를 구별해야하는 이유에 대해 깊이있게 다뤄봅니다.

 3. **프로그램의 흐름 제어** ![](https://img.shields.io/badge/status-not%20started-lightgrey)
    
    원하는 방향으로 프로그램을 제어할 수 있는 몇가지 기능(if-else, for, while, do-while, goto)에 대해 다룹니다. 
    
 4. **배열, 구조체, 공용체** ![](https://img.shields.io/badge/status-not%20started-lightgrey)

    여러 기본 자료형들을 가지고 만들어 낼 수 있는 자료구조인 배열, 구조체, 공용체에 대해 알아봅니다. 또한 기본 자료형의 연산과는 어떻게 다른지, 자료형(Type)에 대해서도 알아봅니다.

 5. **포인터와 기초 어셈블리** ![](https://img.shields.io/badge/status-not%20started-lightgrey)

    주소를 담는 포인터와 이후 내용의 이해에 필요한 기초 x86-64 어셈블리 언어에 대해 알아봅니다.

 6. **서브루틴과 함수** ![](https://img.shields.io/badge/status-not%20started-lightgrey)

    C언어에서 프로그램 모듈화의 핵심을 담당하는 서브루틴과 함수에 대해 알아봅니다.
   
 7. **동적 할당과 메모리 구조** ![](https://img.shields.io/badge/status-not%20started-lightgrey)
   
    프로그램에서 메모리를 요청하고 반환하는 과정에 대해 알아봅니다. 또한 프로그램 전체 실행주기에서 어느 부분에 어떤 메모리가 할당되는지 자세하게 알아봅니다.
   
 8. **문자열 처리** ![](https://img.shields.io/badge/status-not%20started-lightgrey)
 
    C언어에서 문자열 처리가 어떻게 이루어지는지 알아봅니다.
 
 9. **전처리기** ![](https://img.shields.io/badge/status-not%20started-lightgrey)

    #include, #define 등 컴파일 과정에서 일어나는 전처리과정에 대해 알아봅니다.
   
 9. **라이브러리**   ![](https://img.shields.io/badge/status-not%20started-lightgrey)
 
    다른 라이브러리에서 기능을 가져오는 방법에 대해(정적 링크, 동적 링크) 자세히 알아봅니다.
 
 9. **테스팅** ![](https://img.shields.io/badge/status-not%20started-lightgrey)
 
    프로그램의 신뢰성을 향상하기 위해 필요한 과정인 테스팅에 대해 간단하게 알아봅니다.

**Appendix A. 언어 표준에 관하여** ![](https://img.shields.io/badge/status-not%20started-lightgrey)

ANSI-C, C11 등 C언어의 표준이 어떻게 변해왔는지, 그리고 왜 표준을 지켜야 하는지와 UB(Undefined Behavior)에 대해 알아봅니다.
  

### Special Thanks

일부 단원 구성은 식질머신 제작자이신 [kur-creative님의 블로그](https://blog.naver.com/rhdnfka94/221031332013)를 참조하였습니다.

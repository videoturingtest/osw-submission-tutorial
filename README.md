# Open Software Submission Tutorial

아래 순서대로 VTT 오픈소스를 공개한다.

## 1. 자신의 저장소에 오픈소스 공개하기

공개한 오픈소스를 원하는 계정의 GitHub 저장소(repository)에 공개한다. 

오픈소스를 잘 이용할 수 있도록 충분히 문서화한다. 메인테이너는 각 모듈에 대한 문서를 작성한다. 기본적으로 `README.md`, `LICENSE`를 포함해야하며 문서별 내용은 다음과 같다. 

### 1.1. 오픈소스 사용법 문서화

__README.md__
* Overview: 공개SW에 대한 개괄적 설명
* Install: 공개SW 사용 설치 방법
* How to use: 공개SW 사용 방법
* Contact us: 공개SW에 대한 문의를 받을 연락처
* 그 외에 추가적으로 내용을 넣을 수 있다
  * 예시: SNU Parallax (https://github.com/snuspl/parallax/blob/master/README.md )

### 1.2. 소프트웨어 라이선스 문서화

__LICENSE__
* 오픈소스의 사용권 계약사항을 명시한 문서이다. 일반적으로 라이선스를 정하면 이 문서를 자동으로 생성할 수 있다.
* 저장소를 만들 때, 라이선스를 선택하면 파일 저장소 상위 디렉토리에 `LICENSE` 파일이 자동으로 생성된다.
* 저장소를 공개 후 라이선스를 공개했다면, 아래와 같은 방법으로 `LICENSE` 파일을 추가한다.
  * [GitHub repository에 라이선스 파일을 추가하는 방법](https://help.github.com/articles/adding-a-license-to-a-repository/)

## 2. 라이선스 검증 진행

VIC에서 공개SW 담당자가 공개 저장소의 라이선스를 검증한다.  통과하지 못하면, VIC가 검증 결과를 해당 공개SW 메인테이너에게 전달하고, 각 메인테이너는 참여기관 LsWare(신동명 박사; roland@lsware.com)에게 자문을 구하여 라이선스를 수정하거나 코드를 수정하여 라이선스 검증을 통과한다. 

## 3. 공개한 저장소를 VIC organization 계정으로 fork하기

라이선스 검증을 통과한 저장소를 [VIC organization 계정](https://github.com/videoturingtest)으로 fork한다. fork하기 위해서는 VIC의 멤버가 되어야 한다. 자세한 방법은 아래 문서를 참고한다.

[VTT 오픈소스 성과물 제출 방법](osw-submission-tutorial.md)

라이선스 검증 리포트를 해당 저장소에 파일 형태로 추가한다.

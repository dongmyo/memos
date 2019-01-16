## What's New in Effective Java's Third Edition?
* https://dzone.com/articles/whats-new-in-effective-javas-third-edition

### Item 1 - 생성자 대신 정적 팩토리 메쏘드
* java 8에서 지원되는 interface static method 얘기가 추가됨

### Item 5 - 자원 직접 명시 대신 의존성 주입 사용
* java 새 버전 기능과 무관하게 2판에 없던 내용이 추가된 항목

### Item 6 - 불필요한 객체 생성은 no no
* String 인자 하나만 받는 Boolean 생성자가 java 9에서는 deprecated 되었다고 언급됨
* boolean 인자 하나만 받는 Boolean 생성자도 java 9에서 deprecated 됨
* java 9에서는 Boolean 객체는 생성자 못 씀

### Item 8 - finalizer와 cleaner 쓰지마
* java 7에서 도입된 AutoClosable 얘기가 추가됨
* java 9에서 finalizer가 deprecated되고 Cleaner가 도입되어서
  제목이 `finalizer 쓰지마`에서 `finalizer와 cleaner 쓰지마`로 바뀜

### Item 9 - try-with-resources
* java 7에서 도입된 try-with-resources 내용 (새로 추가됨)

### Item 15 - 클래스와 멤버의 접근 권한을 최소화
* java 9에서 모듈 시스템이 도입되면서 두 가지 암묵적인 접근 수준이 추가되었음을 언급함

### Item 19 - 상속 고려 설계, 문서화. 아니면 상속 금지
* java 8에 처음 도입되어 java 9부터 본격적으로 사용되기 시작한 javadoc의 @implSpec 태그 관련 내용 추가됨

### Item 21 - 인터페이스는 구현하는 쪽을 생각해서 설계하라
* java interface의 default method와 관련된 best practice에 대한 내용을 다룸

### Item 25 - 톱 레벨 클래스는 한 파일에 하나만
* java 새 버전 기능과 무관하게 2판에 없던 내용이 추가된 항목

### Item 32 - 제네릭과 가변인수를 함께 쓸 때는 신중하라
* 2판에 없던 내용으로 java 7에 추가된 @SafeVarargs 내용이 나옴

### Item 42 ~ 48 (Chapter 7 Lambda 와 Stream)
* java 8에 도입된 람다와 스트림에 대한 내용이 추가됨

### Item 49 - 매개변수가 유효한지 검사하라
* java 7에 추가된 Objects.requireNonNull() 메쏘드 소개가 추가됨

### Item 50 - make defensive copies when needed
* java 8에서 Date 대신 Instant를 사용하는 것에 대한 내용이 나옴

### Item 55 - 옵서녈 반환은 신중히 하라
* java 8에 도입된 Optional에 대한 적절한 사용에 대한 논의가 추가됨

### Item 56 - 공개된 API에는 항상 문서화 주석을 작성하라
* java 7에서 javadoc에 추가된 -xdoclint 커맨드라인 스위치에 대한 소개가 추가됨
* javadoc의 @implSpec 태그 사용에 대한 논의가 추가됨
* java 9에 도입된 javadoc의 @index 태그에 대한 논의가 추가됨

### Item 59 - 라이브러리를 익히고 사용하라
* java 9에 추가된 InputStream.transferTo(OutputStream) 메쏘드에 대한 논의가 추가됨

### Item 80 - 쓰레드보다는 실행자, 태스크, 스트림
* 제목에 스트림이 추가됨
* java 7에서 executor framework에 추가된 Fork/Join 내용이 추가됨

### Item 85 - 자바 직렬화 쓰지마
* java 새 버전 기능과 무관하게 2판에 없던 내용이 추가된 항목

# project
// < ebook을 대출하는 프로그램 >

/* 시스템 요구사항 */
/* 1. 사람 : 책 고르기, 책 대출하기, 책 반납하기, 신상정보 기입하기(대출)
* 2. ebook 프로그램 : 책 대출하기, 반납하기, 신상정보 확인하기(반납)

* 이미 대출한 책은 대출할 수 없다.
* 대출하지 않은 책은 반납할 수 없다.
* 대출할 때 이름과 전화번호 뒷자리를 받고 저장한다.
* 반납할 때 정보를 입력하고 정보가 맞으면 반납이 되고 정보는 삭제한다.
* 프로그램이 종료되면 모두 초기화된다.*/

/* 필요한 객체 */
//사람, ebook 프로그램

/* 상호작용 */

// 사람이 수신할 수 있는 메세지(사람이 해야하는 일)
/* 1. 대출하기
 * 2. 반납하기
   3. 신상정보 기입하기*/
  
// ebook 프로그램이 수신할 수 있는 메세지(ebook 프로그램이 해야하는 일)
/* 1. 대출하기
 * 2. 반납하기
   3. 신상정보 저장하기 */

/* 클래스 설계하기 */

// 1. 사람 클래스 생성
/* 속성 : 사람
   행위 : 책고르기, 대출하기, 책 반납하기, 신상정보 기입*/



// 2. Ebook 프로그램 클래스 생성
/* 속성 : ebook 프로그램
   행위 : 대출하기, 책 반납하기, 신상정보 저장하기*/

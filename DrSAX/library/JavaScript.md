1. 함수의 속성은 this, 객체의 속성은 객체이름으로,
2. 생성자 함수는 객체라고 생각해야한다.
3. 함수의 속성은 new를 통한 생성자 함수를 통해 접근 가능--매우중요
(프로토타입 추가는 변수이름으로;객체에 추가는 변수.속성,)
4. var o = {'func':function(){
    alert('Hello?');
}

}
o.func();

객체의 매소드 접근가능 
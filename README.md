# ReactJS로 영화 웹 서비스 만들기🎬

## 1. [2021 UPDATE] INTRODUCTION

> React를 배워야 하는 이유 및 필요한 도구들에 대해 소개

## 2. [2021 UPDATE] THE BASICS OF REACT

> 바닐라 JS를 통한 버튼 카운터 만들기
> React.JS로 동일 기능 구현해보기
>
> > React.JS는 Javascript를 통해 element를 제어 할 수 있다.

> React.createElement(tagName, attribute, content)를 통해 React 태그를 만들 수 있다.

> ReactDom.render(React태그, root)를 통해 id="root" 태그 하위에 생성된 React태그를 위치 할 수 있다.

> React.createElement(tagName, attribute, [childReactTagNames...])를 위하여 tagName 하위로 자식 태그들을 위치 할 수 있다.

> JSX는 기본적인 html 코드와 비슷하면서도 React의 기능을 사용 할 수 있다.

> Babel은 JSX로 적은 코드를 브라우저가 이해 할 수 있는 형태로 바꿔주는 역할을 한다.

> function fnName() {return} = fnName = () => {}

> Component의 첫글자는 대문자여야한다.(소문자일 경우 html의 태그라고 생각함.)

> Component안에 다른 컴포넌트를 넣기 위해서는 자식 Component를 함수로써 선언하고, 부모 함수부분에서 자식 Component를 호출한다.<br/>

```javascript
const root = document.getElementById('root');
const Button = () => {
  <button>Click me</button>;
};
const Container = () => {
  <div>
    <Button />
  </div>;
};
ReactDom.render(<Container />, root);
```

## 3. [2021 UPDATE] STATE

## 4. [2021 UPDATE] PROPS

## 5. [2021 UPDATE] CREATE REACT APP

## 6. [2021 UPDATE] EFFECTS

## 7. [2021 UPDATE] PRACTICE MOVIE APP

## 8. INTRODUCTION

## 9. SETUP

## 10. JSX & PROPS

## 11. STATE

## 12. MAKING THE MOVIE APP

## 13. CONCLUSIONS

## 14. ROUTING BONUS

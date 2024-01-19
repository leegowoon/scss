# #Partials(파샬-부분적인)
- 소스에 반복되는 부분들을 분산시켜서 모듈화시키는 기능(관련된 것끼리 묶어서 분리, 분산하는것)
- 파샬 파일명은 _(언더바)로 시작하며(_파일명.scss)
- 파샬파일을 불러올 때는 @import '파일명' (_,확장명없이) 경로는 상대경로를 사용한다.

# #scss는 _로 시작하는 파일은 컴파일하지 않는다.

# #변수의 중복을 막을 수 있는 방법 -- @use, @forward
- @use --> 많이 사용
- 구분하는 방법
```
@use "./partials/var";
@use "./partials/var2";

h1{color:$color-primary} //나중에 불러온 변수가 적용됨
```

# #as를 이용하여 별명을 붙일 수 있다.   
![image](https://github.com/leegowoon/scss/assets/145514701/2a5b431b-8655-4886-9881-5b6ec25270ca)


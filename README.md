# React-webpack2-skeleton for goorm
- 본 프로젝트는 구름 IDE에서 react를 실행하는 예제입니다.
- [velopert/react-webpack2-skeleton](https://github.com/velopert/react-webpack2-skeleton)의 light branch을 시작으로 만들어졌으며  
본래 README는 [ORIGINAL_README](ORIGINAL_README.md)으로 옮겨졌습니다.


## 실행방법
1. `프로젝트 > 실행 URL과 포트`에서 원하는 url를 입력하고 port에 3000을 입력 후 적용을 눌러 실행 url을 만들어줍니다. (실행용)

2. git clone
```bash
$ git clone https://github.com/minungHan/react-webpack2-skeleton.git
```
3. npm install
```bash
$ npm install
```
4. devServer를 실행합니다.
```bash
$ npm start
```
5. 만들어 놓은 url으로 접속합니다.

## 참고

- 구름 IDE에서 사용하기 위해 다음과 같이 devServer가 수정되었습니다.
```
devServer: {
    contentBase: paths.context,
    host: '0.0.0.0',
    port: 3000,
    disableHostCheck: true
},
```
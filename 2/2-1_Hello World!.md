영후

스크립트 태그 안에는 자바스크립트 코드가 들어간다 . 브라우저가 이태그 를 만나면 안의 코드를 자동을 처리한다.

자바스크립트 코드의 양이 많은 경우엔 파일로 소분하여 저장할 수 있다.

```js
<script src="/path/to/script.js"></script>
```
여기서 /path/to/script.js는 사이트의 루트에서부터 파일이 위치한 절대 경로를 나타냅니다. 현재 페이지에서의 상대 경로를 사용하는 것도 가능합니다. 같은 폴더 내에 있는 파일인 "script.js"를 src="script.js"로 참조하는 것처럼 말이죠.

위에서 절대 경로로 표현하였는데 상대 경로는 현재 페이지에서의 상대 경로를 사용한다.

그래서 전부 절대 경로로 표현 하면 안되는지 의문이든다. 그럼 헷갈릴 일 도 없는데 ..

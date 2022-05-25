1. md파일로 포스팅한다.

2. hunBlog 폴더에서 cli커맨드

```js
hugo -t PaperMod
```

를 입력한다. 입력 하면 public폴더가 업데이트 될 것이다.

3. public폴더는 실질적인 배포된 정적 페이지이므로, github submodule로 등록돼있다. 따라서, 업데이트 된 파일을 commit후 push까지 해주면, https://findmytrueself.github.io/ 로 자동배포가 될 것이다.

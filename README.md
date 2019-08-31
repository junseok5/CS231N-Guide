# CS231N-Guide
CS231N preparation guide.

### References

- [홈](http://cs231n.stanford.edu/)
- [강의](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)
- [강의 번역 블로그 1-5](https://cding.tistory.com/category/%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5/%EB%88%84%EA%B5%AC%EB%82%98%20%EC%9D%B4%ED%95%B4%ED%95%A0%20%EC%88%98%20%EC%9E%88%EB%8A%94%20%EB%94%A5%EB%9F%AC%EB%8B%9D%28cs231n%29)
- [슬라이드](http://cs231n.stanford.edu/syllabus.html)
- [참고](http://cs231n.github.io/)
- [Numpy Tutorial - 영어](http://cs231n.github.io/python-numpy-tutorial/)
- [Numpy Tutorial - 번역](http://aikorea.org/cs231n/python-numpy-tutorial/)
- [Numpy Reference](https://docs.scipy.org/doc/numpy/reference/index.html)
- [벡터와 행렬의 연산](https://datascienceschool.net/view-notebook/3f44cfdda2874080a9aa6b034c71d5ec/)
- [벡터와 행렬의 연산 - 조대협 블로그](https://bcho.tistory.com/1153)

### Memo

- 행렬의 연산을 할 때 행렬의 크기가 매우 커질 경우, for문을 통한 연산은 매우 느려질 수 있다. 브로드캐스팅을 사용하면 코드를 간결하고 빠르게 해준다.

- 벡터 x, 행렬 w의 곱에서 shape가 달라서 shape를 바꿔주어 연산해주어야 할 때, 벡터의 shape를 바꾸는 경우 x.T(전치행렬) 사용, 행렬의 shape를 바꾸는 경우 np.reshape 

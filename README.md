라벨링 규칙
---
1. **글자가 짤리지 않는게 최우선 !!!** (불가능하다고 생각하면 그냥 스킵)
2. 너무 멀어서 안보이면 #으로 적어두기. 잘린애도 잘린부분 제외하고 진행....ㅠ
3. 사각형(점 네개만, 꼭 직사각형일 필요는 없으나, 이에 가까울 수록 좋음)
4. 다른 글자, 경계선에 겹치지 않도록( 글자에 딱 맞춰져 있을 수록 더 좋음, 아래 예시 이미지들 참고)
5. 많이 하는 것보다 정확하게 하는게 더 중요. 영어 철자 확인 필수
6. 글자 단위가 아니라 단어 단위로 박스를 치고, 라벨은 최대한 이미지에 적힌대로 따라간다. (화살표가 들어가있는 숫자는 안해도 무관)
![image](https://github.com/ili0820/a/assets/65278309/d712936d-9984-46a0-9819-cb640733f80b)
여기서 한글은 라벨을 "덕정로138번길" 로 하고 영어는 "Deokjeong-ro 138beon-gil"로 적는다.
7. 잘리거나 가려진 부분은 하지말고 한글/영어/숫자 만 라벨링
![image](https://github.com/ili0820/a/assets/65278309/93ee3815-0550-40cf-8a67-e1f59fa192b9)
위의 Stn은 하지 않는다.
8. 해상도 등의 이유로 문자를 정확히 식별이 불가능 할때는 라벨링을 하지 않는다.(다만 단어의 한글자와 같이 검색, 혹은 이전 라벨링을 통해 정확히 유추가 가능하다면 라벨링을 진행한다.)
![image](https://github.com/ili0820/a/assets/65278309/1fda011b-0b3f-42fe-829f-da53bbd2daf4)
영어단어의 형체를 알아 보기 힘드므로 라벨링을 진행하지 않는다.
9. 라벨링을 진행한 내용 이외의 것들은 모두 삭제<br>
![image](https://github.com/ili0820/a/assets/65278309/14dcf91a-e7b1-4ffd-a5f7-cf59a8fcf8ce)<br>
료(ra), 9051,2499,TnET와 같은 잘못 표시된 사각형들과 라벨은 모두 지운다.<br>
![image](https://github.com/ili0820/a/assets/65278309/a5f7a0b6-4cf9-433f-b36c-5661fa699426)



https://devocean.sk.com/blog/techBoardDetail.do?ID=164615
```python
conda config --add channels conda-forge
conda config --set channel_priority strict
conda config --remove channels defaults
conda config --show channels

```

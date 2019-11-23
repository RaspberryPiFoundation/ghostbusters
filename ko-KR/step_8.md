## 타이머 추가하기

이제 플레이어가 유령을 잡을 수 있는 시간을 10초로 제한하도록 타이머를 추가할 것입니다.

\--- task \---

'시간'이라는 새 변수를 추가합니다.

\--- /task \---

\--- task \---

무대에 타이머를 추가해서 플레이어가 10초 동안만 유령을 잡게 만들 수 있나요?

타이머는 이렇게 동작해야 해요.

+ 10초부터 시작합니다.
+ 매 초 숫자가 줄어듭니다.

타이머가 0이 되면 게임이 끝나야 합니다.

\--- hints \--- \--- hint \---`녹색 깃발이 클릭되면`{:class=”block3events”}, `시간`{:class=”block3variables”} 변수를 `10으로 정하기`{:class=”block3variables"}로 초기화합니다. 그 후 매 초마다 `-1만큼 바꾸기`{:class="block3variables"}로 `0이 되기 전까지`{:class="block3control"}까지 값을 줄여 나갑니다. \--- /hint \--- \--- hint \--- 사용할 수 있는 코드 블럭을 살펴보겠습니다: ![유령 스프라이트](images/ghost-backdrop.png)

```blocks3
정지 [all]

< [ ] = [ ] >

[time v] 를 [10] 로 정하기

[time v] 를 (-1) 만큼 바꾸기

(time)

(1) 초 기다리기

반복하기 < >
끝

flag 클릭했을 때

```

\--- /hint \--- \--- hint \--- 다음은 추가해야 할 코드입니다.![백드롭 아이콘](images/ghost-backdrop.png)

```blocks3
flag 클릭했을 때
[time v] 를 [10] 로 정하기
< (time) = [0] > 까지 반복하기
(1) 초 기다리기
[time v] 를 (-1) 만큼 바꾸기
끝
정지 [all]
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

여러분이 만든 게임을 친구에게 해 보라고 말해 보세요. 친구의 점수는 몇 점인가요?

\--- /task \---

만약 게임이 너무 쉽다면, 다음을 고려해 난이도를 바꾸어 볼 수 있습니다.

+ 플레이 시간을 줄여 보세요.
+ 유령이 나타나는 회수를 줄여 보세요.
+ 유령의 크기를 줄여 보세요.

\--- task \---

게임의 난이도가 적절하다고 느껴질 때까지 게임을 바꿔 보세요.

\--- /task \---
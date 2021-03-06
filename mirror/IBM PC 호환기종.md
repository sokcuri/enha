  * [컴퓨터 관련 정보](%EC%BB%B4%ED%93%A8%ED%84%B0%20%EA%B4%80%EB%A0%A8%20%EC%A0%95%EB%B3%B4.md)
  * 본 항목은 [32비트](32%EB%B9%84%ED%8A%B8.md), [IA-32](IA-32.md), [x86](x86.md), [x86 아키텍처](x86%20%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98.md)로도 들어올 수 있습니다.  

IBM PC compatible

## Contents

    

1. 개요 
2. 설명 
3. 특징 
4. 역사 
5. 비영어권 국가에서의 자국어 표기 및 보급 
    

5.1. 한국

5.2. 일본

[[edit](http://rigvedawiki.net/r1/wiki.php/IBM%20PC%20%ED%98%B8%ED%99%98%EA%B8
%B0%EC%A2%85?action=edit&section=1)]

## 1. 개요 ¶

[IBM](IBM.md)에서 발표한 [IBM PC](IBM%20PC.md) 아키텍처를 기반으로 만든 개인용
[컴퓨터](%EC%BB%B4%ED%93%A8%ED%84%B0.md) 아키텍처 계열. 흔히 **[PC](PC.md)**라고 부른다.
또 다른 명칭은 **x86 아키텍처**로, 이 명칭은 80286, 80386등과 같이 끝이 86으로 끝나는 인텔 CPU의 모델명에서 나온
이름이다. 2000년대 초중반부터 이 IBM-PC 전체 아키텍처의 기본 구조가 PC를 넘어서 서버나 다른 임베디드 시스템에도 쓰이는 경우가
많아지면서 "x86 아키텍처"라는 이름이 공식적인 명칭이 되어가고 있다.

  

CPU가 64비트를 지원하기 시작하고, 32비트라는 x86 아키텍처의 한계상`[1]` [4GB 이상의 RAM을 제대로 활용할 수 없는문제](RAM/%EC%A3%BC%EC%86%8C%ED%95%A0%EB%8B%B9%20%EB%AC%B8%EC%A0%9C#s-3.md)가
발생함에 따라 AMD가 개발한 [AMD64](AMD64.md) 아키텍처로 빠르게 대체되고 있다. 아직은 그래도 현역취급을 받고 있지만,
32비트라는 x86 아키텍처의 한계상 [2038년 이후의 시간을 제대로 기록할 수 없어 컴퓨터의 시간이 오버플로우 하는현상](2038%EB%85%84%20%EB%AC%B8%EC%A0%9C.md)이 발생할 수 있기 때문에, x86의 수명은 얼마 남지
않은걸로 보인다. 단, AMD64라고 해도 하드웨어의 구조적인 부분은 같은데다, 거의 모든 OS에서 x86 하위 호환성 모드를 지원하기
때문에([윈도우](%EC%9C%88%EB%8F%84%EC%9A%B0.md)의 경우에는 WOW64) 사용자는 x86에서 AMD64로
넘어가는 것에 큰 부담을 느끼지는 않을 듯하다. 과거 16비트에서 32비트로 넘어올 때도 하위 호환을 유지하고 넘어왔듯이, AMD64로
바뀐다고 IBM PC 호환기종 그 자체의 카테고리가 사라지고 생판 다른 아키텍처로 변화하지는 않는다는 의미이다.

[[edit](http://rigvedawiki.net/r1/wiki.php/IBM%20PC%20%ED%98%B8%ED%99%98%EA%B8
%B0%EC%A2%85?action=edit&section=2)]

## 2. 설명 ¶

아키텍처 구조가 모두 공개되어 있고, 각각의 부품이 규격에 맞게 생산되어 나오고 모듈화 되어 있기 때문에, 부품만 구비되어 있다면 납땜 같은
전문적인 과정 없이 슬롯이나 소켓에 끼워맞추고 나사로 고정하면 어렵지 않게 PC 본체 한 대가 나온다. 이 때문에 사용자가 하드웨어 지식을
조금만 익혀도 손쉽게 커스터마이징 할 수 있다. 거기다 그 부품의 조합도 수백, 수천가지가 나올 정도로 다양하다.

  

그런데 사실 딱히 IBM PC에 특별히 규격이 있는 것은 아니다.(...) 회사들이 서로서로 '상호 호환이 가능' 하도록 만든 결과가 이것.
**하드웨어 계의 [오픈소스](%EC%98%A4%ED%94%88%EC%86%8C%EC%8A%A4.md)**라고 봐도 무리가 아니다.

  

덕분에 부품을 가지고 사용자가 직접 만드는 **[조립 PC](%EC%A1%B0%EB%A6%BD%20PC.md)**라는 것이 가능하다.
덕분에 기성품 PC([매킨토시](%EB%A7%A4%ED%82%A8%ED%86%A0%EC%8B%9C.md) 계열 포함)와의
[가성비](%EA%B0%80%EC%84%B1%EB%B9%84.md) 논란에서 가성비 최강으로 항상 손꼽히는 것이 이 조립 PC이다.
물론 사후지원 등 여러가지를 총체적으로 따지면 조립 PC도 기성품에 비해 큰 차이가 나지 않지만`[2]`, 순수하게 부품 단가+공임(용산
기준)+OS가격을 따지면 확실히 조립 PC가 우위에 있는 것도 사실이다.

  

1990년 이후 전 세계의 개인용 컴퓨터는 [애플](%EC%95%A0%ED%94%8C.md)사의
[매킨토시](%EB%A7%A4%ED%82%A8%ED%86%A0%EC%8B%9C.md) 계열을 제외하고는 전부 IBM PC 호환기종이라고
봐도 무방하다. 이마저도 애플이 인텔 CPU를 사용하면서 기본 구조는 거의 같아졌다. 이 때문에 요즘은 윈도우가 매킨토시 계열에서도
설치되고, 맥OS도 해킹을 하면 IBM-PC 호환기종에서 설치된다. 결국 OS를 제외하면 같다. 업무용, 저개발국가용으로 널리 퍼져있는
리눅스 PC하고 다를 것이 없다는 이야기. 그럼에도 스티브 잡스가 상대 진영을 끝가지 계속 'PC'라고 불러서인지 사람들에게 맥 계열
컴퓨터는 IBM 호환 PC와 대척점으로 포지셔닝 되었다. 가정용 컴퓨터 점유율을 보면 애플이 2010->2011에 미국에서 20%의 성장율을
보이는 등 상당히 선전하고 있음이도 전세계적으로는 탑 5안에 들지 못하고 있다.`[3]` 다만 헐리우드 영화나 미드 속 가상의 세계에서는
매킨토시 천하. 등장인물들의 데스크탑 특히 노트북은 애플제가 정말 많이보인다. 이는 애플의 제품라인이 단순하고 외관이 너무 식별이
쉬워서이기도 하고(물론 PPL도 많이 하겠지만, 앵글에 잡히는 제품의 출연 대가는 공짜가 별로 없다.) 미국에서의 점유율은 11.6%(당연히
아이패드류는 제외)로 제품라인이 많지 않고 상대적으로 B2B시장에서 열세인 것 치고는 상당히 높은 편.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/IBM%20PC%20%ED%98%B8%ED%99%98%EA%B8
%B0%EC%A2%85?action=edit&section=3)]

## 3. 특징 ¶

**업무용이다**.

  

원형 IBM PC는 제대로 된 그래픽 모드가 없고 사운드 기능도 없다시피 했다. 그래픽은 [MDA](MDA.md)와
[CGA](CGA.md), 사운드는 삑삑 거리는 [PC스피커](PC%20%EC%8A%A4%ED%94%BC%EC%BB%A4.md)가 전부.<del>삐익~삑!삑!삑!</del> 비즈니스
컴퓨터로서 최대한의 기능을 추구하고 그래픽이나 사운드 같은 사치스러운 기능은 제외했기 때문이다. 대신 CPU 처리가 고속이었다.

  

그래픽이나 사운드 측면에서는 [아미가](%EC%95%84%EB%AF%B8%EA%B0%80.md)나 [아타리ST](%EC%95%84%ED%83%80%EB%A6%AC%20ST.md)같은 홈 컴퓨터가 훨씬 우수했으며, 솔직히 IBM PC로
[게임](%EA%B2%8C%EC%9E%84.md)을 돌리는 것은 문자 그대로 "[그러라고 사준 컴퓨터가 아닐텐데](%EA%B7%B8%EB%9F%AC%EB%9D%BC%EA%B3%A0%20%EC%82%AC%EC%A4%80%20%EC%BB%B4%ED%93%A8%ED%84%B0%EA%B0%80%20%EC%95%84%EB%8B%90%ED%85%90%EB%8D%B0.md)!!"라는 소리를 들을 짓이었다. 하지만
[VGA](VGA.md)와 [사운드카드](%EC%82%AC%EC%9A%B4%EB%93%9C%20%EC%B9%B4%EB%93%9C.md)가 나오면서 서서히 다른 기종과
비교해도 손색이 없는 수준의 멀티미디어 갖추게 된다. 486이 나올 시점에서는 CD-ROM까지 대중화되면서 미려한 그래픽과 사운드를
출력하고, 대용량 보조기억장치까지 갖춘 "멀티미디어 PC"라는 개념으로 발전하게 된다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/IBM%20PC%20%ED%98%B8%ED%99%98%EA%B8
%B0%EC%A2%85?action=edit&section=4)]

## 4. 역사 ¶

PC가 처음 나올 당시에는 아직 여러 회사가 제각기 별도의 아키텍처로 개인용 컴퓨터를 생산하던 시대였다. PC규격도 본래는 IBM에서 만든
업무용 컴퓨터 규격의 하나였지만 다른 회사에 아키텍처를 공개하고, DELL이나 컴팩, [HP](HP.md)에서 마구마구 찍어내면서
사실상 다른 회사의 이종 아키텍처를 몰아내고 전세계 [표준](%ED%91%9C%EC%A4%80.md)으로 자리잡게 되었다.

  

그런데 정신차려보니 정작 밥상을 맛있게 차려놨더니 다른 놈들이 맛있는건 다 처먹어버리고 힘들게 밥상 차린 자신은
[찬밥](%EC%B0%AC%EB%B0%A5.md) 신세가 된 것을 뒤늦게 깨달은 IBM은 MCA(Micro Channel
Architecture)라는 신기술을 바탕으로 PS/2 시리즈를 발매, PC시장 탈환 시도를 하였다. PS/2는 오픈 아키텍처였던 예전의
IBM PC와 달리 클로즈드 아키텍처를 표방했지만 이미 PC시장의 주도권은 [CPU](CPU.md)의
[인텔](%EC%9D%B8%ED%85%94.md)과 [OS](OS.md)의 [마이크로소프트](%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%86%8C%ED%94%84%ED%8A%B8.md) 진영과 그것을 사용한 호환기종을 만드는 다른 PC
제조회사들로 완전히 넘어간 상태여서 결국 **시원하게 망했다.**`[4]` PS/2 아키텍처의 흔적이 지금도 PC에 남아있는데 그게 키보드와
마우스를 연결하는 PS/2 포트`[5]`와 **VGA**`[6]`.

  

실질적으로 80386 시대에 이미 IBM은 이 아키텍쳐의 선도능력을 잃어버렸고, [인텔](%EC%9D%B8%ED%85%94.md)과 [마이크로소프트](%EB%A7%88%EC%9D%B4%ED%81%AC%EB%A1%9C%EC%86%8C%ED%94%84%ED%8A%B8.md)가 아키텍쳐 설계의 중심이 되었다. 이른바 윈텔. 최초의 80386 PC를 발표한 곳도 IBM이 아닌 컴팩이었다. <del>뭐 컴팩도 결국
HP에 팔렸지만</del>

  

이제는 이미 IBM이 PC산업에서 물러나버린 상황이고, IBM PC 호환기종이 아닌 개인용 컴퓨터를 찾기 어려워져서 오히려 이런 표현을 듣는
게 어려워졌다. PC가 곧 IBM PC 호환기종인 것이 당연하게 돼버려서 더 이상 "IBM 호환기종"이라는 말을 붙일 필요도 없는 시대가 된
것이다. 심지어 최근엔 매킨토시조차 PC의 일종쯤으로 생각하는 부류가 대부분... 인텔로 프로세서가 바뀐 지금은 그렇게 다르지도 않지만.

  

2000년대 들어서는 이미 'PC용' 아키텍처라고 부르기가 힘들어졌다. [POS기](POS%EA%B8%B0.md)나
[ATM](ATM.md) 등의 임베디드 기기에도 이걸 쓰고, [서버](%EC%84%9C%EB%B2%84.md)도 이 아키텍처를
쓰는 것이 대단히 많다. 심지어 [아케이드게임](%EC%95%84%EC%BC%80%EC%9D%B4%EB%93%9C%20%EA%B2%8C%EC%9E%84.md)
[기판](%EA%B8%B0%ED%8C%90.md)도 이걸 쓰는 경우`[7]`가 있고, 콘솔 게임 머신 중
[XBOX](XBOX.md), [엑스박스원](%EC%97%91%EC%8A%A4%EB%B0%95%EC%8A%A4%20%EC%9B%90.md), [플레이스테이션4](%ED%94%8C%EB%A0%88%EC%9D%B4%EC%8A%A4%ED%85%8C%EC%9D%B4%EC%85%98%204.md)는
이 아키텍처를 기반으로 한 임베디드 기기라고 봐도 손색이 없다. 이 때문에 IBM-PC 호환기종이라는 명칭 대신 **x86 아키텍처**라는
명칭이 대세가 되어가는 중.

  

결국 현재 IBM PC 혹은 PC라 함은 x86 아키텍처 하드웨어에 윈도우즈 소프트웨어가 결합된 형태, 즉 윈텔을 지칭하게 되었다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/IBM%20PC%20%ED%98%B8%ED%99%98%EA%B8
%B0%EC%A2%85?action=edit&section=5)]

## 5. 비영어권 국가에서의 자국어 표기 및 보급 ¶

[[edit](http://rigvedawiki.net/r1/wiki.php/IBM%20PC%20%ED%98%B8%ED%99%98%EA%B8
%B0%EC%A2%85?action=edit&section=6)]

### 5.1. 한국 ¶

기존의 8비트 PC가 한글,한자 등 동아시아권 문자`[8]` 처리에 성능상 어려움이 있다 보니 상대적으로 <del>본고장인 미국을
제외하고</del> 16비트에 집중적인 관심을 보이게 되었다. 이는 알파벳 위주의 문자체계를 가진 유럽에서 90년대 중반까지도 8비트 PC를
제법 많이 볼 수 있었던 것과는 비교된다.

  

하지만 일본보다 기술수준이 낮았던 관계로`[9]` 역설적으로 IBM PC 호환기종의 보급이 상대적으로 무척 빨랐다. 거기에 한국 특유의
교육열도 한몫 했는데 1989년 교육용 PC를 정할 때, IBM PC XT 기종을 결정한 것. 당시 다가오는 21세기는 정보화 시대로 이미
예상되고 있었고, 이 흐름에 동참하기 위해서는 컴퓨터를 배워야 한다는 인식이 특히 강한 때였다. 이런 상황에서 [교육용PC사업](%EA%B5%90%EC%9C%A1%EC%9A%A9PC%20%EC%82%AC%EC%97%85.md)에서 IBM-PC가 결정되자
IBM PC 호환기종이 갑자기 많이 팔리기 시작하고, 거기에 맞춰 PC 산업이 8비트에서 16비트 위주로 급속하게 재편되었다. 애플과 MSX
호환기종이 나눠 가지고 있던 시장은 1989년 이후 단 1~2년만에 IBM-PC 호환기종으로 통일되었다. 물론 이는 교육열 보다는 PC
제조업체들의 로비(..)라는 의견도 많다.`[10]`

  

한국 회사를 통해서 한글 MS-DOS도 나왔지만, 소프트웨어적인 방법으로 완성형(ks) 한글을 텍스트 방식으로 표시했기 때문에 영문판
DOS보다 메모리 점유율이 높은데다가,`[11]` 텍스트 모드를 후킹해서 그래픽으로 뿌려주는 방식의 특성상 반응성이 떨어지는 편이어서 그다지
인기는 없었다. MS 사에서 신버전 DOS가 나와도 한글판 DOS는 버전업이 한두 달 늦었다. 이 때문에 한국 프로그래머들은 적극적으로 자체
한글 표시가 가능한 유틸리티를 개발해 일본보다는 자국어 표시에 열정적이었다. [아래아한글](%EC%95%84%EB%9E%98%EC%95%84%20%ED%95%9C%EA%B8%80.md)이나
[이야기](%EC%9D%B4%EC%95%BC%EA%B8%B0.md) 같은 경우는 아예 그래픽 모드를 기반으로 한글을 처리했다. 그리고
확장카드를 통해 적은 메모리로 한글을 깔끔하게 구현한 곳도 있었다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/IBM%20PC%20%ED%98%B8%ED%99%98%EA%B8
%B0%EC%A2%85?action=edit&section=7)]

### 5.2. 일본 ¶

1980년대 당시 일본의 PC 설계기술은 미국 다음이였고 일본어 처리와 독특한 아니메 문화와 관련되어 높은 그래픽기능을 필요로 했으나 업무용
컨셉이였던 IBM PC는 VGA카드 출시 전까지 그래픽기능에 큰 관심이 없었다. 그러다보니 [PC-9801](PC-9801.md)을
비롯한 독자적인 아키텍쳐의 PC들이 NEC, [샤프](%EC%83%A4%ED%94%84%EC%A0%84%EC%9E%90.md),
후지쯔, [히타치](%ED%9E%88%ED%83%80%EC%B9%98.md) 등 여러 제조사에서 제조되었다. <del>그래서
[에로게](%EC%97%90%EB%A1%9C%EA%B2%8C.md)도 많이 나왔고</del> 그러다 보니 IBM PC 호환기종의 필요를
느끼지 못했다. 더군다나 80년대 중,후반기는 일본의 거품 경제 전성기라서 온갖 희안한 기능으로 떡칠한 고가의 자국 기종도 잘 팔렸던
시기였다. 그 결과 한 제조사에서도 가정용, 업무용으로 서로 다른 아키텍쳐의 16비트 기기`[12]`를 출시하는 등
[갈라파고스화](%EA%B0%88%EB%9D%BC%ED%8C%8C%EA%B3%A0%EC%8A%A4%ED%99%94.md)의 정점을
이루고 있었다. 그러니 IBM-PC 호환기종의 도입은 매우 늦어졌다.

  

일본에서는 그동안 IBM PC 호환기종 컴퓨터들은 [일본어](%EC%9D%BC%EB%B3%B8%EC%96%B4.md)를 지원하지 않아서
인기가 저조했다가, [DOS/V](DOS/V.md)라는 이름의 일본어 지원 OS가 나오고 나서야 점유율을 늘려가기 시작했기 때문에, 이
기종을 주로 DOS/V라고 불렀으며, 지금도 그렇게 부르는 사람이 있다(...)`[13]`

  

그럼에도 불구하고 일본에서 PC가 주류로 자리잡게 된 것은 윈도우즈95가 나오면서 일본어가 완전하게 지원된 뒤의 일이라 한다. 당시 자국
환경에 맞춘 고유의 아키텍처([MSX](MSX.md), [PC-9801](PC-9801.md) 등)가 나온 일본은 이들 기종과
경쟁해야 했기 때문. 게다가 시기적으로도 거품경제가 끝나고 잃어버린 10년이 되면서 표준화된 생산방식으로 원가를 낮춰 저렴한 가격으로 수입된
동아시아(한국,대만,홍콩)제 IBM PC 호환기종에 대한 관심 또한 일본에서 PC 호환기종으로의 전환에 한 역할을 했다고 볼 수 있다.

`\----`

  * `[1]` 사실 x86아키텍처는 3가지로 나뉜다. 16비트의 IA-16, 32비트의 IA-32, 64비트의 x86-64가 있다. 좁은 의미의 x86은 IA-32를 말하고, 64비트를 나타낼 때에는 [x86-64](AMD64.md)라고 따로 지칭한다. IA-64는 이름과 달리 IA-32와 전혀 다른 아키텍처라 X86으로 분류하지 않으며(x86 인스트럭션을 에뮬레이션으로 지원하기는 한다) IA-64를 채용한 아이태니엄 시리즈는 인텔의 [흑역사](%ED%9D%91%EC%97%AD%EC%82%AC.md). 
  * `[2]` AS가 안 되는건 아니지만 총체적인 AS가 안되고, 부품별로 된다. 이 때문에 부품간의 호환성 문제로 발생하는 문제는 사용자가 직접 캐치해야 한다.
  * `[3]` 5등이 아수스인데 점유율 6.8%. 물론 모든 PC가 IBM PC의 전형적인 이미지인 윈텔, 즉 마이크로소프트의 OS를 탑재하지는 않지만. 개인용 컴퓨터에서 다른 OS의 점유율은 정말 작다.
  * `[4]` 그런데 아이러니하게도 다른 PC 제조회사들이 MCA의 대항마로 내놓았던 EISA도 시원하게 망하기는 마찬가지였다. ISA와 호환이 되는 장점이 있었지만 비싼 가격이 문제였다는 평. 결국 486 시대에는 ISA 옆에 VESA 로컬 버스를 붙이는 방식으로 버텼고, 진짜 승자는 펜티엄 시절에 나온 인텔의 PCI가 되었다.
  * `[5]` 그나마 [USB](USB.md)에 밀려서 서서히 사라져가는 중이다.
  * `[6]` 초창기의 VGA는 PS/2 머신에 회로의 형태로 내장되어 있었는데 그것을 호환기기 개발사들이 **리버스 엔지니어링**을 통해 비디오카드의 형태로 만든 것이 VGA 카드의 시초이다.
  * `[7]` [타이토](%ED%83%80%EC%9D%B4%ED%86%A0.md) [Type X](Type%20X.md), [세가](%EC%84%B8%EA%B0%80.md) [LINDBERGH](LINDBERGH.md) 등등
  * `[8]` Double-Byte Charactor Set. 2바이트 문자 체계
  * `[9]` 그렇지만 1980년대 당시 독자적인 PC 아키텍쳐를 설계할 수 있는 국가는 미국,일본 정도였다. 세계적 기준으로 본다면 낮지는 않은 편.
  * `[10]` 8비트 기종의 경우 1987~89년 당시 애플 호환기종은 세운상가 기반 중소업체에서만 나왔고 MSX는 대우전자에서만 만들었었다. 교육용 시장에 관심이 큰 [삼성](%EC%82%BC%EC%84%B1.md), [금성(현 LG)](LG%EC%A0%84%EC%9E%90.md), [현대](%ED%98%84%EB%8C%80.md), [삼보](%EC%82%BC%EB%B3%B4.md) 같은 대기업들이 8비트를 밀을 리 없다.
  * `[11]` hbios라는 프로그램을 사용했는데 기본 메모리가 640kb이던 시절에 4~50kb 이상을 혼자 점유했다. 당연히 겜돌이들에겐 기피대상. 다만 hbios /e라는 옵션을 줘서 재실행하면 1kb도 남기지 않고 깔끔하게 언로딩할 수 있어서 안 좋은 소리는 듣지 않았다.
  * `[12]` 당연히 소프트웨어가 <del>이식없이는</del> 상호 호환되지 않는다.
  * `[13]` 요도바시 카메라나 빅 카메라 같은 곳의 PC 부품 매장 중에는 아직도 DOS/V 코너가 있는 곳도 있다. 빅 카메라 신주쿠 서쪽 출구점 4층이라거나 (...)


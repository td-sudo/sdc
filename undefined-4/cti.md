# 상담콜 CTI

상담콜 CTI '상담하기' 기능

콜관리 메뉴에서 전화 응대 환경 세팅을 먼저 완료해 주세요.\
아직 환경 세팅을 완료하지 않으셨다면 '[**기본 환경 설정**](../undefined-1/undefined/)' 가이드를 참고해 주세요.

{% hint style="info" %}
전화 상담에 필요한 [기본 환경 설정](../undefined-1/undefined/)을 마쳤다면, 상담하기 기능을 사용하실 수 있습니다.
{% endhint %}

## 1. 상태 정보

**우측 상단**에서 **착신번호**와 계정 소유자의 **이름**을 확인하실 수 있습니다.\
이름을 클릭하여 상태를 변경하실 수 있습니다.

![](<../.gitbook/assets/image (69).png>)                    **콜 수신**이 **가능**한 상태인 경우  초록색으로  표시됩니다.

![](<../.gitbook/assets/image (70).png>)<mark style="color:purple;">**️**</mark>                      **수신안함 상태**인 경우 **회색**으로 표시됩니다.

![](<../.gitbook/assets/image (71).png>)  전화가 연결되어 **통화 중**인 경우, **빨간색**으로 표시됩니다.

## 2. 담당 전화번호

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

**착신번호**로 등록한 전화번호를 확인하실 수 있습니다.

{% hint style="info" %}
여러개의 착신번호를 사용하는 경우, 선택한 번호로 아웃콜 (아운바운드) 통화가 이루어 집니다.
{% endhint %}

## 3. 인바운드 전화 처리하기

**고객**이 ARS 시나리오 멘트를 듣고, **전화 연결**을 요청하는 경우 사전에 등록한 착신번호로 고객의 전화를 수신하게 됩니다.

\[당겨받기] 버튼: 다른 상담원 자리에서 버튼을 선택하면 해당 고객전화가 \[당겨받기] 버튼을 선택한 상담원의 전화로 연결됩니다.

<figure><img src="../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**고객의 전화 연결 요청 발생 시 실시간으로 전화 상담을 요청한 고객의 전화 번호**와 **대기 건수**를 **안내**합니다.
{% endhint %}

* **대기중**인 **전화번호**를 **클릭**하면 해당 **고객**에 대한 **정보**를 사전에 열람하실 수 있습니다.
* 아래 예시 이미지의 고객은 **신규 고객**이며, 'today' 영역에서 오늘의상담건수 / 부재중 통화 건을 사전에인지하고 응대할 수 있습니다.
* **네이버 스마트스토어에서 상품을 판매중이시라면 \[주문정보 조회] 버튼을 클릭하시면**\
  **인입된 고객의 스마트스토어 주문정보를 조회할 수 있습니다.**\
  **- 크롬 브라우저에서만 조회 가능합니다.**

<figure><img src="../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

* 추가로 상담이력, 메모 탭을 선택하여 고객이 어떤 응대를 받았는지 확인해보세요.\
  상담이력은 월 단위로 조회할 수 있습니다.
* 시간대 별로 고객이 어떤 응대를 받았는지, 여러번 통화를 시도했는데 통화 연결이 되지 않았다면 사전에 미리 인지하고 고객에게 전화 연결 지연에 대해 먼저 사과를 할 수도 있겠죠?

<figure><img src="../.gitbook/assets/image (76).png" alt=""><figcaption><p>상담이력 탭</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (78).png" alt=""><figcaption><p>메모 탭</p></figcaption></figure>

* 해당 정보를 바탕으로 고객의 불만을 해소하기 위해 프로모션 쿠폰 등을 발행 한다거나,\
  신규 고객을 충성고객으로 유치 할수도 있겠네요!



## 4. 아웃콜

**상담콜 CTI**에서는 **아웃콜**(아웃바운드) 전화 기능을 제공하고 있습니다.\
아웃콜 기능을 사용하기 위해 먼저 좌측의 **콜 목록** 중 전화를 걸고자 하는 번호를 선택해 주세요.

{% hint style="info" %}
목록 선택 후 우측 고객정보 영역 상단에 '**전화걸기**' 버튼을 선택하시거나

화면 상단의 \[전화걸기] 버튼을 선택하여 전화 받으실 고객번호를 직접 입력하실 수도 있습니다.
{% endhint %}

<figure><img src="../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

*   전화걸기 버튼 선택 시 착신번호로 설정하신 (담당번호) 번호로 전화가 옵니다.

    ※ 아웃콜 연결을 위해 시스템에서 담당 전화번호로 전화 연결을 요청하는 단계입니다.
* 수화기를 들면, "통화를 시작합니다" 멘트와 함께 통화 연결음이 시작됩니다.
* 이후 고객의 전화로 전화 연결이 진행되며, 고객이 전화 받기를 선택하면 "ooo상담원으로부터 걸려온 전화입니다" 멘트와 함께 전화 통화 연결이 완료됩니다.

## 5. 고객정보 입력하기

처음 응대하는 고객의 정보를 기록하실 수 있습니다.\
고객정보 영역 우측 하단의 \[편집] 버튼을 눌러주세요.

<figure><img src="../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
고객의 이름, 이메일, 주소 등 필요 정보를 등록하실 수 있습니다.
{% endhint %}

<figure><img src="../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>



* 정보 입력 후 반드시 등록 버튼을 눌러주세요.

## 6. 상담 내역 후처리

상담 정보 영역에서 다양한 후처리 기능을 지원하고 있습니다.\
상담 메모, 상담 분류 선택(상담유형), 플래그, 고객 분류, 처리 상태를 기록하실 수 있어요.

<figure><img src="../.gitbook/assets/image (85).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
상담 분류는 콜관리 > 서비스 관리 > [**상담 분류 설정**](../undefined-1/undefined/undefined-2.md) 메뉴에서 설정하신 분류 값을 사용하시게 됩니다.
{% endhint %}

* 플래그 기능을 통해 해당 상담 건을 5가지로 분류하여 표시할 수 있습니다.\
  색상 별 규칙을 정하시면 해당 상담 건이 어떤 상태로 처리 되었는지 쉽게 확인할 수 있겠네요.

<figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

* 어떤 회원인지도 기록할 수 있습니다.

<figure><img src="../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>

* 처리 상태 내용도 선택해 주세요.

<figure><img src="../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>

## 7. 콜백 예약하기

고객에게 다시 전화를 걸어야 하는 경우, **콜백 예약 기능**을 사용해보세요.\
\
**등록방법 1.** 상담 건 후처리 영역 하단에서 '빠른 콜백예약'을 등록할 수 있습니다. 이 때 담당자는 해당 콜백예약을 진행하는 상담사로 자동 등록됩니다.

<figure><img src="../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

**등록방법 2.** 우측 '콜백' 탭에서 다른 담당자를 지정하여 콜백 예약을 등록할 수 있습니다.

<figure><img src="../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>

* 예약날짜 및 예약시간과 담당자 선택, 추가 필요한 메모를 입력하신 후 \[등록] 버튼을 누르면\
  콜백 예약이 완료됩니다.

{% hint style="info" %}
예약하신 시간 10분 전에 알림으로 콜백 예약 건에 대하여 미리 알려드리고 있습니다.
{% endhint %}

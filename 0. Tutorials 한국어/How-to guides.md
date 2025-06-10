# How-to guides

지금 내가 이걸 어떻게 하지? 라는 류의 고민을 하고 있는 당신이 있습니다. 
이 가이드는 목표지향적이고 견고합니다.

가이드들은 당신이 구체적인 task 를 완료할 수 있도록 합니다. 개념적인 설명을 위해서는 [conceptual guides](../archive/Conceptual%20guides.md) 찾아보세요. 

end-to-end walkthroughts 는 [Tutorial](Tutorials.md) 를 보세요. 

모든 클래스나 함수에 대한 포괄적인 설명은 [API Reference](../archive/api_reference.md) 를 참고하세요.

## Installation

* [How to: 랭체인 패키지 설치](../archive/howtoinstalllLangchainpackage.md)
* [How to: 다른 Pydantic 버전에서 랭체인 사용하기](../archive/howtouselangchainwithdifferentpydanticversion.md)

## Key Features

아래는 랭체인을 사용하는데 중요한 코어 기능입니다.

* [How to: 모델로부터 자료구조 리턴받기](../archive/howtoreturnstrtucteddatafromamodel.md)
* [How to: call tool 로 모델 사용하기](../archive/howtouseamodeltocalltools.md)
* [How to: stream runnables](../archive/howtostreamrunnables.md)
* [How to: LLM 앱 디버깅하기](../archive/howtodebugyourlllmapps.md)


## Componuents

아래는 당신이 어플리케이션은 만들 때 사용할 수 있는 중요한 빌딩 블럭들입니다.

### Chat Models
[Chat Models](../archive/chatmodels.md) 은 메시지를 받고 보내는 언어모델의 forms 입니다. [Supported intergraions](../archive/supported%20integrations.md) 에 chat models 를 시작하는 구체적인 것들이 있습니다. 

### Message
[Messages](../archive/message.md) 는 chat models 의 입출력입니다. 메시지는 메시지를 설명하는 정보와 역할을 가지고 있습니다.

### Prompt Templates
[Prompt Templates](../archive/prompttemplate.md) 은 유저의 인풋을 언어모델에 들어갈 수 있도록 포맷에 넣어주는 규격화 된 포맷입니다. 

### Example Selectors
# AMP 디자인 원칙

이 디자인 원칙은 의도와 AMP개발을 위한 가이드이다.
이 글은 일관적인 결정을 하는데 도움이 될 것이다.

## User Experience > Developer Experience > Ease of Implementation.
## 사용자 경험 > 개발자 경험 > 구현이 쉽게 되었는지

앱 개발자나 라이브러리 개발자가 어렵더라도 사용자 경험이 쉬운것을 우선시 한댜

## Don’t design for a hypothetical faster future browser.
## 아직 만들지 않은 미래의 브라우저를 위해서 설계하지 않는다.

AMP는 extensible web manifesto의 뜻대로 내일의 웹이 아니라 오늘의 웹을 만들기로 했다.

AMP는 현재의 브라우저에서 빠르다. 특정 최적화는 미래의 플랫폼에서 불가할 수 도있다. AMP 개발자는 웹표준 개발에 참여해서 웹 플랫폼에 이러한 점을 추가 할 수 있도록 해야한다.

## Don’t break the web.
## web을 파괴하지 않는다.

Ensure that if AMP has outages or problems it doesn’t hurt the rest of the web. That means if the Google AMP Cache, the URL API or the library fails it should be possible for websites and consumption apps to gracefully degrade. If something works with an AMP cache it should also work without a cache.

AMP가 동작하지않거나 문제가 있을때 나머지 웹요소에는 영향을 끼치지않는 것을 보장한다. 만약 Google AMP Cache(URL API or the library)가 실패한다면 이것은 성능이 저하되더라도 웹사이트를 이용가능해야 한다.
만약 AMP캐시를 사용하는 다른 것이 있다면 이것은 캐시없이 동작해야한다.

## Solve problems on the right layer.
## 알맞은 계층에서 문제를 해결하라

E.g. don’t integrate things on the client side, just because that is easier, when the user experience would be better with a server side integration.

예: 사용자 경험을 좋게하는 것은 클라이언트 사이드에서 integrate하는 것 보다 는 서버 사이드에서 integrate 하는것이 좋다

## Only do things if they can be made fast.
## 더 빠르게 할 수 있는 경우에만 작업한다.

Don’t introduce components or features to AMP that can’t reliably run at 60fps or hinder the instant load experience on today’s most common mobile devices.

근래의 일반적인 모바일 디바이스에서 60fps 또는 즉시 로드 경험을 주지 못하는 component 또는 feature는 도입하지 않는다.

## Prioritise things that improve the user experience – but compromise when needed.
## 사용자 경험을 향상시키는 것이 우선순위이지만 필요시에는 타협한다.

Some things can be made fast and are still a terrible user experience. AMPs should deliver a fantastic user experience and speed is just one part of that. Only compromise when lack of support for something would stop AMP from being widely used and deployed.

어떤 것들은 빠르게 만들 수있으면서 사용자 경험이 나쁘다. AMP는 멋진 사용자 경험을 제공하고 속도는 하나의 부분이다. AMP가 널리 배포되는 것을 안되는 경우에 대한 지원이 없을 때 만 타협하라

## No whitelists.
## 화이트리스트를 사용하지 않는다.

We won’t give any special treatment to specific sites, domains or origins except where needed for security or performance reasons.

우리는 security or performance reasons이 필요하지 않는 특정한 사이트, 도메인, origin에 특별한 취급을 하지 않는다.
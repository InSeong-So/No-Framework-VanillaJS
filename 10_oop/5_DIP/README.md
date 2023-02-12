# DIP - 의존성 역전 원칙
> Dependency Inversion Principle

의존성 역전 원칙(DIP)은 높은 수준의 모듈이 낮은 수준의 모듈에 의존해서는 안 되며, 둘 다 추상화에 의존해야 한다는 SOLID 설계 원칙입니다.
즉, 추상화(예: 인터페이스 또는 추상 클래스)는 코드의 안정적인 부분이어야 하며, 이러한 추상화의 구체적인 구현은 가변적인 부분이어야 합니다.

DIP를 준수하면 높은 수준의 모듈에 영향을 미치지 않고 추상화의 구체적인 구현을 더 쉽게 변경할 수 있으므로 보다 유연하고 유지 가능한 코드베이스를 촉진하는 데 도움이 됩니다.
또한 코어 코드를 변경하지 않고도 새로운 기능을 추가하거나 기존 기능을 쉽게 수정할 수 있습니다.

개발자는 DIP를 준수함으로써 시간이 지남에 따라 유지보수 및 수정이 쉽고 변화하는 요구사항에 적응할 수 있는 유연하고 확장 가능한 설계를 만들 수 있습니다. DIP는 다른 SOLID 원칙과 밀접하게 관련되어 있으며, 코드베이스를 보다 유연하고 확장 가능하며 유지보수 가능하게 만드는 목표를 달성하는 데 도움이 됩니다.
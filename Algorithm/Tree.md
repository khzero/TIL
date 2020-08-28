# Tree(트리 구조)

부모 노드와 자식 노드로 구성된 가지 모양 구조

## 이진트리

자식 노드가 최대 2개인 노드들로 구성된 트리

### 종류

#### 포화이진트리

모든 노드가 두개의 자식노드를 가지며, 부모 노드는 동일한 깊이 또는 레벨을 갖음.

#### 완전이진트리

마지막 레벨을 제외하고 모든 레벨이 완전히 채워져 있고,
마지막 레벨에서는 왼쪽부터 노드가 순서대로 채워져 있음.

### 순회 방법

#### 전위순회

루트 노드부터 왼-오 순으로 순회(current - left - right)

#### 중위순회

왼쪽 하위 트리의 노드부터 오른쪽 방향으로 순회(left - current - right)

#### 후위순회

왼-오-자신 순으로 순회(left - right - current)
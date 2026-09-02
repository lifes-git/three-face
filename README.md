# 얼굴 특징 측정 시각화

각도와 조명이 바뀌면 사람이 정의한 특징 수치가 무너진다는 것을 보여주는 3D 인터랙티브 시각화.

## 배포 방법

### 1. 저장소 만들기

GitHub에서 새 저장소를 만듭니다. 이름은 자유롭게 정하고 Public으로 설정합니다.

### 2. 파일 올리기

`index.html`을 저장소 루트에 올립니다.

### 3. 모델 파일 (선택)

HTML이 세 가지 경로를 순서대로 시도합니다.

1. `./LeePerrySmith.glb` — 같은 폴더에 있는 파일
2. jsDelivr CDN
3. threejs.org

2번이나 3번이 동작하면 모델 파일 없이도 됩니다. 안 되면 아래에서 받아서 저장소에 함께 올리세요.

https://github.com/mrdoob/three.js/raw/dev/examples/models/gltf/LeePerrySmith/LeePerrySmith.glb

파일명은 `LeePerrySmith.glb` 그대로 두고 `index.html`과 같은 위치에 놓습니다.

### 4. Pages 켜기

저장소 Settings → Pages로 이동합니다.
Source를 `Deploy from a branch`로 두고 Branch를 `main` / `/ (root)`로 설정한 뒤 Save를 누릅니다.

1~2분 뒤 아래 주소로 접속됩니다.

```
https://<사용자명>.github.io/<저장소명>/
```

### 5. 노션에 임베드

노션 페이지에서 `/embed`를 입력하고 위 주소를 붙여넣습니다.
임베드 높이는 420px 정도가 적당합니다.

## 조작

- 드래그로 얼굴 회전
- 슬라이더로 조명 조절
- 정면으로 되돌리기 버튼으로 초기화

# Toy_Example_Push_T

이 폴더는 `flow_matching_policy_state_pusht_demo.ipynb`를 로컬에서 실행하기 위한 최소 예제입니다.

## 레퍼런스

이 노트북은 Diffusion Policy 공개 자료의 Push-T 데모를 참고했습니다.

- https://diffusion-policy.cs.columbia.edu/

## 실행 방법

Python 3.10 기준으로 아래 순서대로 실행하세요.

```bash
cd /path/to/Toy_Example_Push_T
python3.10 -m venv .venv
. .venv/bin/activate
python -m pip install --upgrade "pip<26" "setuptools<81" wheel
python -m pip install --no-compile -r requirements.txt
```

## 데이터셋 파일

노트북은 `pusht_cchi_v7_replay.zarr.zip`이 없으면 자동 다운로드를 시도합니다.  

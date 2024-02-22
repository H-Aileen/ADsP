### 새로운 환경 만들기

```
conda create -n [환경이름] python=3.8
conda activate [환경이름]
```

---
### 주피터에서 새로운 환경 사용하기
```
# 주피터 설치
pip install jupyter

# 주피터에서 환경 불러오기 위함
pip install ipykernel
python -m ipykernel install --user --name=[환경이름]
```

# README

為咗令每日揀食乜嘅過程唔好咁痛苦, 我地偉大嘅EPM同事設計咗呢個小程式去幫大家決定食咩。
以下嘅command都係用`windows powershell`進行

## pipenv

呢個project用咗`pipenv`來控制 python library version

1. 如果未裝`pipenv`, 用`pip install pipenv`裝返佢先
2. 用`pipenv run py eat_what_generate.py`開始呢個program

## intellisense

- 如果你係用緊vscode來開, 可以去右下角選擇返呢個project 的pipenv產生嘅virtual environment (format 會類似`.virtualenvs\eat_what_generater-QNZ1ZMrG`)
- 見唔到選擇嘅話, 可以用`pipenv --venv`顥示返條path, 再人手加入去

## 太長, 唔想睇 TLDR

- install python
- `pip install pipenv`
- `pipenv run py .\eat_what_generate.py`
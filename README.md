# 4行のスパムボット
## 環境設定
Terminalを開いて、
`virtualenv spam-bot`
で仮想環境を構築します。virtualenvがインストールされてない場合は、
`pip install virtualenv`
でインストールできます。
`source spam-bot/bin/activate`
で仮想環境を起動したら、
`pip install pyautogui`
で必要なライブラリをインストールします。
仮想環境を停止したい場合、`deactivate`

## 使い方
`python3 spam-bot.py`
で起動したら、LINEやYoutubeライブなどのテキスト入力ボックスをクリックするだけです。
forループ内を適宜変更して迷惑が掛からないように友人間なのでお遊びください。

# -
観光地認識アプリ
このリポジトリは、StreamlitとAnthropic APIを使用して、画像から観光地を認識するアプリのソースコードを含んでいます。このプロジェクトは、Pythonを使った画像処理とAI技術の実践的なチュートリアルです。

特徴
インタラクティブなWebアプリ: Streamlitを使用して、ユーザーが簡単に画像をアップロードし、観光地を認識することができます。
画像処理: Pillowライブラリを使用して、画像をbase64形式に変換。
Anthropic API連携: アップロードされた画像をAnthropic APIに送信し、観光地を認識
。
必要なライブラリ
pip install streamlit pillow anthropic

使用方法
リポジトリをクローンします:
git clone https://github.com/あなたのユーザー名/観光地認識アプリ.git

必要なライブラリをインストールします:
pip install -r requirements.txt

app.py ファイルを開き、YOUR APIをあなたのAnthropic APIキーに置き換えます:

streamlit run app.py を実行してアプリを起動します。

ファイル構成
app.py: メインのStreamlitアプリケーションファイル。
requirements.txt: 必要なPythonライブラリのリスト。

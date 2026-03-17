ディレクトリ名を変更して clone したいとき
git clone <URL> <新しいディレクトリ名>

applicationを記載したファイルが保存されているディレクトリ名を変更した時は
FLASK_APP の値も変更

仮想環境の再構築
clone 後に必ず仮想環境を構築し、依存関係もインストール
python3 -m venv .venv
pip install -r requiremrnts.txt

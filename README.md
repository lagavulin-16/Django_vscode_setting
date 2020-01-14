# Django_vscode_setting
VSCodeでDjango使って開発する際の設定もろもろの覚え書き

1. 同一フォルダ内にこれと仮想環境とDjangoプロジェクトのルートフォルダを置く。これのフォルダ名は.vscodeにする
2. launch.jsonの"projectname"をプロジェクトのルートフォルダの名称に書き換える
3. settings.jsonの"venv"を仮想環境のフォルダ名に書き換える
4. .env内にデバッグ時の環境変数を設定(サンプルではDBにPostgreを使うための設定にしてある)

これでvscodeからデバッグできる

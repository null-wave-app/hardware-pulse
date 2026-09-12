# Hardware Pulse v0.1.1 preview

カードからプロセスの使用状況を直接確認できる preview です。

## v0.1.0 からの変更

- CPU・メモリ・GPU・VRAM のカードをクリックすると、その指標の降順でプロセス一覧を表示
- CPU の詳細に「プロセス」「コア別」タブを追加
- 独立した Processes カードを廃止
- 既存の検索・列設定・グループ詳細・終了確認を継続して利用可能

## 含まれる機能

- CPU、GPU、メモリ、VRAM の状態表示
- 負荷、クロック、温度、電力の表示（取得できる値のみ）
- グラフと統計表示
- メトリックカードの表示順、表示倍率、テーマ、アクセントカラー設定
- プロセス一覧、検索、列設定、グループ詳細
- 選択プロセスの終了操作

## 配布

- Asset: HardwarePulse-v0.1.1-win-x64.zip
- 対象: Windows 11 x64
- 動作確認: Windows 11 x64 build 26200
- .NET ランタイム同梱
- 未署名の実行ファイル

CPU 温度や一部センサーは、ハードウェア、ドライバー、LibreHardwareMonitor、PawnIO、UAC、管理者権限の組み合わせにより取得できない場合があります。Hardware Pulse はドライバーを自動導入しません。

プロセス終了では未保存の作業を失う可能性があります。設定は %APPDATA%\HardwarePulse\settings.json に保存されます。自動更新はありません。

第三者ライセンスと notices は [THIRD-PARTY-NOTICES.txt](https://github.com/null-wave-app/hardware-pulse/blob/main/THIRD-PARTY-NOTICES.txt) を参照してください。

ZIPをすべて展開して `HardwarePulse.exe` を起動してください。`Source code` の自動生成アーカイブにはアプリ本体は入っていません。

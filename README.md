## レジストリ置き場 (Registry-Repository)
Windows 11 (10) 用のカスタマイズレジストリエントリ

🟦 カテゴリ

 - HKEY_CLASSES_ROOT
 - HKEY_CURRENT_USER
 - HKEY_LOCAL_MACHINE
 - コンテキストメニュー削除
 - コンテキストメニュー追加
 - その他

<br>
🟦 内容

 - Windows 11 のカスタマイズ用エントリ<br>
   ⚠️　ツール、画像、アイコンなどのパスは環境に合わせて編集してください。

<br>
🟧 除外

 - ハードウェア依存
 - CPU,GPU,メモリ関連のカスタマイズ
<br><br>
---

🟢　テンプレート
~~~
Windows Registry Editor Version 5.00

;----- 説明 -----
[HKEY_CURRENT_USER\Software\********]
"*****"=*****

; 備考など(必要と思われる場合)

~~~
<br>
🟡 備考 :<br>
🔸大文字/小文字の区別<br>
　　　HKEY_CURRENT_USER\Software<br>
　　　HKEY_LOCAL_MACHINE\SOFTWARE
<br>
🔸コメントは、; (セミコロン)
<br>
🔸エンコーディング : UTF-16 BOM付
<br>
<br>

---
🟨 更新履歴 :<br>

**2026-01-29**
 - 25H2 新機能有効化エントリ.reg 追加

**2026-01-28**
 - いくつか追加

**2026-01-24** 公開


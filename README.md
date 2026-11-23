# ucc3-firmware

USB Cable Checker 3 のファームウェアと、ファームウェア更新ツール(Windows 用)の配布場所です。

## ダウンロード

最新の更新ツールは、次のリンクからダウンロードできます。

**[UCC3-Firmware-Updater-Windows.zip](https://github.com/aroerina/ucc3-firmware/releases/latest/download/UCC3-Firmware-Updater-Windows.zip)**

zip を展開して `ucc3-updater.exe` を起動します。使い方は、zip に入っている `.txt` を読んでください。
更新ツールは起動したときに、ここにある最新のファームウェアを自動でダウンロードします。

これまでの版は [Releases](https://github.com/aroerina/ucc3-firmware/releases) にあります。

## 更新できる本体

> [!IMPORTANT]
> **ファームウェア v1.x.x の本体は、ファームウェアの更新に対応していません。**
> v1.x.x の本体には USB でファームウェアを更新する機能がないため、この更新ツールでは更新できません。

更新できるのは、ファームウェア v2.0.0 以降の本体です。
本体のファームウェアのバージョンは、電源を入れたときの起動画面に出ます。

## このリポジトリにあるもの

各 Release に、次のファイルを入れています。

| ファイル | 中身 |
|---|---|
| `UCC3-Firmware-Updater-Windows.zip` | 更新ツール(`ucc3-updater.exe`)と使い方 |
| `ucc3_app_r13_X.Y.Z.ucc3fw` | ファームウェア。更新ツールが使います |
| `latest.json`、`latest.json.sig` | ファームウェアの一覧と、その電子署名。更新ツールが、本物のファームウェアかどうかを確かめるのに使います |

---

## English

Firmware and the Windows firmware updater for USB Cable Checker 3.

- Download the latest updater: [UCC3-Firmware-Updater-Windows.zip](https://github.com/aroerina/ucc3-firmware/releases/latest/download/UCC3-Firmware-Updater-Windows.zip).
  The updater downloads the latest firmware from this repository by itself.
- **Devices with firmware v1.x.x do not support firmware updates.** They have no USB update function, so this updater cannot update them.
  Firmware v2.0.0 and later can be updated. The device shows its firmware version on the startup screen.

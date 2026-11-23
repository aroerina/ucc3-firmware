# ucc3-firmware

USB Cable Checker 3 のファームウェアと、ファームウェア更新ツール(Windows 用)の配布場所です。

Firmware and the firmware updater (for Windows) for USB Cable Checker 3.

## ダウンロード / Download

**[UCC3-Firmware-Updater-Windows.zip](https://github.com/aroerina/ucc3-firmware/releases/latest/download/UCC3-Firmware-Updater-Windows.zip)**

最新の更新ツールは、上のリンクからダウンロードできます。
zip を展開して `ucc3-updater.exe` を起動します。使い方は、zip に入っている `.txt` を読んでください。
更新ツールは起動したときに、ここにある最新のファームウェアを自動でダウンロードします。
これまでの版は [Releases](https://github.com/aroerina/ucc3-firmware/releases) にあります。

Download the latest updater from the link above.
Unzip it and start `ucc3-updater.exe`. The `.txt` file in the zip explains how to use it (in Japanese).
When it starts, the updater downloads the latest firmware from this repository by itself.
Earlier versions are in [Releases](https://github.com/aroerina/ucc3-firmware/releases).

## 更新できる本体 / Supported devices

> [!IMPORTANT]
> **ファームウェア v1.x.x の本体は、ファームウェアの更新に対応していません。**
> v1.x.x の本体には USB でファームウェアを更新する機能がないため、この更新ツールでは更新できません。
>
> **Devices with firmware v1.x.x do not support firmware updates.**
> They have no function to update the firmware over USB, so this updater cannot update them.

更新できるのは、ファームウェア v2.0.0 以降の本体です。
本体のファームウェアのバージョンは、電源を入れたときの起動画面に出ます。

Devices with firmware v2.0.0 or later can be updated.
The device shows its firmware version on the startup screen.

## このリポジトリにあるもの / Files in this repository

各 Release に、次のファイルを入れています。

| ファイル | 中身 |
|---|---|
| `UCC3-Firmware-Updater-Windows.zip` | 更新ツール(`ucc3-updater.exe`)と使い方 |
| `ucc3_app_r13_X.Y.Z.ucc3fw` | ファームウェア。更新ツールが使います |
| `latest.json`、`latest.json.sig` | ファームウェアの一覧と、その電子署名。更新ツールが、本物のファームウェアかどうかを確かめるのに使います |

Each release contains the following files.

| File | Contents |
|---|---|
| `UCC3-Firmware-Updater-Windows.zip` | The updater (`ucc3-updater.exe`) and how to use it |
| `ucc3_app_r13_X.Y.Z.ucc3fw` | The firmware, used by the updater |
| `latest.json`, `latest.json.sig` | The list of firmware and its digital signature. The updater uses them to check that the firmware is genuine |

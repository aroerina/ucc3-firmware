# ucc3-firmware

USB Cable Checker 3 のファームウェアと、ファームウェア更新ツール(Windows 用)の配布場所です。<br>
Firmware and the firmware updater (for Windows) for USB Cable Checker 3.

## ダウンロード / Download

最新の更新ツールは、次のリンクからダウンロードできます。<br>
Download the latest updater here:

**[UCC3-Firmware-Updater-Windows.zip](https://github.com/aroerina/ucc3-firmware/releases/latest/download/UCC3-Firmware-Updater-Windows.zip)**

zip を展開して `ucc3-updater.exe` を起動します。使い方は、zip に入っている `.txt` を読んでください。<br>
Unzip it and start `ucc3-updater.exe`. The `.txt` file in the zip explains how to use it (in Japanese).

更新ツールは起動したときに、ここにある最新のファームウェアを自動でダウンロードします。<br>
When it starts, the updater downloads the latest firmware from this repository by itself.

これまでの版は [Releases](https://github.com/aroerina/ucc3-firmware/releases) にあります。<br>
Earlier versions are in [Releases](https://github.com/aroerina/ucc3-firmware/releases).

## 更新できる本体 / Supported devices

> [!IMPORTANT]
> **ファームウェア v1.x.x の本体は、ファームウェアの更新に対応していません。**<br>
> **Devices with firmware v1.x.x do not support firmware updates.**
>
> v1.x.x の本体には USB でファームウェアを更新する機能がないため、この更新ツールでは更新できません。<br>
> They have no function to update the firmware over USB, so this updater cannot update them.

更新できるのは、ファームウェア v2.0.0 以降の本体です。<br>
Devices with firmware v2.0.0 or later can be updated.

本体のファームウェアのバージョンは、電源を入れたときの起動画面に出ます。<br>
The device shows its firmware version on the startup screen.

## このリポジトリにあるもの / Files in this repository

各 Release に、次のファイルを入れています。<br>
Each release contains the following files.

| ファイル / File | 中身 / Contents |
|---|---|
| `UCC3-Firmware-Updater-Windows.zip` | 更新ツール(`ucc3-updater.exe`)と使い方<br>The updater (`ucc3-updater.exe`) and how to use it |
| `ucc3_app_r13_X.Y.Z.ucc3fw` | ファームウェア。更新ツールが使います<br>The firmware, used by the updater |
| `latest.json`、`latest.json.sig` | ファームウェアの一覧と、その電子署名。更新ツールが、本物のファームウェアかどうかを確かめるのに使います<br>The list of firmware and its digital signature. The updater uses them to check that the firmware is genuine |

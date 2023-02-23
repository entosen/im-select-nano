========================
im-select-nano
========================

Macの入力ソースの現在値の取得、および、セットができるプログラム。

`im-select <https://github.com/daipeihust/im-select>`_ の代替として使用できる。

ビルド済みのバイナリファイルを含まず、Mac用のソースコードのみで構成される。

USAGE
===============

ビルド::

    # build
    % gcc -o im-select-nano -framework Foundation -framework Carbon main.m

    # 確認
    % ./im-select-nano

        com.apple.inputmethod.Kotoeri.RomajiTyping.Roman
        or
        com.apple.inputmethod.Kotoeri.RomajiTyping.Japanese


できあがった im-select-nano をPATHの通ったディレクトリに配置してください。

LICENSE
==============

This project is licensed under the MIT License, see the LICENSE.txt file for details

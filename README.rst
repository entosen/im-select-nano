========================
im-select-nano
========================

Macの入力ソースの現在値の取得、および、セットができるプログラム。

https://github.com/daipeihust/im-select をもとに、
ビルド済みのバイナリファイルを削除し、Mac用のソースコードだけを含む形にしたもの。

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

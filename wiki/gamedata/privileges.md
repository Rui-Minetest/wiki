---
title: 権限
date:
---

実装されている権限の一覧です。MinetestおよびMinetest Gameで利用できるもののみを掲載しています。

権限はプレイヤーの実行できる操作を管理する機能です。
コマンド実行などの操作で要求されます。
プレイヤーの権限を変更するには[grantコマンド](commands#grant)と[revokeコマンド](commands#revoke)を使用します。

- toc
{:toc}

# Minetest

## interact

ブロックの破壊や設置に必要な権限。
シングルプレイ時に自動的に与えられる。

## shout

チャットでの会話に必要な権限。
シングルプレイ時に自動的に与えられる。

## basic_privs

[interact](#interact)と[shout](#shout)を包括した権限。
basic_privs設定から含む権限を変更することが可能。
シングルプレイ時に自動的に与えられる。

## privs

権限の変更に必要な権限。
シングルプレイ時に自動的に与えられる。

## teleport

[teleportコマンド](commands#teleport)の実行に必要な権限。

## bring

[teleportコマンド](commands#teleport)を他のプレイヤーへ使用する場合に必要な権限。

## settime

[timeコマンド](commands#time)で時間を変更する場合に必要な権限。

## server

[setコマンド](commands#set)や[shutdownコマンド](commands#shutdown)などのサーバ操作に必要な権限。

## protection_bypass

ブロックの保護を回避するための権限。

## ban

[banコマンド](commands#ban)と[unbanコマンド](commands#unban)の実行に必要な権限。

## kick

[kickコマンド](commands#kick)の実行に必要な権限。

## give

[giveコマンド](commands#give)と[givemeコマンド](commands#giveme)の実行に必要な権限。

## password

[setpasswordコマンド](commands#setpassword)と[clearpasswordコマンド](commands#clearpassword)の実行に必要な権限。

## fly

飛行モードに必要な権限。

## fast

高速移動モードに必要な権限。

## noclip

飛行モード時のすり抜けに必要な権限。

## rollback

ロールバック操作に必要な権限。

# Minetest Game

## home

[homeコマンド](commands#home)と[sethomeコマンド](commands#sethome)の実行に必要な権限。
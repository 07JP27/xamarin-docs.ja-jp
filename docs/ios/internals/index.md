---
title: iOS の高度な概念と内部構造
description: このトピックでは、MonoTouch API デザイン、アセンブリと .NET 基本クラス ライブラリ (BCL) からのクラスおよび Visual Studio for Mac を Xcode の Interface Builder と Apple のツール チェーンと統合する方法を検索します。
ms.prod: xamarin
ms.assetid: 951713CD-D6AD-981C-A09E-4F2C98588D8B
ms.technology: xamarin-ios
author: bradumbaugh
ms.author: brumbaug
ms.date: 06/05/2017
ms.openlocfilehash: aca113448038df8b22eeb858acb48ee17a7809e2
ms.sourcegitcommit: aa9b9b203ab4cd6a6b4fd51e27d865e2abf582c1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2018
ms.locfileid: "39350863"
---
# <a name="ios-advanced-concepts-and-internals"></a>iOS の高度な概念と内部構造

_このトピックでは、MonoTouch API デザイン、アセンブリと .NET 基本クラス ライブラリ (BCL) からのクラスおよび Visual Studio for Mac を Xcode の Interface Builder と Apple のツール チェーンと統合する方法を検索します。_

##  <a name="api-designiosinternalsapi-designindexmd"></a>[API の設計](~/ios/internals/api-design/index.md)

API のバインドの背後にあるデザインの原則について説明します。

##  <a name="available-assembliescross-platforminternalsavailable-assembliesmd"></a>[使用できるアセンブリ](~/cross-platform/internals/available-assemblies.md)

使用可能なアセンブリと .NET 基本クラス ライブラリ (BCL) からのクラスを示します。

##  <a name="xib-code-generationiosinternalsxib-code-generationmd"></a>[XIB コードの生成](~/ios/internals/xib-code-generation.md)

また、Visual Studio for Mac と Xcode の Interface Builder を使用すると、UI の設計に Interface Builder を使用する方法についても説明します。

> [!IMPORTANT]
> このドキュメントには、Mac の Xcode の Interface Builder にのみ統合のための Visual Studio がについて説明します。 IOS Designer の詳細についてを参照してください、 [iOS Designer](~/ios/user-interface/designer/index.md)ドキュメント。

##  <a name="ios-architectureiosinternalsarchitecturemd"></a>[iOS のアーキテクチャ](~/ios/internals/architecture.md)

Xamarin.iOS アプリケーションでは、Mono 実行環境内で実行され、完全な事前の Time (AOT) コンパイルを使用して、ARM アセンブリ言語を c# コードをコンパイルします。 このガイドで低レベルでの Xamarin.iOS をについて説明します

##  <a name="objective-c-selectorsiosinternalsobjective-c-selectorsmd"></a>[OBJECTIVE-C セレクター](~/ios/internals/objective-c-selectors.md)

メモと OBJECTIVE-C セレクター (メソッド) を直接呼び出すために使用します。

##  <a name="limitationslimitationsmd"></a>[制限事項](limitations.md)

落とし穴と Xamarin.iOS で注意すべき制限します。
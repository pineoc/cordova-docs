---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

title: File
---

File
====

このオブジェクトは一つのファイルの属性を含みます。

プロパティー
----------

- __name:__ ファイルの名前を表します。 _(DOMString)_
- __fullPath:__ ファイルの名前を含むフルパスを表します。 _(DOMString)_
- __type:__ ファイルの mime type を表します。 _(DOMString)_
- __lastModifiedDate:__ ファイルの最終更新日時を表します。 _(Date)_
- __size:__ ファイルのサイズをバイトで表します。 _(long)_

詳細
-------

この `File` オブジェクトは一つのファイルの属性を含みます。 `[FileEntry](../fileentry/fileentry.html)` オブジェクトの __file__ メソッドを呼び出すことで、 File オブジェクトのインスタンスを取得できます。

サポートされているプラットフォーム
-------------------

- Android
- BlackBerry WebWorks (OS 5.0 以上)
- iOS
- Windows Phone 7 (Mango)

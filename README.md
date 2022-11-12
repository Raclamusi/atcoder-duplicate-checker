# Atcoder Duplicate Checker

AtCoder でコードを提出する時、過去に同じコードを提出していないかチェックし、同じコードがあった場合本当に提出するか確認します。  
これにより、コードをコピーしたつもりができていなくて、1つ前の問題のコードを貼り付け提出してしまうといったミスを防げます。

チェックは「自分の提出」ページの1ページ目の提出について行われます。
つまり、直近20回より前の提出は考慮されません。

When submitting code to AtCoder, this script checks to see if the same code has been submitted before, and if so, confirms that you are sure you want to submit it.  
This prevents mistakes such as thinking you have copied the code, but not having done so, and then pasting the code from the previous problem into the submission.

The check is made for submissions on the first page of the "My Submissions" page.
In other words, submissions prior to the most recent 20 will not be considered.

## インストール | Installation

Greasy Fork からインストールできます。

You can install this from Greasy Fork.

https://greasyfork.org/ja/scripts/454704-atcoder-duplicate-checker


# 魔法一覧

## 変更メソッド

Array.prototype.copyWithin() 配列内で配列内の連続した要素をコピーします。
Array.prototype.fill() 配列内の指定した開始位置から終了位置までの要素を固定値で埋めます。
Array.prototype.pop() 配列から最後の要素を取り除き、戻り値として返します。
Array.prototype.push() 配列の最後に 1 個以上の要素を追加し、新しい配列の長さを返します。
Array.prototype.reverse() 配列の要素の順番を逆転させます (最初の要素は最後に、最後の要素は最初になります)。
Array.prototype.shift() 配列から最初の要素を取り除き、その要素を返します。
Array.prototype.sort() 配列内で要素を整列し、配列を返します。
Array.prototype.splice() 配列に対して複数の要素を追加したり取り除いたりします。
Array.prototype.unshift() 配列の最初に 1 個以上の要素を追加し、配列の変更後の長さを返します。

## アクセサ メソッド
これらのメソッドは呼び出し対象の配列を書き換えず、配列を何らかの形で表したものを返します。

Array.prototype.concat() この配列に他の配列や値を結合して新しい配列を返します。
Array.prototype.includes() この配列が特定の要素を含むかどうか判定し、その結果を true または false で返します。
Array.prototype.indexOf() 指定された値と等しい値を持つ最初の (添字の一番小さい) 要素の添字を返します。見つからない場合、-1 を返します。
Array.prototype.join() 配列のすべての要素を結合した文字列を返します。
Array.prototype.lastIndexOf() 指定された値と等しい値を持つ最後の (添字の一番大きい) 要素の添字を返します。見つからない場合、-1 を返します。
Array.prototype.slice() 配列の一部を取り出して新しい配列として返します。
Array.prototype.toSource() 指定された配列を表す配列リテラルを返します。この値を使って新しい配列を作れます。Object.prototype.toSource() メソッドを上書きしています。
Array.prototype.toString() 配列とその要素を表す文字列を返します。Object.prototype.toString() メソッドを上書きしています。
Array.prototype.toLocaleString() 配列とその要素を表すロケールに従った文字列を返します。Object.prototype.toLocaleString() メソッドを上書きしています。

## 反復メソッド

Array.prototype.entries() 新しい Array Iterator オブジェクトを返します。このオブジェクトは、配列中の各インデックスに対する key/value ペアを保持しています。
Array.prototype.every() 指定したテスト関数を配列中のすべての要素が満たした場合に true を返します。
Array.prototype.filter() 指定したフィルタリング関数が true を返す、配列中の要素を格納した新しい配列を生成します。
Array.prototype.find() 指定したテスト関数を満たす、配列中の要素の値を返します。1 個も見つからない場合は undefined を返します。
Array.prototype.findIndex() 指定したテスト関数を満たす、配列中の要素のインデックスを返します。1 個も見つからない場合は -1 を返します。
Array.prototype.forEach() 配列中のそれぞれの要素について関数を呼び出します。
Array.prototype.keys() 新しい Array Iterator を返します。このオブジェクトは配列中の各インデックスのキーを保持します。
Array.prototype.map() 配列内のすべての要素に対して与えられた関数を呼び出し、その結果を格納した新しい配列を生成します。
Array.prototype.reduce() アキュムレータと配列内のすべての要素に対して (左から右の順で) 関数を適用し、単一の値に還元します。
Array.prototype.reduceRight() アキュムレータと配列内のすべての要素に対して (右から左の順で) 関数を適用し、単一の値に還元します。
Array.prototype.some() 指定したテスト関数を配列中の少なくとも 1 個の要素が満たした場合に true を返します。
Array.prototype.values() 新しい Array Iterator オブジェクトを返します。このオブジェクトは、配列中の各インデックスの値を保持します。
Array.prototype[@@iterator]() 新しい Array Iterator オブジェクトを返します。このオブジェクトは、配列中の各インデックスの値を保持します。
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc3Mzg1NzA3Nyw0OTc4MTg4MTBdfQ==
-->
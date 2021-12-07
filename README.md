#JavaScriptについて
変数と関数の命名ルール
・変数名に使ってもよい記号は_(アンダーバー)$(ドル）のみ
・変数名の１文字目に数字は使えない
・大文字と小文字は区別され、let ABC と let abc は別の変数となる
・変数名に予約語は使えない

変数のスコープ
・関数の中で宣言した変数はその関数の中でしか利用することができない。
　⇒変数のスコープという。変数を宣言した場所によって変数を呼び出せる範囲が変わる。
※スコープの適用外のところから変数を呼び出そうとするとエラーになる。

関数のメリット
ある機能を持った関数を後から何度でも呼び出すことができる。

予約語
変数名や関数名に使うことができない文字列のこと。
JavaScriptの命令ですでに使われているため、自分で変数名や関数名として宣言するとエラーとなる。↓
abstract	arguments	boolean	break	byte
case	catch	char	class	const
continue	debugger	default	delete	do
double	else	enum	eval	export
extends	false	final	finally	float
for	function	goto	if	implements
import	in	instanceof	int	interface
let	long	native	new	null
package	private	protected	public	return
short	static	super	switch	synchronized
this	throw	throws	transient	true
try	typeof	var	void	volatile
while	with	yield		
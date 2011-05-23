/**
 * Loggix_Plugin - Show Related Entry List
 *
 * @copyright Copyright (C) UP!
 * @author    hijiri
 * @link      http://tkns.homelinux.net/
 * @license   http://www.opensource.org/licenses/bsd-license.php  New BSD License
 * @since     2010.05.25
 * @version   11.5.23
 */

●関連記事を表示するプラグイン

■概略
このソフトウェアは、Loggixに投稿された記事から関連する記事を表示するプラグインです。

■詳細
Loggixで記事を投稿する際のタグを利用して共通するタグを持つ記事を検索して表示します。同様のタグを持つ記事の場合は新しい記事が優先されます。

デフォルトでは記事のPermlinkに関連記事を表示しますが、置換えのターゲット文字(標準では<!-- related -->)を編集すれば自由な個所へ関連記事を表示出来ます。

■インストール/アンインストール方法
インストール
    1./plugins/へshowRelatedEntryList.phpをアップロードします。必要であれば、表示するエントリ数や出力するHTMLを編集します。
    2./theme/permalink.htmlの関連記事を表示したい個所へ<!-- related -->を記述するか、記事を投稿する際に<!-- related -->を記述します。

アンインストール
    1./plugins/からshowRelatedEntryList.phpを削除します。
    2./theme/permalink.htmlへコードを追加した場合は追加したコードを削除します。

■使用方法
インストールすれば何もしなくても直ぐに適用されます。

■その他
単純に共通するタグを持つ記事をリストしますので、全く関連しない記事内容であっても共通するタグがあれば表示される可能性があります。

■サポート
作者多忙の為サポート出来ません。意見/感想はContactからご連絡ください。

■更新履歴
2011-05-23:PHP5.3.0でエラーが出ていた箇所を修正
2010-07-03:一部のエントリーがリストされないバグを修正
2010-06-11:公開
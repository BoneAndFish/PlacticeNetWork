
■ 通信サンプルプログラム

★はじめての通信プログラム
●実行ファイル
03\SocketSample\bin\SocketSample.exe		TCPサンプルプログラム
03\SocketSample\bin\SocketSample*.exe		UDPサンプルプログラム

●実行の仕方
Unity3D でプロジェクトファイルを起動してプログラム実行します。この時Consoleウインドウを表示してください。
Unity3D ではサーバ側で「Launch server」を選択してください。
クライアント側は実行ファイルを起動します。サーバ起動後、「Connect to server」を押してください。
クライアントのウインドウを閉じるとConsoleウインドウに"Hello, this is client."と表示されます。
メッセージが表示されれば通信が成功しています。


●サンプルプログラム
プロジェクトファイル：03\SocketSample\Assets\Scene\SocketSample.unity
プログラム：03\SocketSample\Assets\Script

SocketSampleTCP.cs		TCPソケットのサンプルプログラム
SocketSampleUDP.cs		UDPソケットのサンプルプログラム


★通信ライブラリ
●サンプルプログラム
プロジェクトファイル：03\NetworkLibrary\Assets\Scene\NetworkLibrary.unity
プログラム：03\NetworkLibrary\Assets\Script

LibrarySample.cs		ライブラリの動作確認プログラム
TransportTCP.cs			TCP通信を行う通信モジュール
TransportUDP.cs			UDP通信を行う通信モジュール
PacketQueue.cs			パケットデータをスレッド間で共有するためのバッファ
NetworkDef.cs			通信イベント関連の定義
			

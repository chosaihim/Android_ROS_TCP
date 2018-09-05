##Readme.txt

[ROS_ver4 file includes]
* CMakeLists.txt //컴파일 할 파일들과 옵션에 대한 정보
* include
* msg		//topic에 사용될 message파일
* package.xml
* src		//소스파일

	/msg
	* orders 	//안드로이드 상에서 사용자가 선택한 버튼 정보
	* workDone	//Robot에서 서버로 보내는 신호

	/src
	* order_publisher	//안드로이드 클라이언트의 신호를 받아들이는 c++서버, 
				//안드로이드에서 받은 신호를 subscriber로 보내고, subscriber에서 다시 신호를 보낼 때까지 대
	* order_subscriber	// Publisher에서 신호를 받은 후, 
				// 키보드 입력을 받아들이면 publisher로 Done 신호를 보낸다.


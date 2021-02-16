## BLACKWAN란?
BLACKWAN은 교육의 목적으로 Hideen-tear를 기반으로 만든 랜섬웨어 입니다.  
기본적으로 바탕화면의 있는 파일만 암호화 합니다.

## 기존 Hidden-tear랑 다른점
기존 Hidden-tear는 서버로 암호를 보낸다면, BLACKWAN은 서버로 암호를 보내지 않는다는 것입니다.  
또한 Hidden-tear는 .locked라는 확장자명으로 변경되지만, BLACKWAN 랜섬웨어는 랜덤 확장자 명으로 암호화하여 더욱더 복구화 하기 힘들게 합니다.

## 주의사항!
BLACKWAN은 교육의 목적으로 만들어진 랜섬웨어 입니다.  
이를 악용시 개발자는 책임지지 않습니다.

소스코드에는 Debug파일 또는, Releases파일이 존재할 수 있습니다.  
만약 위 2개의 파일이 있을시 안티 프로그램에서 랜섬웨어로 감지하여 파일을 모두 지울 수 있으니, 소스코드를 다운받고 격리파일에서 위 2개의 파일을 지운뒤 소스코드를 수정하십시오.

BLACKWAN 랜섬웨어는 기본적으로 바탕화면에 있는 파일만 암호화 합니다.  
다른 폴더에서도 암호화를 하고싶으면 소스코드에서 폴더의 위치를 바꾸십시오

## 복구하는법
같은 폴더에 있는 BLACKWAN-Decrypter를 실행하고 바탕화면에 있는 README.txt를 열고, 안에 있는 복구화 키를 복사후 붙여넣습니다.  
또한 확장자 명이 랜덤으로 변경된 것도 복사하여 붙여넣습니다.  
암호화 된 파일이 많을수록 시간이 오래 걸립니다.

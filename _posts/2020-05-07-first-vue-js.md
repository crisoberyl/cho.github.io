**vue.js 프로젝트** 만들려고 하는데 권한문제로 생성이안됨.

**atom 에디터에 terminal 플러그인 인스톨**했었음

모르겠고 **powershell 관리자 모드**로 실행해서 **ExecutionPolicy** 확인하니까
**restricted** 되어있었음
그래서
**Set-ExecutionPolicy unrestricted**
했더니 **unrestricted** 되어가지고
atom안에서 terminal 열어가지고 프로젝트 생성하니까 잘 되었음.

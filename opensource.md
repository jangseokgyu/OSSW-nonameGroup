---
layout: post
---
--------------------------
<div class="post">
  <h1 class="pageTitle">오픈소스의 사례들</h1>
		<ul>

시장규모 | 2006년 | 2007년 | 2008년 | 2009년 | 2010년 | 2011년
-------|-------|---------|--------|-------|---------|-----------
기업용 애플리케이션 | 29 | 42 | 62	| 94 | 131 | 172
기간계 SW | 156 | 199 | 252 | 308 | 382 | 462
---------------------------------
장점 | 단점
-----------|-----------------------
관리가 용의하다 | 전 단계가 완벽해야 오류가 없다.
체계적이다 | 중간결과라는 것 자체가 없다
요구사항이 적은 프로젝트에 적합하다 | 폭포를 거슬러 오를 수 없다.
----------------------------------------------
# 오늘날의 오픈소스 소프트웨어들
-------------------------
사실 마이크로소프트와 같은 사유소프트웨어 기업들이 지난 몇십년을 거의 지배해왔던 것은 사실이다. 프로그램을 개발해서 판다는 것을 하는 행위에는 어느 사업처럼 인간에게 있어 가장중요한 동기부여가 필요했다. 사유소프트웨어 개발은 길게 돈을 벌지는 못하더라도 적어도 오픈소스보다는 빨리 많은 돈을 벌게 해주었고 자본주의사회에서 금전동기부여는 효과적으로 사유소프트웨어 개발 시장의 크기를 늘리는 원동력이 되어왔다. 그러나 왜 지금에 와서 오픈소스가 이렇게도 중요해졌는가?

우선 기술의 발전이 한 개인이 따라잡을 수 없을 만큼 빨라졌음을 들 수 있겠다. 제한된 인원으로 고품질의 코드를 짠다는 것은 거대한 소프트웨어, 고난도의 소프트웨어 개발일 수록 불가능에 가까워졌다. 그렇기에 어쩔수 없어서라도 코드를 공개하고 GPL라이선스에 따라 개발을 진행하는 것이 유일한, 혹은 가장 효율적인 수단이된 것이다. 설령 공개된 소스가 기업에서 사용하는 것에 못미치는 수준이더라도 수많은 이의 손을 거치게되면서 금방 기업의 그것을 능가하는 소스가 되곤 한다.

대표적인 예로 텐서플로우가 있을 수 있겠다. 2015년 공개된이후 계속해서 발전하고 있고 딥러닝과 머신러닝 기술의 첨병역할을 하고 있다. 그외의 오픈소스 소프트웨어는 아래와 같은 것들이 있다.
---------------------------------
## 시스템 소프트웨어
---------------------
1. LINUX : 너무나 유명한 OS이다. 모바일,태블릿,콘솔에서 슈퍼컴퓨터에까지 사용된다. http://www.linux.org
2. Free BSD : AT&T의 유닉스에서 개발되어 버클리 대학을 거쳐 발전된 무료 유닉스 운영체제이다. x86플랫폼을 중심으로 움직인다.http://www.freebsd.org
3. NET BSD : BSD의 오픈소스버전으로 이식성에 초점을 두고 아직도 개발되고 있다.http://www.net-bsd.org
4. Open BSD : net bsd에서 branch되어 나온 오픈소스이다. 역시 이식성에 중점을 두고 개발중이다.http://www.openbsd.org
5. XEN : virtual box같은 가상 머신 모니터 오픈소스이다.http://wwww.xen.org
-------------------------
### 소프트웨어 개발
-------------------
1. GCC : GNU Compiler Collection의 약자로 다양한 언어를 컴파일 하기위한 컴파일러 http://gcc.gnu.org
2. Python : 코드 가독성을 극단적으로 중시하는 프로그래밍 언어 http://www.Python.org
3. PHP : HTML과 호환이 잘되는 스크립트 언어 http://www.php.net
4. Ruby : 일본인이 만든 자연스러운 문법을 가진 언어 http://www.ruby-lang.org/en/
5. Java Techonology : 썬 시스템에서 개발한 프로그래밍언어 http://www.oracle.com/technetwork/java
6. Scala : 우아하고 안정적인 방법으로 일반적인 패턴을 표현하기 위해 설께된 언어 http://www.scala-lang.org
7. Erlang : 에릭슨에 의해 고안된 프로그래밍언어 http://www.erlang.org
8. Perl : 기능 중심의 포르그래밍언어 http://www.Perl.org
9. Lua : 경량화된 스크립트 언어 http://www.lua.org
10. Scumm VM : 어드벤처 게임을 위한 플랫폼 인터프리터 http://www.ScummVM.org
11.Tcl/TK : Tool Command Language의 약자로 GUI를 만드는데 탁월한 언어이다. http://www.tcl.tk
---------------------
## 응용 소프트웨어
-----------------
### 데스크탑 환경
-------------------
1. Gnome : 리눅스와 유닉스를 실행하기위한 데스크탑 환경이다. 1999년 릴리스했다. http://www.gnome.org
2. X11 : 거의 X 윈도우로 불리며 GUI를 제공한다.http://www.x.org/wiki
3. KDE : x11같은 GUI환경을 제공한다.http://www.kde.org
----------------
### 데이터베이스
---------------
1. MySQL : 관계형 데이터베이스 관리시스템이다. 나중에 저작자가 MySQL 저작권을 가진 회사를 세워서 GPL라이선스와 사유 제품 라이선스 두가지를 가지고 있는 특이한 오픈소스이다.http://www.mysql.com
2. PostgreSQL : 객체관계형 데이터베이스 관리시스템이다. PostrgreSQL 라이센스를 갖고 있다.http://www.postgresql.org
3. HSQLDB : 자바언어로 코딩한 SQL 관계형 데이터베이스 엔진이다. GUI인터페이스도 지원한다.http://hsqldb.org
4. SQLite : SQL을 구현하는 라이브러리 http://www.sqlite.org

### 웹, 애플리케이션 서버

1. Apache HTTP server : 확장성 좋은 오픈소스이다. 릴리스되어 널리 쓰여서 덩달아 리눅스가 널리 퍼져 쓰이게된 킬러 어플리케이션이되었다. http://httpd.apache.org
2. Jakarta Tomcat : 자바 서플릿, JSP 기술을 지원하는 오픈소스이다. http://tomcat.apache.org
3. JBOSS : J2EE기반 자유 소프트웨어 애플리케이션 서버이다. http://www.jboss.org
4. AWStats : GUI환경에서 스트리밍을 위한 강력한 도구.http://awstats.sourceforge.net

### 시스템 도구

1. Wireshark : 네트워크 문제해결, 분석, 소프트웨어 Protocal 개발, 교육을 위한 오픈소스 패킷 분석기 http://www.wireshark.org
2. Nagios : IT 모니터링 관리 시스템 http://www.nagios.org
3. phpMyAdmin : 웹을 통해 MySQL 관리가 가능한 PHP로 작성된 도구 http://www.phpmyadmin.net

### 이메일

1. Fetchmail : 에릭 레이먼드가 개발한 유명한 오픈소스 소프트웨어이다. 유닉스를 위한 메일 도구이다. http://www.fetchmail.info
2. Sendmail : 다양한 메일 전송을 지원하는 Agent이다. http://www.sendmail.org
3. Postfix : 전자 메일을 라우팅하는 빠른 오픈소스 전송 소프트웨어 http://www.postfix.org
4. SpamAssassin : 스팸 필터링 소프트웨어 http://spamassassin.apache.org

### 네트워킹 인프라

1. BIND : 널리 사용되고 있는 DNS 소프트웨어 http://www.isc.org/software/bind
2. Zenoss : 기업용 네트워크 & 시스템 관리 어플리케이션 http://www.zenoss.com

### 보안

1. Clonezilla : 디스크 파티션 및 클론 시스템  http://www.clonezilla.org
2. Putty : 사이먼이 개발한 SSH&텔넷 클라이언트 http://www.putty.org
3. TrueCrypt : 자유 오픈소스 디스크 압축도구 http://truecrypt.org
4. WinSCP : 컴퓨터 통신 때의 안전한 파일 전송을 위한 윈동우용 오픈소스 http://winscp.net/eng/index.php

### 데스크탑

1. Mosaic : 1993년 개발된 웹브라우저이다. 인터넷 초기에 중심적인 역할을 했다. 다만 상업용을 위해서는 별도로 계약해야 쓸 수 있다. 그외 교육용,사업을 위한 사용에는 별도의 라이센스가 필요하지 않다. http://www.ncsa.illinois.edu
2. FireFox : Mozilla Application에 포함된 오픈소스 웹브라우저이다. http://www.mozilla.org
3. ThunderBird : Mozilla가 개발한 이메일 및 뉴스 클라이언트 http://www.mozilla.org
4. OpenOffice : 워드 프로세서, 스프레드 시트, 데이터베이스 등을 가진 오픈소스, 마이크로소프트의 office에 대항하는 소프트웨어다. http://www.openoffice.org
5. Evolution : Gnome 데스크탑 사용자를 위한 메일 주소록 일정 프로그램 http://projects.gnome.org/evolution
6. Gaim : Yahoo,MSN 등에 한꺼번에 연결할 수 있는 채팅 클라이언트 http://www.pidgin.im
7. 7zip : 다양한 포맷을 지원하는 압축도구 http://www.7-zip.org
8. KeePass Password Safe : 윈도우를 위한 패스워드 관리자. http://kepass.info

### 엔터테이먼트

1. Mumble : 게이머를 위한 보이스 채팅 도구 http://mumble.sourceforge.net
2. Mediainfo : 멀티미디어 파일을 위한 도구 http://mediainfo.sourceforge.net
3. Media Player Classic : 윈도우를 위한 오디오 & 비디오 플레이어 http://mpc-hc.sourceforge.net
4. Bittorrent : 유명한 P2P 파일공유 클라이언트 http://www.bittorrent.com
5. VLC 플레이어 : 동영상,오디오, 웹스트리밍,TV수신카드 플레이를 위한 플레이어 http://www.videolan.org/vlc
6. AUdacity : 맥, window,linux 등 다양한 OS에서 사용가능한 오픈소스 사운드 편집 프로그램http://audacity.sourceforge.net

### 그래픽

1. Inkscape : W3C를 표준으로 하는 벡터 그래픽 편집기 http://www.inkscape.org
2. Gnuplot : 다양한 OS를 위한 명령어 기반 그래픽 도구 http://www.gnuplot.info
3. GMT : 지형을 그리기 위한 도구 http://gmt.soest.ha-waii.edu
4. GraphViz : 그래프를 그리기 위한 도구 http://www.graphviz.org
5. GIMP : 사진 편집, 압축을 위한 소프트웨어 http://www.gimp.org
6. iReport : 유명한 시각적 레포팅 도구 http://www.jasperforge.org/projects/ireport
7. FreeMind : 자바로 코딩한 아이디어 마인드 맵을 그리기위한 소프트웨어 http://freemind.sourceforge.net

### 교육

1. Scratch : 단순한 GUI로 코딩의 개념을 가르치기 위한 어플 http://scratch.mit.edu
2. Tux Paint : 유아를 위한 그리기 프로그램 http://tuxpaint.org
3. Moodle : 이러닝 컨텐츠 관리 시스템 http://moodle.org
4. Etoys : 직관적인 방식의 프로그래밍을 통해 코딩 교육을 위한 프로그램 http://www.squeakland.org

### 공학

1. R : 통계 계산 및 그래픽화를 위한 도구 아주 많이 쓰인다. http://www.r-project.org
2. GNU Octave : 초등학생에게 수학을 가르치기 위한 방정식 공식 프로그램 http://www.gnu.org/software/octave

### 출판

1. TeX : 모든 컴퓨터에서 동일한 고품질의 도서를 만들기위해 고안되었다. http://www.tug.org
2. DockBook:기술 문서를 위한 마크업 언어. 마크 다운의 아버지뻘이다.http://www.docbook.org
3. TCPDF : PDF문서를 생성하기 위한 오픈소스 PHP 클래스http://www.tecnick.com/public/code/cp_dpage/php?aiocp_dp=tcpdf
4. TXC : 윈도우 기반 환경에서 LaTeX 문서를 생성하기 위해 만들어졌다. http://www.texnic-center.org

### 에디터

1. VIM : 유닉스 텍스트 에디터로 많이 쓰인다. http://www.vim.org
2. Notepad ++ : 윈도우 노트패드를 대체하기 위한 에디터 http://notepad-plus.sourceforge.net
3. GNU Emacs : 확장, 커스터마이징이 가능한 텍스트 에디터 http://www.gnu.org/software/emacs

### VCS

1. CVS : 초기에 많이 쓰인 개발 컨트롤 http://www.nongnu.org/cvs
2. Apache Subversion : CVS와 비슷한 개발 버전컨트롤 http://subversion.apache.org
3. GIT : 가장 많이 쓰이는 VCS로 속도가 아주 빠른 것이 특징이다. http://git-scm.com
4. Mercurial : 분산 버전 관리도구로 직관적인 인터페이스가 특징 http://mercurial.selenic.com

### IDE

1. eclipse : java 통합개발환경으로 IBM에서 만들어졌다가 오픈소스로 릴리스되었다. http://www.Eclipse.org
2. NetBeans : 개발자를 위한 플랫폼을 지원한다. http://netbeans.org
3. Apache Ant : 빌드 프로세스를 자동화 하기 위한 도구 http://ant.apache.org

### frame work

1.Simply Ajax and Mobile : java로 작성된 웹 애플리케이션 프레임워크, 질 좋은 GUI를 쉽게 만들 수 있다. http://www.zkoss.org
2.Mono : 클로스 플랫폼 어플의 쉬운 작성을 위해 만든 플랫폼 http://www.mono-project.com/Main_Page
3.Qt : GUI 소프트웨어 개발을 위한 프레임워크 http://qt.nokia.com
4.Ruby on Rails : 애자일 방식으로 사용될 목적으로 만들어진 프레임 워크 http://www.rubyonrails.org

### 컨텐츠 관리 시스템

1.Drupal : 개인 블로그 및 대형 회사 사이트 작성에 많이 사용된다. http://drupal.org
2.WordPress : PHP, MySQL을 이용하는 블로그 애플리케이션이다.인기있는 CMS http://wordpress.org
3.Joomla : 쉬운 운용방법을 기반으로 웹사이트 구축을 할 수 있게 한다. http://www.Joomla.org
4.Arianne : RPG게임 서버및 클라이언트를 생성하기위한 멀티플레이어 온라인 엔진 http://arianne.sf.net
5.Media Wiki : PHP로 작성된 자유 소프트웨어 패키지로 그 유명한 WIKIPEDIA에 사용되었다. http://www.mediawiki.org

### 비즈니스 어플리케이션

1.Compiere : 중소기업을 위한 ERP & CRM 솔루션 http://www.Compiere.com
2.Open ERP : 거의 완벽한 ERP & CRM 시스템이다. 데이터베이스,서버,클라이언트를 계층구조로한다. http://www/OpenERP.com
3.PostBooks ERP : 중소기업을 위한 회계 오픈소스 ERP http://postbooks.sourceforge.net
4.Openbravo ERP : 종합적인 웹 ERP 솔루션 http://www.Open-bravo.com
5.J Stock : 많이 쓰이는 무료 주식시장 소프트웨어 http://jstock.source-forge.net
<blockquote>출처 : [네이버](https://naver.com)</blockquote>

</ul>
</div>

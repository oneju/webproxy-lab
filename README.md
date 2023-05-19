####################################################################
## CS:APP Proxy Lab
## Student Source Files
####################################################################
- This directory contains the files you will need for the CS:APP Proxy
Lab.

proxy.c
csapp.h
csapp.c

    These are starter files.  csapp.c and csapp.h are described in
    your textbook.
    You may make any changes you like to these files.  And you may
    create and handin any additional files you like.
    Please use `port-for-user.pl’ or ‘free-port.sh’ to generate
    unique ports for your proxy or tiny server.
Makefile

    This is the makefile that builds the proxy program.  Type “make”
    to build your solution, or “make clean” followed by “make” for a
    fresh build.
    Type “make handin” to create the tarfile that you will be handing
    in. You can modify it any way you like. Your instructor will use your
    Makefile to build your proxy from source.

port-for-user.pl

    Generates a random port for a particular user
    usage: ./port-for-user.pl <userID>
free-port.sh

    Handy script that identifies an unused TCP port that you can use
    for your proxy or tiny.
    usage: ./free-port.sh
driver.sh

    The autograder for Basic, Concurrency, and Cache.
    usage: ./driver.sh
nop-server.py

    helper for the autograder.
tiny

    Tiny Web server from the CS:APP text
---
이 디렉토리는 CS:APP 프록시 랩에 필요한 파일들을 담고 있습니다.

proxy.c, csapp.h, csapp.c

    이들은 시작 파일입니다. csapp.c와 csapp.h는 교재에서 설명됩니다.
    이 파일들에 원하는 대로 변경을 가할 수 있습니다. 또한 필요한 추가 파일을 만들어 제출할 수도 있습니다.
    `port-for-user.pl` 혹은 ‘free-port.sh’를 사용하여 프록시 또는 tiny 서버에 대한 고유한 포트를 생성해주세요.
Makefile

    이것은 프록시 프로그램을 만드는 메이크파일입니다. “make”를 입력하여 솔루션을 빌드하거나, “make clean” 다음에 “make”를 입력하여 새로 빌드할 수 있습니다.
    “make handin”을 입력하면 제출할 tarfile을 생성합니다. 원하는 대로 수정할 수 있습니다. 담당 교수님은 이 Makefile을 사용해 소스로부터 프록시를 빌드할 것입니다.
port-for-user.pl

    특정 사용자를 위한 임의의 포트를 생성합니다.
    사용법: ./port-for-user.pl <사용자ID>
free-port.sh

    프록시나 tiny 서버에 사용할 수 있는 사용하지 않는 TCP 포트를 찾아주는 유용한 스크립트입니다.
    사용법: ./free-port.sh
driver.sh

    Basic, Concurrency, Cache에 대한 자동 채점기입니다.
    사용법: ./driver.sh
nop-server.py

    자동 채점 도우미입니다.
tiny

    CS:APP 교재에서 설명하는 작은 웹 서버입니다.
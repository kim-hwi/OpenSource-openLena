## <img src="docs/images/readme_lena_ctl_head.png" width="800"> [![Github Maven Repository Upload](https://github.com/OpenLENA/lena-ctl/actions/workflows/gh-mvn-upload.yml/badge.svg)](https://github.com/OpenLENA/lena-ctl/actions/workflows/gh-mvn-upload.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=OpenLENA_lena-ctl&metric=alert_status)](https://sonarcloud.io/dashboard?id=OpenLENA_lena-ctl) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=OpenLENA_lena-ctl&metric=coverage)](https://sonarcloud.io/dashboard?id=OpenLENA_lena-ctl)

Cancel changes

# OpenSourceSW_Project

## git-action과 SonarCloud를 이용한 coverege확인

- git-action이란?
 
 소프트웨어 workflow를 자동화할 수 있도록 도와주는 도구이다. 해당 프로젝트에선 sonarcloud와 연동하는데 사용하였다.

- sonarcloud란?
  
 코드품질을 확인할 수 있는 툴이며, 공개되어있는 프로젝트에 한해서 무료로 이용이 가능하다.

- coverege란?
  
 소프트웨어 테스트, 품질과 연관이 있으며 해당 코드가 얼마나 커버되어있는지(테스트해보았는지)를 나타내는 지표이다.

- 프로젝트 의의

 프로젝트에서 코드품질은 상당히 중요한 부분이다. 코드품질에 따라 코드안정성, 확장성 등도 결정이 된다. 코드의 품질이 좋고 나쁨을 개발자 스스로 인지하기 어려운것이 사실이고, 이를 도와주는 툴이 있다면 이를 활용하여 코드품질을 개선하고, 좋은 프로그래밍 습관을 기를 수 있다.  
이를 도와주는 다양한 툴이 있지만, 이 프로젝트에선 SonarCloud를 선택하였다. 그 이유는 로컬에 설치할 필요 없이 cloud상에서 코드품질을 확인할 수 있고, git-action에 대해서도 학습할 수 있기 때문이다. 또한 오픈소스로 프로젝트를 진행하게 되며 왜 오픈소스가 중요한지 더욱 느낄 수 있다고 생각하였기 때문에 해당 툴을 선택하였다.  











This is the home of the LENA Ctl.
LENA Ctl help to install servers easily by offering command line interface in LENA.

The feature of LENA Ctl : 

+ Installation : Create, Delete and Clone server. Don't need to type in much things when create server, just required server name and service port.
  Clone server is so useful when you wanna save the status of the server right away.
 
+ Execution : Start, Stop server. You can check the server status just with a command "ps". Just in case, service request is under abnomal status and you need to
              restart the server forcely. Use the command "force restart server_id". 

+ Monitoring : It is possible to capture heap and thread dump using LENA which means that, you don't need to memorize complicated commands like jmap.
               just do that with simple command of LENA.

## Installation and Getting Started
You can get a [installation guide](https://github.com/OpenLENA/lena-ctl/wiki/Installation-Guide).

## Getting Help
If you are having some trouble with LENA? Contact us the way you want.
+ Check the [reference documentation](https://github.com/OpenLENA/lena-ctl/wiki).
+ Notify us the problem by using [GitHub's Issue](https://github.com/OpenLENA/lena-ctl/issues/new).
+ Feel free to join our [community](https://groups.google.com/g/lena-oe) and ask that to us.

## Reporting Issues
We use GitHub's integrated issue tracking system to record bugs and other issues. Following are recommendations to keep the rule for reporing issues.
+ Check what the issue you found out is already [recorded](https://github.com/OpenLENA/lena-ctl/issues) or not.
+ If there is nothing, [Create issues](https://github.com/OpenLENA/lena-ctl/issues/new).
+ Keep the rule for commit message.
+ If possible, try to create a test-case.

## Release
LENA will be released every each quarter. You can get [released files](https://github.com/OpenLENA/lena-ctl/releases) and check what is changed in [release note](https://github.com/OpenLENA/lena-ctl/releases).

## Roadmap
You can find a roadmap of LENA Ctl [here](https://github.com/OpenLENA/lena-ctl/wiki/2021-Roadmap).

## Community
[LENA Community](https://groups.google.com/g/openlena)

## License
LENA Ctl is Open Source software released under the Apache 2.0 license.


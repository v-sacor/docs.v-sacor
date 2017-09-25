## <a name="microsoft-open-source-code-of-conduct"></a>Microsoft 오픈 소스 준수 사항

이 프로젝트에는 [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/)(Microsoft 오픈 소스 준수 사항)이 적용됩니다.
자세한 내용은 [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)(준수 사항 FAQ)를 참조하거나 [opencode@microsoft.com](mailto:opencode@microsoft.com)에 추가 질문 또는 의견을 알려주세요.

## <a name="contribute-to-azure-technical-documentation"></a>Azure 기술 문서에 참가
Microsoft에서는 Microsoft 커뮤니티(사용자, 고객, 파트너, 핵심 Azure 제품 팀 외의 Microsoft 직원 등)와 핵심 Azure 제품 팀에서 근무하는 직원의 참가를 환영합니다. 참가 방법은 참가자가 누구인가에 따라 달라집니다.

* **커뮤니티 - 부분 업데이트**: 친절한 마음에서 부분 업데이트에 참가하는 경우 이 리포지토리에서 문서를 찾거나 [https://docs.microsoft.com/azure](https://docs.microsoft.com/azure)에서 문서를 찾아 **편집** 링크를 클릭하여 문서의 GitHub 원본으로 이동할 수 있습니다. 그런 다음 GitHub UI를 사용하여 업데이트합니다. 또는 리포지토리를 분기하고 분기에서 업데이트를 제출해도 됩니다.

* **커뮤니티 - 새 문서**: Azure 커뮤니티의 일원이고 새 문서를 만들려는 경우 공용 및 개인 리포지토리의 작업을 조합하여 새 콘텐츠를 가져오려면 직원과 협력해야 합니다.

* **직원**: Azure 서비스에 대한 제품 팀의 테크니컬 라이터, 프로그램 관리자 또는 개발자인 경우 기술 문서에 참가하거나 기술 문서를 작성하는 것이 본인의 직무인 경우 개인 리포지토리(https://github.com/MicrosoftDocs/azure-docs-pr)를 사용해야 합니다. 기존 문서의 많은 부분을 변경하거나, 이미지를 추가 또는 변경하거나, 새 문서에 참가하는 경우 이 리포지토리를 분기하고 Markdown 편집기인 Git Bash를 설치하고 몇 가지 Git 명령을 배워야 합니다. 자세한 내용은 [내부 참가자 가이드](https://review.docs.microsoft.com/en-us/help/contribute/?branch=master)를 참조하세요.


## <a name="about-your-contributions-to-azure-content"></a>Azure 콘텐츠에 참가 방법
### <a name="minor-corrections"></a>사소한 수정
이 리포지토리의 설명서 및 코드 예제에 대해 제출한 사소한 수정 또는 확인 내용은 [docs.microsoft.com 사용 약관](https://docs.microsoft.com/legal/termsofuse)에서 다룹니다.

### <a name="larger-submissions"></a>대규모 제출
설명서 및 코드 예제에 대한 새롭거나 중요한 변경 내용을 통해 끌어오기 요청을 제출하면, Microsoft 직원이 아닌 경우 온라인 참가 사용권 계약(CLA)을 제출하도록 요청하는 GitHub의 설명이 전송됩니다. 온라인 양식 작성을 먼저 완료해야 Microsoft에서 끌어오기 요청을 수락할 수 있습니다.

## <a name="tools-and-setup"></a>도구 및 설정
커뮤니티 참가자는 GitHub UI를 사용하거나 리포지토리를 분기하여 참가할 수 있습니다. 직원이 기술 문서 집합에 참가하는 방법에 대한 자세한 내용을 알아보려면 [내부 참가자 가이드](https://review.docs.microsoft.com/en-us/help/contribute/?branch=master) 를 방문해야 합니다.

## <a name="repository-organization"></a>리포지토리 조직
azure-docs 리포지토리의 콘텐츠는 https://docs.microsoft.com/azure에 있는 설명서의 구성을 따릅니다. 이 리포지토리에는 두 개의 루트 폴더가 포함됩니다. 이 리포지토리에는 두 개의 루트 폴더가 포함됩니다.

### <a name="articles"></a>\articles
*\articles* 폴더는 *.md* 확장명의 markdown 파일 형식의 설명서를 포함합니다. 일반적으로 문서는 Azure 서비스별로 그룹화됩니다.

*\articles* 폴더는 루트 디렉터리 문서 미디어 파일에 대한 *\media* 폴더를 포함하며 이 폴더 내에는 각 문서에 대한 이미지가 담긴 하위 폴더가 있습니다.  서비스 폴더는 각 서비스 폴더 내에서 문서에 대한 별도의 미디어 폴더를 포함합니다. 문서 이미지 폴더는 *.md* 파일 확장을 뺀 문서 파일과 이름이 동일합니다.

### <a name="includes"></a>\includes
하나 이상의 문서에 포함될 재사용 가능한 콘텐츠 섹션을 만들 수 있습니다. 

## <a name="how-to-use-markdown-to-format-your-topic"></a>항목의 서식을 지정하는 Markdown을 사용하는 방법
이 리포지토리의 모든 문서는 GitHub 버전의 Markdown을 사용합니다.  다음은 리소스 목록입니다.

* [Markdown 기본 사항](https://help.github.com/articles/markdown-basics/)
* [인쇄 가능한 Markdown 치트 시트](./contributor-guide/media/documents/markdown-cheatsheet.pdf?raw=true)


## <a name="labels"></a>레이블
공용 azure-docs 리포지토리에서는 당사가 끌어오기 요청 워크플로를 관리하고 끌어오기 요청에 대한 진행 상황을 알리는 데 도움을 주기 위해 끌어오기 요청에 자동화된 레이블이 할당됩니다.

* 참가 사용권 계약 관련
  * cla-not-required: 변경 내용이 비교적 사소하며 CLA 서명이 필요하지 않습니다.
  * cla-required: 변경 범위가 비교적 크며 CLA 서명이 필요합니다.
  * cla-signed: 참여자가 CLA에 서명했으므로 끌어오기 요청이 검토 단계로 진행될 수 있습니다.
* 작성자에게 변경 내용 전송: 작성자에게 보류 중인 끌어오기 요청에 대해 알렸습니다.
* ready-to-merge: 끌어오기 요청 검토 팀에서 검토할 준비가 되었습니다.


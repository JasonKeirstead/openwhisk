---

copyright:
  years: 2016, 2018
lastupdated: "2018-07-17"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}
{:tip: .tip}

# {{site.data.keyword.conversationshort}} 패키지 

{{site.data.keyword.conversationfull}} 서비스는 머신 러닝, 자연어 이해 및 통합 대화 도구를 결합하여 앱과 사용자 간의 대화 플로우를 작성합니다.
{: shortdesc}

{{site.data.keyword.conversationshort}} 패키지에는 다음 엔티티가 포함되어 있습니다. 엔티티 이름을 클릭하여 {{site.data.keyword.conversationshort}} API 참조서의 추가 세부사항을 찾을 수 있습니다. 

|엔티티 |유형 |매개변수 |설명 |
| --- | --- | --- | --- |
| [`assistant-v1`](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html) |패키지 | username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,  |{{site.data.keyword.conversationshort}} 서비스 관련 작업을 수행합니다. |
| [message](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#message) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,    input, alternate_intents, context, entities, intents, output,     nodes_visited_details,  |사용자 입력에 대한 응답을 가져옵니다. |
| [create-workspace](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-workspace) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,   name, description, language, intents, entities, dialog_nodes, counterexamples, metadata, learning_opt_out,  |작업공간을 작성합니다. |
| [delete-workspace](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-workspace) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,  |작업공간을 삭제합니다. |
| [get-workspace](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-workspace) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     export,     include_audit,  |작업공간에 대한 정보를 가져옵니다. |
| [list-workspaces](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-workspaces) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    page_limit,     include_count,     sort,     cursor,     include_audit,  |작업공간을 나열합니다. |
| [update-workspace](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-workspace) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,    name, description, language, intents, entities, dialog_nodes, counterexamples, metadata, learning_opt_out,     append,  |작업공간을 업데이트합니다. |
| [create-intent](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-intent) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,    intent, description, examples,  |의도를 작성합니다. |
| [delete-intent](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-intent) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,  |의도를 삭제합니다. |
| [get-intent](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-intent) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,     export,     include_audit,  |의도에 대한 정보를 가져옵니다. |
| [list-intents](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-intents) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     export,     page_limit,     include_count,     sort,     cursor,     include_audit,  |의도를 나열합니다. |
| [update-intent](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-intent) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,    new_intent, new_description, new_examples,  |의도를 업데이트합니다. |
| [create-example](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-example) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,    text,  |사용자 입력 예제를 작성합니다. |
| [delete-example](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-example) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,     text,  |사용자 입력 예제를 삭제합니다. |
| [get-example](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-example) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,     text,     include_audit,  |사용자 입력 예제에 대한 정보를 가져옵니다. |
| [list-examples](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-examples) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,     page_limit,     include_count,     sort,     cursor,     include_audit,  |사용자 입력 예제를 나열합니다. |
| [update-example](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-example) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     intent,     text,    new_text,  |사용자 입력 예제를 업데이트합니다. |
| [create-counterexample](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-counterexample) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,    text,  |반증을 작성합니다. |
| [delete-counterexample](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-counterexample) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     text,  |반증을 삭제합니다. |
| [get-counterexample](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-counterexample) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     text,     include_audit,  |반증에 대한 정보를 가져옵니다. |
| [list-counterexamples](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-counterexamples) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     page_limit,     include_count,     sort,     cursor,     include_audit,  |반증을 나열합니다. |
| [update-counterexample](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-counterexample) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     text,    new_text,  |반증을 업데이트합니다. |
| [create-entity](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-entity) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,    entity, description, metadata, values, fuzzy_match,  |엔티티를 작성합니다. |
| [delete-entity](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-entity) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,  |엔티티를 삭제합니다. |
| [get-entity](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-entity) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     export,     include_audit,  |엔티티에 대한 정보를 가져옵니다. |
| [list-entities](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-entities) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     export,     page_limit,     include_count,     sort,     cursor,     include_audit,  |엔티티를 나열합니다. |
| [update-entity](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-entity) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,    new_entity, new_description, new_metadata, new_fuzzy_match, new_values,  |엔티티를 업데이트합니다. |
| [create-value](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-value) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,    value, metadata, synonyms, patterns, value_type,  |엔티티 값을 추가합니다. |
| [delete-value](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-value) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,  |엔티티 값을 삭제합니다. |
| [get-value](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-value) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,     export,     include_audit,  |엔티티 값을 가져옵니다. |
| [list-values](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-values) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     export,     page_limit,     include_count,     sort,     cursor,     include_audit,  |엔티티 값을 나열합니다. |
| [update-value](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-value) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,    new_value, new_metadata, new_type, new_synonyms, new_patterns,  |엔티티 값을 업데이트합니다. |
| [create-synonym](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-synonym) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,    synonym,  |엔티티 값 동의어를 추가합니다. |
| [delete-synonym](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-synonym) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,    synonym,  |엔티티 값 동의어를 삭제합니다. |
| [get-synonym](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-synonym) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,     synonym,     include_audit,  |엔티티 값 동의어를 가져옵니다. |
| [list-synonyms](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-synonyms) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,     page_limit,     include_count,     sort,     cursor,     include_audit,  |엔티티 값 동의어를 나열합니다. |
| [update-synonym](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-synonym) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     entity,     value,     synonym,    new_synonym,  |엔티티 값 동의어를 업데이트합니다. |
| [create-dialog-node](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#create-dialog-node) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,    dialog_node, description, conditions, parent, previous_sibling, output, context, metadata, next_step, actions, title, node_type, event_name, variable, digress_in, digress_out, digress_out_slots,  |대화 상자 노드를 작성합니다. |
| [delete-dialog-node](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-dialog-node) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     dialog_node,  |대화 상자 노드를 삭제합니다. |
| [get-dialog-node](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#get-dialog-node) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     dialog_node,     include_audit,  |대화 상자 노드를 가져옵니다. |
| [list-dialog-nodes](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-dialog-nodes) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     page_limit,     include_count,     sort,     cursor,     include_audit,  |대화 상자 노드를 나열합니다. |
| [update-dialog-node](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#update-dialog-node) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     dialog_node,    new_dialog_node, new_description, new_conditions, new_parent, new_previous_sibling, new_output, new_context, new_metadata, new_next_step, new_title, new_type, new_event_name, new_variable, new_actions, new_digress_in, new_digress_out, new_digress_out_slots,  |대화 상자 노드를 업데이트합니다. |
| [list-all-logs](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-all-logs) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    filter,     sort,     page_limit,     cursor,  |모든 작업공간의 로그 이벤트를 나열합니다. |
| [list-logs](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#list-logs) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    workspace_id,     sort,     filter,     page_limit,     cursor,  |작업공간의 로그 이벤트를 나열합니다. |
| [delete-user-data](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html?curl#delete-user-data) |액션 |  username, password,  iam_access_token, iam_apikey, iam_url,  headers, headers[X-Watson-Learning-Opt-Out], url,    customer_id,  |레이블 지정된 데이터를 삭제합니다. |

## {{site.data.keyword.conversationshort}} 서비스 인스턴스 작성
{: #service_instance}

패키지를 설치하기 전에 {{site.data.keyword.conversationshort}} 서비스 인스턴스 및 서비스 신임 정보를 작성해야 합니다. 

1. [{{site.data.keyword.conversationshort}} 서비스 인스턴스 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")를 작성하십시오](https://console.bluemix.net/catalog/services/conversation).
2. 서비스 인스턴스가 작성되면 자동 생성 서비스 신임 정보도 사용자를 위해 작성됩니다. 

## {{site.data.keyword.conversationshort}} 패키지 설치
{: #install}

{{site.data.keyword.conversationshort}} 서비스 인스턴스가 보유되면 {{site.data.keyword.openwhisk}} CLI를 사용하여 네임스페이스에 {{site.data.keyword.conversationshort}} 패키지를 설치하십시오.
{: shortdesc}

### {{site.data.keyword.openwhisk_short}} CLI에서 설치
{: #conversation_cli}

시작하기 전에 다음을 수행하십시오. 
  1. [{{site.data.keyword.Bluemix_notm}} CLI용 {{site.data.keyword.openwhisk_short}} 플러그인을 설치하십시오](bluemix_cli.html#cloudfunctions_cli).
  2. [`wskdeploy` 명령 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://github.com/apache/incubator-openwhisk-wskdeploy/releases)을 설치하고 다운로드된 2진을 PATH에 추가하십시오. 

{{site.data.keyword.conversationshort}} 패키지를 설치하려면 다음을 수행하십시오.

1. {{site.data.keyword.conversationshort}} 패키지 저장소를 복제하십시오.
    ```
    git clone https://github.com/watson-developer-cloud/openwhisk-sdk
    ```
    {: pre}

2. 패키지를 배치하십시오.
    ```
    wskdeploy -m openwhisk-sdk/packages/assistant-v1/manifest.yaml
    ```
    {: pre}

3. 패키지가 패키지 목록에 추가되었는지 확인하십시오.
    ```
    ibmcloud fn package list
    ```
    {: pre}

    출력:
    ```
    packages
    /myOrg_mySpace/assistant-v1                        private
    ```
    {: screen}

4. 작성한 {{site.data.keyword.conversationshort}} 인스턴스의 신임 정보를 패키지에 바인드하십시오.
    ```
    ibmcloud fn service bind conversation assistant-v1
    ```
    {: pre}

    출력 예:
    ```
    Credentials 'Credentials-1' from 'conversation' service instance 'Watson Assistant (formerly Conversation)-8h' bound to 'assistant-v1'.
    ```
    {: screen}

5. 패키지가 {{site.data.keyword.conversationshort}} 서비스 인스턴스 신임 정보로 구성되었는지 확인하십시오.
    ```
    ibmcloud fn package get assistant-v1 parameters
    ```
    {: pre}

    출력 예:
    ```
    ok: got package assistant-v1, displaying field parameters
    [
      {
        "key": "__bx_creds",
            "value": {
          "conversation": {
            "credentials": "Credentials-1",
            "instance": "Watson Assistant (formerly Conversation)-8h",
            "password": "AAAA0AAAAAAA",
            "url": "https://gateway.watsonplatform.net/assistant/api",
            "username": "00a0aa00-0a0a-12aa-1234-a1a2a3a456a7"
          }
        }
      }
    ]
    ```
    {: screen}

### {{site.data.keyword.openwhisk_short}} UI에서 설치
{: #conversation_ui}

1. {{site.data.keyword.openwhisk_short}} 콘솔에서 [작성 페이지 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://console.bluemix.net/openwhisk/create)로 이동하십시오. 

2. **Cloud Foundry 조직** 및 **Cloud Foundry 영역** 목록에서 {{site.data.keyword.cos_short}} 패키지가 설치될 네임스페이스를 선택하십시오. 네임스페이스는 결합된 조직 및 영역 이름으로 구성됩니다. 

3. **패키지 설치**를 클릭하십시오. 

4. **Watson** 패키지 그룹을 클릭하십시오. 

5. **Watson Assistant** 패키지를 클릭하십시오. 

5. **설치**를 클릭하십시오. 

6. 일단 패키지가 설치되면 사용자는 액션 페이지로 경로 재지정되며, 이름이 **assistant-v1**인 새 패키지를 검색할 수 있습니다. 

7. **assistant-v1** 패키지의 액션을 사용하려면 서비스 신임 정보를 액션에 바인드해야 합니다. 
  * 서비스 신임 정보를 패키지의 모든 액션에 바인드하려면 위에 나열된 CLI 지시사항의 5 - 6단계를 수행하십시오.  
  * 서비스 신임 정보를 개별 액션에 바인드하려면 UI에서 다음 단계를 완료하십시오. **참고**: 사용할 각 액션마다 다음 단계를 완료해야 합니다. 
    1. 사용할 **assistant-v1** 패키지의 액션을 클릭하십시오. 해당 액션에 대한 세부사항 페이지가 열립니다.  
    2. 왼쪽 탐색 창에서 **매개변수** 섹션을 클릭하십시오.  
    3. 새 **매개변수**를 입력하십시오. 키에 대해 `__bx_creds`를 입력하십시오. 값에 대해 이전에 작성한 서비스 인스턴스의 서비스 신임 정보 JSON 오브젝트를 붙여넣으십시오. 

## {{site.data.keyword.conversationshort}} 패키지 사용
{: #usage}

이 패키지의 액션을 사용하려면 다음 형식으로 명령을 실행하십시오. 

```
ibmcloud fn action invoke assistant-v1/<action_name> -b -p <param name> <param>
```
{: pre}

모든 액션에서는 YYYY-MM-DD 형식의 버전 매개변수가 필요합니다. API가 백워드 호환 불가 방식으로 변경된 경우에는 새 버전 날짜가 릴리스됩니다. [API 참조서](https://www.ibm.com/watson/developercloud/assistant/api/v1/curl.html#versioning)의 세부사항을 참조하십시오. 

이 패키지의 기능에서는 Watson Assistant의 현재 버전(2018-07-10)을 사용합니다. `list-workspaces` 액션을 사용해 보십시오. 
```
ibmcloud fn action invoke assistant-v1/list-workspaces -b -p version 2018-07-10
```
{: pre}

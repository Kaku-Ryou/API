����������������������������������������������������������������������������������������������������������������������<br>
#### ��{�d�l
�P�AAPI�p�X�F/addUsers<br>
�Q�A���\�b�h�FPOST<br>
����������������������������������������������������������������������������������������������������������������������<br>
#### ���N�G�X�g�w�b�_�[
�V�O�l�`����API�L�[�Ȃǂ̏ڍׂ́u���ʃt�H�[�}�b�g�v���Q�Ƃ��Ă��������B<br>

|�t�B�[���h��|���e|
|-|-|
|Content-Type|application/json|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���N�G�X�g�R���e���g

|�p�����[�^��|����|�f�[�^�^|�K�{|�`�F�b�N|
|-|-|-|-|-|
|company_unique_code|��ƕW���R�[�h|������A���p50��|��|���݃`�F�b�N|
|person_in_charge_code|�S���҃R�[�h|������A���p60��|��|��Ӄ`�F�b�N�A�t�H�[�}�b�g�`�F�b�N|
|passwords|�p�X���\�h|������A���p50��|��||
|person_in_charge_name|�S���Җ�|������A���p20��|��||
|person_in_charge_mail|�S���҃��[���A�h���X|������A���p60��|��|�t�H�[�}�b�g�`�F�b�N|
|mobile_tel|�g�ѓd�b�ԍ�|������A���p20��|||
|home_tel|����d�b�ԍ�|������A���p20��|||

����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���XHTTP�X�e�[�^�X

|�X�e�[�^�X�R�[�h|����|
|-|-|
|200|�o�^����|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���X�w�b�_�[

|�t�B�[���h��|�l|
|-|-|
|Content-Type|application/json|
|Location|https://dora.jpis.co.jp/Sales41_aws_demo/rest/UserInfoService/addUsers/�S���҃R�[�h|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���X�R���e���g

|�p�����[�^��|����|�f�[�^�^|
|-|-|-|
|person_in_charge_name|�S���Җ�|������|
|createDate|�o�^����|����|
|person_in_charge_code|�S���҃R�[�h|������|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���N�G�X�g�T���v���iID�EPASSWORD�F�؁j
curl -X POST \ <br>
 -H "user-id:demo@ebskk.com" \ <br>
 -H "user-key:11111111" \ <br>
 -H "Content-Type: application/json" \ <br>
 -d "{company_unique_code:12345678,person_in_charge_code:ebs@ebskk.com,passwords:ebs,person_in_charge_name:ebs,person_in_charge_mail:ebs@ebskk.com,mobile_tel:1234567890,home_tel:0987654321}" \ <br>
https://dora.jpis.co.jp/Sales41_aws_demo/rest/UserInfoService/addUsers <br>
����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���X�T���v���iID�EPASSWORD�F�؁j
HTTP/1.1 201 Created<br>
Content-Type: application/json;charset=UTF-8<br>
Location: https://dora.jpis.co.jp/Sales41_aws_demo/rest/UserInfoService/addUsers/�S���҃R�[�h<br>

{"createDate":"2018-08-28T11:27:16.446Z","person_in_charge_name":"ebs","person_in_charge_code":"ebs@ebskk.com"}<br>
����������������������������������������������������������������������������������������������������������������������<br>																																

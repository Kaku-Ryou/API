����������������������������������������������������������������������������������������������������������������������<br>
#### ��{�d�l
�P�AAPI�p�X�F/gaityusaki/��ƕW���R�[�h/���Ӑ�R�[�h/<br>
�Q�A���\�b�h�FGET<br>
����������������������������������������������������������������������������������������������������������������������<br>
#### ���N�G�X�g�w�b�_�[
�V�O�l�`����API�L�[�Ȃǂ̏ڍׂ́u���ʃt�H�[�}�b�g�v���Q�Ƃ��Ă�������<br>

|�t�B�[���h��|���e|
|-|-|
|Content-Type|application/json|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���N�G�X�g�R���e���g
�Ȃ�<br>
����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���XHTTP�X�e�[�^�X

|�X�e�[�^�X�R�[�h|����|
|-|-|
|200|�擾����|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���X�w�b�_�[

|�t�B�[���h��|�l|
|-|-|
|Content-Type|application/json|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���X�R���e���g

|�p�����[�^��|����|�f�[�^�^|
|-|-|-|
|out_order_code|�O����R�[�h|������|
|out_order_name|�O���於��|������|
|out_order_simple_name|�O���旪��|������|
|out_order_fax|FAX|������|
|out_order_phone|�d�b�ԍ�|������|
|call_name|�O����敪|������|
|out_order_postcode|�X�֔ԍ�|������|
|taxs_div|����ŋ敪|������|
|payment_date|�x����|������|
|fraction_processing|�[������|������|
|payment_condition|�x������|������|
|payment_delay_days|�x���T�C�g|������|
|begin_buy_balance|���񔃊|�c��|������|
|last_payment_balance|�O��x���c��|������|
|out_order_address1|�O����Z��1|������|
|person_in_charge1|�O����S����1|������|
|person_in_charge1_job|�O����S���Җ�E1|������|
|person_in_charge1_mail|�O����S���҃��[��1|������|
|bill_mail1|�x��������1|������|
|out_order_address2|�O����Z��2|������|
|person_in_charge2|�O����S����2|������|
|person_in_charge2_job|�O����S���Җ�E2|������|
|person_in_charge2_mail|�O����S���҃��[��2|������|
|bill_mail2|�x��������2|������|
|out_order_address3|�O����Z��3|������|
|person_in_charge3|�O����S����3|������|
|person_in_charge3_job|�O����S���Җ�E3|������|
|person_in_charge3_mail|�O����S���҃��[��3|������|
|bill_mail3|�x��������3|������|

����������������������������������������������������������������������������������������������������������������������<br>
#### ���N�G�X�g�T���v��
curl -X GET -G \ <br>
 -H "user-id:demo@ebskk.com" \ <br>
 -H "user-key:11111111" \ <br>
 -H "Content-Type: application/json" \ <br>
https://dora.jpis.co.jp/Sales41_aws_demo/rest/UserInfoService/gaityusaki/12345678/000001 <br>
����������������������������������������������������������������������������������������������������������������������<br>
#### ���X�|���X�T���v��
{<br>
  "out_order_code":"000001",<br>
  "out_order_name":"���Ӑ�_�d�a�r_���Y_0000000001",<br>
  "out_order_simple_name":"���O0000000001",<br>
  "out_order_fax":"03-5339-1101  ",<br>
  "out_order_phone":null,<br>
  "call_name":null,<br>
  "out_order_postcode ":"03-5339-1102",<br>
  "taxs_div":"����",<br>
  "fraction_processing":"�؂�̂�",<br>
  "payment_date":"20",<br>
  "payment_condition":"�U����",<br>
  "payment_delay_days":"10",<br>
  "begin_buy_balance":"100000",<br>
  "last_payment_balance":"50000",<br>
  "out_order_address1":"�����s",<br>
  "person_in_charge1":"���Y",<br>
  "person_in_charge1_job":"�ے�",<br>
  "person_in_charge1_mail":"admin@ebskk.com",<br>
  "bill_mail1":"admin@ebskk.com",<br>
  "out_order_address2":null,<br>
  "person_in_charge2":null,<br>
  "person_in_charge2_job":null,<br>
  "person_in_charge2_mail":null,<br>
  "bill_mail2":null,<br>
  "out_order_address3":null,<br>
  "person_in_charge3":null,<br>
  "person_in_charge3_job":null,<br>
  "person_in_charge3_mail":null,<br>
  "bill_mail3":null<br>
}<br>
����������������������������������������������������������������������������������������������������������������������<br>

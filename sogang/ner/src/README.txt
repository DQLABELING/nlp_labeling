<������ :  �ɼ� �߰�>
��Ʈ��Ʈ���� ����, �⺻ CRF �𵨸� �н��ؼ�, �뷮 unlabeled data�� prediction�Ͽ�, ����� ����ϰ��� �� ���
python main.py -g -na -i <unlabeled raw data input file name> -o <machine-labeled data output file name>

 [�߰��� �ɼǼ���]
  * -na : non-active, active train�� ���� ��Ʈ��Ʈ���� ������ �������� ����. ��Ʈ��Ʈ���� ������ ������ ���� sub iteration, bagging ��� ����
  * -i : unlabeled raw data input file name ��� ���� ����, ����������� ������� input ���丮�� unlabeld _raw_data  ���丮 �Ʒ��ִ� ��� ������ �о unlabeled raw data�� ���
  * -o : unlabeled raw data�� prediction�� �ο��� machine-labeled data�� ���� file nmae, ������������ ������ output �� full_data �Ʒ��� ����
  * -boot_iter : boot iter �� �� �Է��ϰ� �߾��µ� active train ���ϽŴټż� ���� �������� ������ 0���� ���� �صξ����ϴ�. 
<��¾�� ����>
 active train ���ϽŴٱ⿡ active train�� ������ ��¾���� �ٲ��� �ʾҽ��ϴ�.
 machine-labeled data output file ( full data )�� ��Ŀ� ������ Ȯ���� �Ʒ��� ���� ���� �߰��Ǿ����ϴ�. ����� Ȯ������ ������ ���Դϴ�.

 ;���� ī�ʹ� ������ �� ���� ī��Ƽ �÷��ν� �������� �¾��.  0.986828040801
 ���� NNP 0 B-PS 1.0
 ī�� NNP 0 I-PS 0.99999999996

## R3. Upstream Mapping
### ����� ��������� � ��������� ����� ��������������� ����
- `git branch -vv` � ������� ������ ��������� ����� � ��������� ����������� � ��� upstream-�����
- `git branch -u <upstream> [<branchname>]` � ������ upstream-����� ��� ��������� ��� ������� �����
- `git push -u origin HEAD` � ������� ��������� �����, ��������������� ��������� � ���������� ����� ���� upstream-�����, ����� �������� ��������� �� ��������� ����� � ��������� �����������
- `git checkout <remote_branchname>` � ������� ��������� �����, ��������������� ��������� � ���������� ����� ���� upstream-�����, ����� ����������� HEAD �� ���
- `git pull` = `git pull origin` � �������� ���������� ��������� ���������� ����������� � ����� ��������� �� ��������� ����� � ��������������� ��������� �����
- `git pull --ff-only` � �������� ����������, � ����� �����, ���� �������� fast-forward merge
- `git pull --rebase` � �������� ���������� � ��������� rebase ��������� ����� �� ��������� �����
- `git config --global push.default simple` � ������ simple-����� �������� � upstream-������� ��� push. ��� ����� �� ��������� � Git 2.0 � ����
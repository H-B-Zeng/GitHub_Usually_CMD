###git init
```
git init �@�}�l����l��
```

### git add 
```
git add . �����s�W	
git add app/*	�s�WAPP�ؿ����U
git add *.txt �s�W���ɦW��txt
git add -u	�ȱN�u��s�v�Ρu�R���v���ɮ��ܧ�g�J��u�����ɡv���C
```

###git status
```
git status
git status -s	²�u����
```

###git commit
```
git commit
git commit -m "����������������r"
```    

###git log
```
git log				���log
git log -10		�u���10��log
```

###git rm
```
git rm �����O���檺�ɭԡA�|�P�ɰ����ơG
�R���u�@�ؿ��֨��� 'Gruntfile.js' �o���ɮ� (�ΨӼХܳo�ӧR���ɮת��ʧ@�n�C�J��������)
�R���u�@�ؿ��U�� 'Gruntfile.js' �o�ӹ����ɮ� (�N��u����o�ӹ����ɮ׵��R��)

git rm filename ���ɭԡA���F��s�����ɤ��~�A�s�u�@�ؿ��U���ɮפ]�|�@�ֳQ�R��
git rm --cached a.txt �u�Q�R�������ɤ������ɡA�S�n�O�d�u�@�ؿ��U�������ɮ�
git rm '*.txt'  
git rm 'app/*.html'
```

###git mv
```
git mv 'oldname' 'newname'	�N�ɮק�W
```

###git reset
```
git reset ���]�@�U�u�@�ؿ������ު��A�A�Ҧpadd -A ����A�٭�
git reset --hard �p�G�Q��u�@�ؿ��]���٭��ثe���̷s���A�@����Ҧ��ɮ׳����٭�F
git rm �R�����ؿ����ɮסA�٬O�� git mv ��W���ؿ����ɮסA�z�L git reset ���L�k��u�����ɮסv���Ϧ^��
�I
```

###git checkout
```
git checkout master 'filename' �u�٭�@���ɮ�
```

###git gc
```
git gc	�|�۰ʰ��歫�s�ʸ˵��ʧ@�A���A�̵M�i�H�ۦ�U�F���O����
```

###git fsck
```
git fsck	�ˬd Git ���@���ɮרt�άO�_����
```

###git push
```
git push -u origin master ����s���W�Ǩ�GitHub
```

###git branch
```
git branch  										 =>�d�ݦ����Ǥ���
git branch [branch_name]     		 =>�إߤ���A�ثe�u�@�ؿ������b�ۤv������
git checkout -b [branch_name]		 =>�إߤ���A�N�ثe�u�@�ؿ�������s������
git checkout [branch_name]			 =>������U���ؿ�����@�Ӥ���
git branch -d [branch_name]			 =>�R���@�Ӥ���A�p�G�O��U�����䤣�i�R��
git log													 =>�d�ݬ���
```
�ϥ�SourceTree �u��i�H�ιϥܡA�i�@�B�F�Ѥ���[�c�A[�ϥΤ�k](https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/docs/08%20%E9%97%9C%E6%96%BC%E5%88%86%E6%94%AF%E7%9A%84%E5%9F%BA%E6%9C%AC%E8%A7%80%E5%BF%B5%E8%88%87%E4%BD%BF%E7%94%A8%E6%96%B9%E5%BC%8F.markdown)�C


###git diff 
```
git diff                 => �u�@�ؿ� vs ����
git diff HEAD            => �u�@�ؿ� vs HEAD
git diff --cached HEAD   => ����     vs HEAD
git diff --cached        => ����     vs HEAD
git diff HEAD^ HEAD      => HEAD^   vs HEAD ����i�̷s�����e�@���j�P�i�̷s���j�������t��
```
###git help 
```
�ԲӪ����O�P�Ѽƻ����A�i�H��J git help reset �d�ߧ��㪺���C
�ԲӪ����O�P�Ѽƻ����A�i�H��J git help checkout �d�ߧ��㪺���C
�ԲӪ����O�P�Ѽƻ����A�i�H��J git help branch �d�ߧ��㪺���C
```




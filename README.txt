2023-2-8
learn to use git

###### 1.1 һ����ʹ��git ######

cd file              #������Ŀ�ļ���
git init             #��ʼ������git�����ǹ����ļ��С�����Ŀ�ļ����У��հ״��Ҽ�ѡ��git bash here�����ն�����
git status           #����--��⵱ǰ�ļ����µ��ļ�״̬�����ֵĺ�ɫ�ļ���Untracked files�������ǵ�Ŀ�������ɰ汾��������ɰ汾��
git add test.txt     #git����test.txt�ļ�
git status           #ԭ����ɫ�ļ���3����README.txt  learn-git.py test.txt��������test.txtΪ��ɫ��ʣ��2��Ϊ��ɫ  
		     #����״̬�ı仯  ��ɫ�������ļ�/�޸���ԭ���ļ�  -��git add �ļ��� .   ��ɫ��git�Ѿ��������� -��git commit
		      -m '������Ϣ'  ��ɫ�����ɵİ汾
get add .            #��git����ǰ�ļ���������δ������ļ�����git����ǰ�ļ����������ļ���
git commit -m 'v1'   #���ɰ汾1����������д������Ϣ
git status           #�ļ����ڵ��ļ������ˡ������ļ����ڵ��ļ�����git������������һ���汾��

#�޸��ļ���
git status           #�޸ĵ��ļ��Ǻ�ɫ��
git add .            #���޸ĵ��ļ��ύgit��Ҳ���Լ��޸ĵ��ļ�����ֻ����͵���ˡ�
git status           #��ɫ�ļ�����ɫ
git commit -m 'v2'   #���ɰ汾2
git log              #��ӡ���ύ�İ汾��Ϣ�����ɵļ����汾

#������Ϣ���ã��û��������䣨��һ�ΰ�װ��Ҫ����git commit��ʱ��ᱨ�� [һ�μ���]
touch lq.py
git status
git commit -m 'xxx'

##������ʾPlease tell me who you are  git config --global user.email "you@exampl.com"
##                                    git config --global user.name "your name"

##ִ�����������
git log              #�����û���������Ϣ

#�ع� �ص�֮ǰ��ĳ���汾
git reset --hard �汾��

#�ص�֮ǰ�İ汾�󣬺���ˣ���Ҫ֮��İ汾������git logֻ���Կ����ð汾֮ǰ�İ汾
git reflog           #�鵽���еİ汾��Ϣ���ҵ���Ҫ�İ汾����git reset --hard �汾�� ��ȥ����


###### 2.2  ######
git branch           #Ŀǰ�������ڵķ�֧
git branch dev       #�����·�֧
git checkout dev     #��master��֧�л���dev��֧

git checkout master  #�л���master����
git merge bug        #��bug�ϲ���master
git branch -d bug    #ɾ��bug��֧





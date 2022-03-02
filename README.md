# airflow_main
Create a new user name hdoop
 
```
sudo adduser hdoop
```

loging to hdoop user
'''
su -hdoop
'''

Download hadoop (version using in the code are v3.2.2 binary)

Gen ssh key

'''
ssh hdoop@localhost.com
'''

setup password less ssh

'''
ssh-keygen -t rsa 
'''

move key 
'''
cat .ssh/id_rsa.pub >> .ssh/authorized_keys
'''

run ssh again then logout
'''
ssh hdoop@localhost.com

logout
'''

All other setup in hadoop, yarn and spark in doc https://docs.google.com/document/d/1jsYlVMNLU7FXC0UvuloQaRsLcxWDlcuH-WJT-pQi5pA/edit



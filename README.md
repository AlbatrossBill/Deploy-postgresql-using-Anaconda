# Deploy-postgresql-using-Anaconda
Install Anaconda postgresql, and using PostgreSQL to manage.
When using Anaconda postgresql might cause issues show up. Here is few of many approachs that can solve the problems.
## 1. Install Anaconda
https://www.anaconda.com/products/individual
## 2. Run Anaconda Prompt with Adminstrator
![image](https://user-images.githubusercontent.com/78173335/128711696-59b3e5f5-568f-4b9c-a3cc-b977b3d339a7.png)

Typing in
```
conda install -c anaconda postgresql
```
If everything goes will, you can see the image below. Then you can keep going to step No.3

![image](https://user-images.githubusercontent.com/78173335/128714019-75605920-530e-4cd5-a3ea-cf79d68c8fe4.png)

Or

If you close the Anaconda commond prompt accidental while the installation didn't finish, some issues might show up.
![image](https://user-images.githubusercontent.com/78173335/128714341-58b60780-666c-4601-8b79-fdb371a41776.png)

### Approach_1:
Delete the file .condarc in C:/Users/<Admin> path
![image](https://user-images.githubusercontent.com/78173335/128714682-fe224d21-c333-43a8-b137-a43fc973807b.png)

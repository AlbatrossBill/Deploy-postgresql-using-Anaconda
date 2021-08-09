# Deploy-postgresql-using-Anaconda
# Windows 10 x64
Install Anaconda postgresql, and using PostgreSQL to manage.
When using Anaconda postgresql might cause issues show up. Here are few of many approachs that can solve the problems.
## 1. Install Anaconda
https://www.anaconda.com/distribution/#windows
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
Delete the .condarc file's content in C:/Users/<Admin> path
![image](https://user-images.githubusercontent.com/78173335/128714682-fe224d21-c333-43a8-b137-a43fc973807b.png)
  
If Approach_1 didn't work ↓
  
### Approach_2:
  Set Anaconda bin and lib into enviorment variable's system variable
  ![image](https://user-images.githubusercontent.com/78173335/128715794-5bcdf03b-5647-4186-ab53-adb44739f153.png)
  
  ![image](https://user-images.githubusercontent.com/78173335/128716383-ee3de90f-dc12-4b3b-8648-870ccc27ac64.png)

  *Please using your Anaconda installation path.
  
  ### Approach_3:
  If the method above not work, and also your computer doesn't have many stuffs, of course you can restore your computer for fixing this issue, i can asure you if can be fix after restore:) (Yes I am joking! but may be I am not?)
  

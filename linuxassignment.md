# Linux User Management Guide

In this guide, we'll cover the process of creating and managing users on a Linux system using the command line.

1. I created a user named "tobiloba".
   ![Creating a new user](1.png)

2. The expiry date of the user account was set to two weeks after it was created.
   ![Set an Expiry Date](2.png)

3. The expiry date of the user account was confirmed.
    ![Confirmation of the expiry date](3.png)

4. The user was prompted to change their password on their next login.
    ![Prompt User to Change Password](4.png)

5. I created a new group called "altschool".
   ![Creating a new group](5.png)

6. I added the user "tobiloba" to the "altschool" group.
    ![Attach User to a Group](9.png)

7. I edited the sudoers file to allow the "students" group to run the `cat` command on files in the `/etc/` directory.
     ![Allow "altschool" Group to Run `cat` on /etc/](7.png)

8. I created a user named "nohometobiloba" without a home directory.
    ![Create Another User Without a Home Directory](8.png)

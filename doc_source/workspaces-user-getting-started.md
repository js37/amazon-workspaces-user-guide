# Getting started with your WorkSpace<a name="workspaces-user-getting-started"></a>

After your administrator creates your WorkSpace, you receive an invitation email\. Complete the following tasks to get started with your WorkSpace\.

**Topics**
+ [Complete your user profile](#complete-registration)
+ [Choose a client](#choose-client)
+ [Determine your client version](#determine-version)
+ [Determine your streaming protocol](#determine-protocol)
+ [Verify networking requirements](#verify-requirements)
+ [\(Optional\) Access the applications assigned to you](#access-wam-apps)
+ [\(Optional\) Integrate with WorkDocs](#workdocs-integration)

## Complete your user profile<a name="complete-registration"></a>

After your administrator creates your WorkSpace, you must complete your user profile within seven days; otherwise, your invitation expires\. If your invitation expires, ask your administrator for another invitation\.

**To complete your user profile**

1. Open the link in the invitation email\.

1. Enter your password\. Passwords are case\-sensitive and must be between 8 and 64 characters in length, inclusive\. Passwords must contain at least one character from each of the following categories:
   + Lowercase characters \(a\-z\)
   + Uppercase characters \(A\-Z\)
   + Numbers \(0\-9\)
   + Non\-alphanumeric characters \(\~\!@\#$%^&\*\_\-\+=`\|\\\(\)\{\}\[\]:;"'<>,\.?/\)

1. Choose **Update User**\.

You can change your WorkSpaces password anytime\. For more information, see [Change your password](manage_workspace_client.md#client-change-password)\.

## Choose a client<a name="choose-client"></a>

You can connect to your WorkSpace using the client application for a supported device or a web browser\. To run the WorkSpaces client application, you must have a Windows or Linux PC, Mac, iPad, Kindle, Chromebook, or Android tablet or phone\. To run WorkSpaces Web Access, you must have a Windows PC or a Mac running a Chrome or Firefox web browser, or a Linux PC running a Firefox browser\.

For information about connecting to your WorkSpace, see the following client documentation\.
+ [Android Client Application](amazon-workspaces-android-client.md)
+ [iPad Client Application](amazon-workspaces-ipad-client.md)
+ [Linux Client Application](amazon-workspaces-linux-client.md)
+ [macOS Client Application](amazon-workspaces-osx-client.md)
+ [PCoIP Zero Client](amazon-workspaces-pcoip-zero-client.md)
+ [Web Access](amazon-workspaces-web-access.md)
+ [Windows Client Application](amazon-workspaces-windows-client.md)

## Determine your client version<a name="determine-version"></a>

To see which version of the WorkSpaces client you have, choose **Amazon WorkSpaces**, **About Amazon WorkSpaces**, or click the gear icon in the upper\-right corner and choose **About Amazon WorkSpaces**\.

## Determine your streaming protocol<a name="determine-protocol"></a>

Device or feature support might differ depending on which streaming protocol your WorkSpace is using, either PCoIP or WorkSpaces Streaming Protocol \(WSP\)\. In the 3\.0\+ versions of the macOS and Windows client applications, you can see which protocol your WorkSpace is using by choosing **Support**, **About My WorkSpace**\. The iPad, Android, and Linux client applications currently support only the PCoIP protocol\.

## Verify networking requirements<a name="verify-requirements"></a>

To ensure a good experience with your WorkSpace, verify that your client device meets the networking requirements\.

### To verify networking requirements for 3\.0\+ clients<a name="verify-requirements-new-clients"></a>

1. Open your WorkSpaces client\. If this is the first time you have opened the client, you are prompted to enter the registration code that you received in the invitation email\.

1. Depending on which client you're using, do one of the following\.    
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workspaces/latest/userguide/workspaces-user-getting-started.html)

   The client application tests the network connection, ports, and round\-trip time, and reports the results of these tests\.

1. Close the **Network** dialog box to return to the sign\-in page\.

### To verify networking requirements for 1\.0\+ and 2\.0\+ clients<a name="verify-requirements-legacy-clients"></a>

1. Open your WorkSpaces client\. If this is the first time you have opened the client, you are prompted to enter the registration code that you received in the invitation email\.

1. Choose **Network** in the lower\-right corner of the client application\. The client application tests the network connection, ports, and round\-trip time, and reports the results of these tests\.

1. Choose **Dismiss** to return to the sign\-in page\.

## \(Optional\) Access the applications assigned to you<a name="access-wam-apps"></a>

You use the Amazon WorkSpaces Application Manager client application on your Windows WorkSpace to install and access the applications that your Amazon WorkSpaces administrator has assigned to you\.

**To install and start assigned applications**

1. To start the Amazon WorkSpaces Application Manager client application, choose the **Amazon WAM** shortcut on the desktop of your Windows WorkSpace\.

   If the shortcut is not available, see [Troubleshooting Amazon WAM Issues](http://docs.aws.amazon.com/wam/latest/userguide/troubleshooting.html) in the *Amazon WAM User Guide*\.

1. To find applications that have been assigned to you but have not been installed, choose **DISCOVER**\.

1. To install an application, choose the triangle \(install\)\.

1. You can start your Amazon WAM applications by using the Amazon WorkSpaces Application Manager client application or the Windows Start menu\. For more information, see [Getting Started](http://docs.aws.amazon.com/wam/latest/userguide/) in the *Amazon WAM User Guide*\.

## \(Optional\) Integrate with WorkDocs<a name="workdocs-integration"></a>

If your Amazon WorkSpaces administrator has enabled it, you can integrate your WorkSpace with Amazon WorkDocs\. You can use Amazon WorkDocs to store, sync, and share your files\. WorkDocs can automatically back up documents on your WorkSpace and sync documents to and from other devices such as a PC or Mac, so that you can access your data regardless of which desktop you are using\.

**Note**  
WorkDocs isn't available for use with Linux WorkSpaces\.

**To install WorkDocs on your WorkSpace**

1. Choose \(double\-click\) the **Install Amazon WorkDocs** desktop shortcut on your WorkSpace\.

1. In the **Amazon WorkDocs Setup** dialog box, choose **Get Started**\.

1. Ignore the prompt to provide a WorkDocs site URL, and instead choose **Enter a WorkSpaces registration code** under the **Next** button\.

1. In the **Registration Code** box, enter the registration code that you received in your WorkSpaces welcome mail, and then choose **Next**\.

1. In the **Username** and **Password** boxes, enter your WorkSpace login credentials, and then choose **Sign In**\.

1. In the next dialog box, a folder is suggested for the location of your synced files\. The default folder is `D:\Users\WorkSpaceUserName\WorkDocs`\. To specify a different folder, choose **Change**\. After you've made your choice, choose **Next**\. 

1. Choose which files you'd like to sync \(either **Sync only the files and folders I select from WorkDocs** or **Sync all files and folders from WorkDocs**\)\. To finish setting up, choose **Next**\.

1. Open Windows File Explorer\. You should now see your new `D:\Users\WorkSpaceUserName\WorkDocs `folder\. To back up and sync your files, make sure to save your files to this location\.

1. Install WorkDocs Drive on any other computers or devices that you'd like to sync files between\. You can download the WorkDocs Drive client from [https://amazonworkdocs\.com/clients](https://amazonworkdocs.com/clients)\. When you log in to WorkDocs Drive, make sure to use your WorkSpace registration code, username, and password, as described earlier in this procedure\.
**Important**  
If you're installing WorkDocs Drive on a Mac, follow the instructions in [Installing Amazon WorkDocs Drive](https://docs.aws.amazon.com/workdocs/latest/userguide/drive_install.html) in the *Amazon WorkDocs Administration Guide* in the *Amazon WorkDocs Administration Guide*\.

For more information about working with WorkDocs Drive, see [Amazon WorkDocs Drive](https://docs.aws.amazon.com/workdocs/latest/userguide/workdocs_drive_help.html) in the *Amazon WorkDocs Administration Guide*\.
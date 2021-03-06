# 配置常用登录IP<a name="ZH-CN_TOPIC_0120362819"></a>

该任务指导用户配置常用登录IP。使用常用登录IP登录到弹性云服务器时，系统不会报异地登录风险。

## 操作步骤<a name="section14815104218011"></a>

1.  登录管理控制台。
2.  在页面上方，单击“服务列表“，选择“安全  \>  企业主机安全“。
3.  在左侧导航树中，选择“安装与配置“，进入安装Agent界面。
4.  选择“安全配置“页签，在“常用登录IP“页面，单击“添加常用登录IP“。
5.  在弹出的对话框中，填写要添加的常用登录IP，如[图1](#fig30200071125018)所示。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >用户可以输入单个IP地址，也可以输入一个网段，支持的格式如下：  
    >-   10.78.10.0/255.255.255.0  
    >-   10.78.10.0/24  
    >-   10.78.10.0  

    **图 1**  添加常用登录IP<a name="fig30200071125018"></a>  
    ![](figures/添加常用登录IP.png "添加常用登录IP")

6.  在左侧“可选云服务器“列表框中选中需要添加该常用登录IP的弹性云服务器，将所选弹性云服务器移动到“已选云服务器“列表框。
7.  单击“确定“，完成一个常用登录IP的配置。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   如果需要编辑已配置的常用登录IP，在目标常用登录IP所在行的“操作“列，单击“编辑“。  
    >-   如果需要删除已配置的常用登录IP，在目标常用登录IP所在行的“操作“列，单击“删除“。  



# 众ROM如何添加白名单

[TOC]

## 小米

- 自启动管理（MIUI8.1）

    `安全中心` > `授权管理` > `自启动管理*`
    
    ``` shell
    {
        cmp=com.miui.securitycenter/com.miui.permcenter.autostart.AutoStartManagementActivity
    }
    ```

- 神隐模式（MIUI8.1）

    `设置` > `电量和性能` > `神隐模式` > `应用配置*` > `找到App，选择无限制` 
     
    ``` shell
    {
        act=miui.intent.action.POWER_HIDE_MODE_APP_LIST
        cmp=com.miui.powerkeeper/.ui.HiddenAppsContainerManagementActivity
    }
    ```

## 魅族

- 手机加速白名单（Flyme5）
    
    `手机管家` > `手机加速*` > `设置` > `手机加速白名单` > `添加白名单`  > `找到App，添加`
    
    ``` shell
    {
        cmp=com.meizu.safe/.SecurityMainActivity 
    }
    ```
     
- 自启动权限（Flyme5）

    新版已经取消

- 待机耗电管理（Flyme5）

    `手机管家` > `省电模式*` > `待机耗电管理` > `找到App，添加`

## 锤子

- 自启动管理（Smartisan V3.1.2,V3.1.5）

    `设置` > `安全中心` > `应用程序权限管理*` > `自启动权限管理` > `找到梦画` > `允许被系统启动` > 
    
    ``` shell
    {
        cmp=com.smartisanos.security/.MainActivity
    }
    ```
    
## OPPO 

- 自启动管理（ColorOS V2.1）

    `桌面图标` > `安全中心` > `权限隐私` > `自启动管理*`
    
    ``` shell
    {
        cmp=com.color.safecenter/.permission.startup.StartupAppListActivity
    }
    ```

- 电量节省（省电设置，纯净后台名单）（ColorOS V2.1）
    
    `桌面图标` > `安全中心` > `设置*` > `电量节省（省电设置）` > `纯净后台名单设置`
    
    ``` shell
    {
        cmp=com.color.safecenter/.SecureSafeMainSettingsActivity
    }
    ```
   
## VIVO TODO

    
    
## 华为 TODO
    


## 三星 TODO



## 一加 TODO


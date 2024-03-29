<div class="sidebar_title icon__uiot"> 物联网通信云平台 UIoT Core</div>

* [概览](iot/uiot-core/overview)
* [产品简介](iot/uiot-core/product_introduction/)
    * [什么是物联网通信云平台](iot/uiot-core/product_introduction/what_is_iotcore)
    * [功能介绍](iot/uiot-core/product_introduction/function_introduction)
    * [名词解释](iot/uiot-core/product_introduction/terms)
    * [使用限制](iot/uiot-core/product_introduction/limitation)
    * [已开通区域及域名列表](iot/uiot-core/product_introduction/available_region_url)
* [产品定价](iot/uiot-core/pricing)
* [快速入门](iot/uiot-core/quick_start/)
    * [快速入门示例](iot/uiot-core/quick_start/scenario_description)
* [控制台操作指南](iot/uiot-core/console_guide/)
    * [登录控制台](iot/uiot-core/console_guide/chek_in)
    * 产品和设备管理
        * [创建产品](iot/uiot-core/console_guide/product_device/create_products)
        * [创建设备](iot/uiot-core/console_guide/product_device/create_devcies)
        * [Topic管理](iot/uiot-core/console_guide/product_device/topic)
    * 规则引擎
        * [概览](iot/uiot-core/console_guide/ruleengine/what_is_ruleegngine)
        * [数据流转管理](iot/uiot-core/console_guide/ruleengine/data_forwarding)
        * [SQL表达式特性](iot/uiot-core/console_guide/ruleengine/sql_statements)
        * [数据流转到MySQL](iot/uiot-core/console_guide/ruleengine/forward_data_to_mysql)
        * [数据流转到MongoDB](iot/uiot-core/console_guide/ruleengine/forward_data_to_mongodb)
        * [数据流转到分布式消息系统kafka](iot/uiot-core/console_guide/ruleengine/forward_data_to_kafka)
        * [数据流转到其他Topic](iot/uiot-core/console_guide/ruleengine/forward_data_to_topic)
        * [数据流转到HTTP服务](iot/uiot-core/console_guide/ruleengine/forward_data_to_http)
    * 设备影子
        * [设备影子简介](iot/uiot-core/console_guide/device_shadow/waht_is_deviceshadow)
        * [设备影子相关操作](iot/uiot-core/console_guide/device_shadow/operation_guide)
    * 物模型
        * [什么是物模型](iot/uiot-core/console_guide/thingmode/what_is_thingmode)
        * [物模型定义流程](iot/uiot-core/console_guide/thingmode/thingmode_guide)
        * [功能定义示例](iot/uiot-core/console_guide/thingmode/operation_example)
    * 固件与升级
        * [概述](iot/uiot-core/console_guide/ota/what_is_ota)
        * [固件管理](iot/uiot-core/console_guide/ota/firmware_management)
        * [升级管理](iot/uiot-core/console_guide/ota/firmware_update)
    * 运维功能
        * [概述](iot/uiot-core/console_guide/monitoring_maintenance/monitoring_maintenance_introduction)
        * [监控视图](iot/uiot-core/console_guide/monitoring_maintenance/monitor)
        * [日志管理](iot/uiot-core/console_guide/monitoring_maintenance/log)
        * [设备调试](iot/uiot-core/console_guide/monitoring_maintenance/online_debug)
    * [上传文件](iot/uiot-core/console_guide/uploadfile)
* [设备端开发指南](iot/uiot-core/device_develop_guide/)
    * [概述](iot/uiot-core/device_develop_guide/sdkdownload)
    * 设备注册
        * [什么是设备注册](iot/uiot-core/device_develop_guide/authenticate_devices/what_is_authenticate_devices)
        * [静态注册](iot/uiot-core/device_develop_guide/authenticate_devices/unique-certificate-per-device_authentication)
        * [动态注册](iot/uiot-core/device_develop_guide/authenticate_devices/unique-certificate-per-product_authentication)
    * 设备连接
        * [基于MQTT-TCP协议建立连接](iot/uiot-core/device_develop_guide/deviceconnect/mqttconnect)
        * [基于MQTT-WebSocket协议建立连接](iot/uiot-core/device_develop_guide/deviceconnect/websocketconnect)
        * [基于HTTP协议建立连接](iot/uiot-core/device_develop_guide/deviceconnect/httpconnect)
    * [设备影子](iot/uiot-core/device_develop_guide/device_shadow)
    * 设备物模型开发
        * [物模型定义](iot/uiot-core/device_develop_guide/thingmode/what_is_thingmode)
        * [获取物模型JSON文档](iot/uiot-core/device_develop_guide/thingmode/get_json)
        * [设备属性](iot/uiot-core/device_develop_guide/thingmode/property)
        * [设备事件](iot/uiot-core/device_develop_guide/thingmode/event)
        * [设备命令](iot/uiot-core/device_develop_guide/thingmode/command)
        * [设备期望属性](iot/uiot-core/device_develop_guide/thingmode/desired)
    * [设备OTA升级](iot/uiot-core/device_develop_guide/ota)
    * [上传文件](iot/uiot-core/device_develop_guide/uploadfile)
    * C-SDK使用参考
        * [C-SDK 快速入门](iot/uiot-core/device_develop_guide/c_sdk_example/csdkquickstart)
        * [HAL接口详细说明](iot/uiot-core/device_develop_guide/c_sdk_example/halinterface)
        * [MQTT与设备认证开发](iot/uiot-core/device_develop_guide/c_sdk_example/mqttinterface)
        * [设备影子开发](iot/uiot-core/device_develop_guide/c_sdk_example/deviceshadowinterface)
        * [设备物模型开发](iot/uiot-core/device_develop_guide/c_sdk_example/thingmodelinterface)
        * [设备OTA开发](iot/uiot-core/device_develop_guide/c_sdk_example/otainterface)
        * [常见问题](iot/uiot-core/device_develop_guide/c_sdk_example/commonerror)
        * [基于STM32+FreeRTOS+LWIP的SDK移植](iot/uiot-core/device_develop_guide/c_sdk_example/stm32_freertos_lwip_portingguide)
* [云端开发指南](iot/uiot-core/api_guide/)
    * [概述](iot/uiot-core/api_guide/summary)
    * [API列表](iot/uiot-core/api_guide/api_list)
    * [关于API接入](iot/uiot-core/api_guide/api_guidehelp)
    * [产品管理](iot/uiot-core/api_guide/productmgmtapi)
    * [设备管理](iot/uiot-core/api_guide/devicemgmtapi)
    * [主题管理](iot/uiot-core/api_guide/topicmgmt)
    * [设备影子](iot/uiot-core/api_guide/deviceshadowmgmtapi)
    * [物模型](iot/uiot-core/api_guide/tingmodemgmtapi)
    * [消息通信](iot/uiot-core/api_guide/messagemgmtapi)
    * [规则引擎](iot/uiot-core/api_guide/ruleeneinmgmt)
    * [上传文件](iot/uiot-core/api_guide/uploadfile)
    * [返回码](iot/uiot-core/api_guide/retcode)
* [最佳实践](iot/uiot-core/best_practices/)
    * [使用MQTT.fx接入物联网通信云平台](iot/uiot-core/best_practices/connect_to_iotcore_using_mqtt.fx)
    * [使用mqtt.js接入物联网通信云平台](iot/uiot-core/best_practices/connect_to_iotcore_with_mqtt.js)
* [常见问题](iot/uiot-core/faq)
* [版本更新说明](iot/uiot-core/release_notes)





    
   
   
    
        

REL 1. How do you manage service limits?
Default service limits exist to prevent accidental provisioning of more resources than you need. There are also limits on how often you can call API operations to protect services from abuse. If you are using AWS Direct Connect, you have limits on the amount of data you can transfer on each connection. If you are using AWS Marketplace applications, you need to understand the limitations of the applications. If you are using third-party web services or software as a service, you also need to be aware of the limits of those services.

Aware of limits but not tracking them

Monitor and manage limits

Use automated monitoring and management of limits

Accommodate fixed service limits through architecture

Ensure a sufficient gap between the current service limit and the maximum usage to accommodate failover

Manage service limits across all relevant accounts and regions

None of these

REL 1.您如何管理服务限制？
存在默认服务限制以防止意外配置比您需要的更多资源。您可以调用API操作的频率也受到限制，这样可以保护服务免受滥用的。如果您使用的是AWS Direct Connect，则可以限制每个连接上可以传输的数据量。如果您使用的是AWS Marketplace应用程序，则需要了解应用程序的限制。如果您使用第三方Web服务或软件服务，则还需要了解这些服务的限制。

意识到限制但不跟踪它们

监控和管理限制

使用自动监控和限制管理

通过架构适应固定服务限制

确保当前服务限制与最大使用之间有足够的差距以适应故障转移

管理所有相关帐户和地区的服务限额

都不是

REL 2. How do you manage your network topology?
Applications can exist in one or more environments: your existing data center infrastructure, publicly accessible public cloud infrastructure, or private addressed public cloud infrastructure. Network considerations such as intra- and inter-system connectivity, public IP address management, private address management, and name resolution are fundamental to using resources in the cloud.

Use highly available connectivity between private addresses in public clouds and on-premises environment

Use highly available network connectivity for the users of the workload

Enforce non-overlapping private IP address ranges in multiple private address spaces where they are connected

Ensure IP subnet allocation accounts for expansion and availability

None of these

REL 2.如何管理网络拓扑？
应用程序可以存在于一个或多个环境中：现有数据中心基础架构，可公开访问的公共云基础架构或私有地址的公共云基础架构。系统内部和系统间连接，公共IP地址管理，私有地址管理和名称解析等网络注意事项对于在云中使用资源是很重要的。

在公共云和本地环境中的私有地址之间使用高可用连接

为工作负载的用户使用高可用性网络连接

当多个私有地址空间相连时，强制使用不重叠的私有IP地址范围

确保IP子网分配考虑扩展和可用性

都不是

REL 3. How does your system adapt to changes in demand?
A scalable system provides elasticity to add and remove resources automatically so that they closely match the current demand at any given point in time.

Procure resources automatically when scaling a workload up or down

Procure resources upon detection of lack of service within a workload

Procure resources manually upon detection that more resources may be needed soon for a workload

Load test the workload

None of these

REL 3.您的系统如何适应需求的变化？
可扩展系统提供弹性以自动添加和移除资源，以便它们在任何给定时间点与当前需求紧密匹配。

向上或向下扩展工作负载时自动获取资源

在检测到工作负载内缺少服务时获取资源

在检测到工作负载可能需要更多资源时手动获取资源

对工作负载进行负载测试

都不是

REL 4. How do you monitor your resources?
Logs and metrics are a powerful tool to gain insight into the health of your workloads. You can configure your workload to monitor logs and metrics and send notifications when thresholds are crossed or significant events occur. Ideally, when low-performance thresholds are crossed or failures occur, the workload has been architected to automatically self-heal or scale in response.

Monitor the workload in all tiers

Send notifications based on the monitoring

Perform automated responses on events

Conduct reviews regularly

None of these

REL 4.您如何监控您的资源？
日志和指标是深入了解工作负载运行状况的强大工具。您可以配置工作负载以监控日志和指标，并在超过阈值或发生重大事件时发送通知。理想情况下，当超过低性能阈值或发生故障时，工作负载已经过设计，可以自动进行自我修复或扩展响应。

监控所有层中的工作负载

根据监控发送通知

对事件执行自动回复

定期进行审核

都不是

REL 5. How do you implement change?
Uncontrolled changes to your environment make it difficult to predict the effect of a change. Controlled changes to provisioned resources and workloads are necessary to ensure that the workloads and the operating environment are running known software and can be patched or replaced in a predictable manner.

Deploy changes in a planned manner

Deploy changes with automation

None of these

REL 5.您如何实施变革？
对环境进行不受控制的更改会导致难以预测更改的影响。必须对配置的资源和工作负载进行受控更改，以确保工作负载和操作环境运行已知软件，并且可以以可预测的方式进行修补或替换。

以有计划的方式部署更改

使用自动化部署的更改

都不是

REL 6. How do you back up data?
Back up data, applications, and operating environments (defined as operating systems configured with applications) to meet requirements for mean time to recovery (MTTR) and recovery point objectives (RPO).

Identify all data that needs to be backed up and perform backups or reproduce the data from sources

Perform data backup automatically or reproduce the data from sources automatically

Perform periodic recovery of the data to verify backup integrity and processes

Secure and encrypt backups or ensure the data is available from a secure source for reproduction

None of these

REL 6.如何备份数据？
备份数据，应用程序和操作环境（定义为使用应用程序配置的操作系统），以满足平均恢复时间（MTTR）和恢复点目标（RPO）的要求。

确定需要备份的所有数据并执行备份或从源重现数据

自动执行数据备份或自动从源重现数据

定期恢复数据以验证备份完整性和备份过程

保护和加密备份或确保数据可从安全源获得以进行复制

都不是

REL 7. How does your system withstand component failures?
If your workloads have a requirement, implicit or explicit, for high availability and low mean time to recovery (MTTR), architect your workloads for resilience and distribute your workloads to withstand outages.

Monitor all layers of the workload to detect failures

Implement loosely coupled dependencies

Implement graceful degradation to transform applicable hard dependencies into soft dependencies

Automating complete recovery because technology constraints exist in parts or all of the workload requiring a single location

Deploy the workload to multiple locations

Automate healing on all layers

Send notifications upon availability impacting events

None of these

REL 7.您的系统如何承受组件故障？
如果您的工作负载具有隐式或显式的对于高可用性和低平均恢复时间（MTTR）的要求，请构建您的工作负载以实现弹性并分布工作负载以抵御中断。

监控工作负载的所有层以检测故障

实现松散耦合的依赖项

实现优雅降级以将适用的硬依赖关系转换为软依赖关系

自动化完全恢复，因为在需要单个位置的部分或全部工作负载中存在技术约束

将工作负载部署到多个位置

在所有层面上自动修复

根据可用性影响事件发送通知

都不是

REL 8. How do you test resilience?
Test the resilience of your workload to help you find latent bugs that only surface in production. Exercise these tests regularly.

Use playbooks for unanticipated failures

Conduct root cause analysis (RCA) and share results

Inject failures to test resiliency

Conduct game days regularly

None of these

REL 8.您如何测试弹性？
测试工作负载的弹性，以帮助您找到仅在生产中出现的潜在错误。定期进行这些测试。

使用手册应对意外失败

进行根本原因分析（RCA）并分享结果

注入失败以测试弹性

定期举办game day

都不是

REL 9. How do you plan for disaster recovery?
Disaster recovery (DR) is critical should restoration of data be required from backup methods. Your definition of and execution on the objectives, resources, locations, and functions of this data must align with RTO and RPO objectives.

Define recovery objectives for downtime and data loss

Use defined recovery strategies to meet the recovery objectives

Test disaster recovery implementation to validate the implementation

Manage configuration drift on all changes

Automate recovery

None of these

REL 9.您如何规划灾难恢复？
如果备份方法需要恢复数据，则灾难恢复（DR）至关重要。您对此数据的目标，资源，位置和功能的定义和执行必须与RTO和RPO目标一致。

定义停机和数据丢失的恢复目标

使用定义的恢复策略来实现恢复目标

测试灾难恢复实施以验证实施

管理所有更改的配置偏差

自动恢复

都不是

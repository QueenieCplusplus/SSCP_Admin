# SSCP Admin

Logical & Physical Security

# OWASP top 10, (Open Web App Security Project)

* A1 Injection Flaws :

   (1) SQL
   
   (2) OS
   
   (3) LDAP   

* A2 Auth (session) Broken:

   (1) Session Token
   
   (2) Password
   
   (3) User Identies

* A3 XSS:

   hacker executes scripts in victim's browser due to error in validation & escaping.

* A4 Direct Obj:

   to expose user to ref to file, directory, db key. Without ACL!

* A5 Security Misconfig:
    
   Secure Setting shall be defined and implemented, and maintained.
   
   (1) app
   
   (2) frameworks
   
   (3) app server
   
   (4) web server
   
   (5) db server
   
   (6) platform

* A6 Sensitive Data Exposure

* A7

* A8

* A9

* A10


# System Software Security

* Drawback, 退版 :

  * regulatory & ops changes
  
  * new threats impact present automated process

  * error cause

 it assumes that a static set of requirements captures before design and coding phases begin. Before latter test begin, error may not be shown due to pre-fix. 

* Retrofit, 更新版本 :

  " the later the requirements into app, the more disruptive they are."

  if the mgmt process is performed, then it may reduce the outcome from:
  
  * Delay, 延遲交付
  
  * Cost overrun, 衍生成本
  
  * Disruption, 中途破壞
  
* Sys Apps Lifecycle, 系統建置的生命週期:

  * waterfall model, 瀑布式
  
      * spiral model, 螺旋式
      
          add Plan-Do-Check-Act to each stage in waterfall.
  
  * component dev & reuse, 安卓使用此方式
  
  * rapid model, 極限開發
  
       * strength:
       
           it  welcomes user to be involved in project with screenflow and feedbacks to and fro with developers. in this way, it has high error detection rate and bypass the extensive retrofit and regression (回歸回復) test.
       
       * weakness:
       
           it suffer "scope creep", team may lost end goal.
  
  * agile (iterative model), 敏捷式
  
       (later on...)
  
  
# Network Security

* Deployment of Sys, 系統部署發行）:

    * quality assurance
    
    * user-acceptance

  before releasing to end user (to the final acceptance test phase), there are QA team performs quality test.

  app or sys is released in Client Env || in the Market.

* Maintenance, 系統維護(除錯抑或是版本升級):

   * discover bugs
   
   * discover vulnerability
   
   * changes in technical env

  patches are released to fix issues || due to version update in Client Env.
  
  
# Data Securitry

  * Main methods:
  
     - [x] Deduplicate, 去重複化
     
     - [x] Scrubble, 去識別化
     
     - [x] Encryption, 加密
     
        * for file/ folder
        
        * for disk

  * IRM, Information Rights Mgmt, 數位版權保護

  * Data Leak Control
  
      * Data Discovery, 資料盤點
      
      * Labeling, 標示
      
      * Policy, 制定規範
      
      * Content Detection/Monitor, 內容監控
      
      * Traffic Block, 使竊盜者無法執行行為
      
      * Report, 報告

# Server Security

# Hardware Security










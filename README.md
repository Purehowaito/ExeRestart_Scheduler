<img width="600" height="465" alt="ExeRestart Scheduler" src="https://github.com/user-attachments/assets/0b38498f-5c79-4e05-a82f-02372bacfce3" />

**A lightweight Windows system tool developed in C++ that supports batch scheduling of multiple EXE program instances in groups and automatic restart to prevent memory leaks caused by long-term operation.**

**Note: This program forcibly terminates processes, so please ensure that the data of the target processes has been properly saved.**

**基于 C++ 开发的轻量级 Windows 系统工具，支持 EXE 程序批量多实例分组调度与自动重启，以规避长期运行导致的内存泄漏。**

**注意：该程序采用强制终止进程的方式，因此请确保目标进程的数据已妥善保存。**

**C++で開発された軽量のWindowsシステムツールで、EXEプログラムの複数インスタンスをグループ単位で一括スケジューリングし、自動再起動することで、長時間稼働によるメモリリークを回避します。**

**注意：本プログラムはプロセスを強制終了する方式を採用しているため、対象プロセスのデータが適切に保存されていることを確認してください。**

**C++로 개발된 경량 Windows 시스템 도구로, EXE 프로그램의 여러 인스턴스를 그룹 단위로 일괄 스케줄링하고 자동 재시작하여 장시간 실행으로 인한 메모리 누수를 방지합니다.**

**주의: 이 프로그램은 프로세스를 강제 종료하는 방식을 사용하므로 대상 프로세스의 데이터가 적절히 저장되었는지 확인하십시오.**

## **更新日志**

- **2026-08-25 Ver 1.2**
    
    改进了UI与交互逻辑、重做程序图标、修正界面翻译
    
    新增进程自动保活，当目标进程因崩溃或外部终止时将自动重新拉起
    
    全局停止热键（Ctrl+Alt+0）改用更可靠的底层监听方式，避免热键冲突
    
    改用静态链接编译，无需额外安装 VC++ 运行库，部署更便捷
    
    新增版本配置校验，不匹配时自动重置设置，规避跨版本异常
    
    新增首次启动时自动适配 Windows 显示语言
    
- **2026-04-10 Ver 1.1**
    
    改进了UI、进程检测与终止等逻辑
    
    新增组概念，支持 3 个独立配置组，每组最多 7 个实例
    
    新增全局停止热键
    
- **2026-03-23 Ver 1.0**
    
    初始

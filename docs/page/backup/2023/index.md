---
level: secret
---

# 机械臂文档

详细介绍了机械臂代码的各部分的功能和使用方法。

## 机械臂代码结构

![tip](assets/image.png){width=50%}

<div class="grid cards" markdown>

-   **:material-chevron-down: `armTool`：机械臂功能包**

        [`armSolution`：机械臂解算方法。](#armsolution){style="text-align:left;" #width .md-button}

        [`armSerial`：机械臂串口通信有关功能。](#armserial){style="text-align:left;" #width .md-button}


        <div class="grid cards" markdown>

        - [:material-chevron-down: `armState`：机械臂姿态描述，控制和信息导出。](#armstate){style="text-align:left;" #width .md-button}

            <div class="grid cards" markdown>

            -   `armInfo`：机械臂物理信息。

            -   `GripperPose`：机械臂夹爪枚举类。

            -   `armPose`：机械臂姿态描述。

            -   `armStruct`：机械臂信息数据帧构造。

            </div>

    </div>
    <div class="grid cards" markdown>

-   **`armControler`：封装功能包功能，提供控制机械臂的功能。**

</div>
<div class="grid cards" markdown>

-   **`armAction`：通过 Action 通信，实现与状态机对接。**

</div>

## 机械臂代码功能文档

<div class="grid cards" markdown>

-   ### `armState`

    [机械臂结构](机械/机械臂结构.md){#width .md-button}

    [数据帧格式](电子/数据帧格式.md){#width .md-button}

    [数据帧构造](电子/数据帧构造.md){#width .md-button}

-   ### `armSolution`

    [未完成](解算/计算文档.md){#width .md-button}

-   ### `armSerial`

    [串口通信](电子/串口通信.md){#width .md-button}

</div>

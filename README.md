[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py



TASK 2.5

1. Simple

<img width="782" alt="image" src="https://github.com/user-attachments/assets/258f89c0-4d6e-4f32-9519-006b70b553f2">

<img width="761" alt="image" src="https://github.com/user-attachments/assets/7ff781e1-e1e6-4f0f-816a-e0ea370012dc">

<img width="767" alt="image" src="https://github.com/user-attachments/assets/54bb0db9-d552-4bb9-952d-e10e629e25cf">

<img width="711" alt="image" src="https://github.com/user-attachments/assets/b175cf5a-9ead-4e86-8c34-f0b5f193375e">

Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 34.600551289244024, correct: 26
Epoch: 20/500, loss: 34.5773262166205, correct: 26
Epoch: 30/500, loss: 34.56605518170847, correct: 26
Epoch: 40/500, loss: 34.549898701764334, correct: 26
Epoch: 50/500, loss: 34.52430154876301, correct: 26
Epoch: 60/500, loss: 34.47357019739457, correct: 26
Epoch: 70/500, loss: 34.39344175071142, correct: 26
Epoch: 80/500, loss: 34.262064696060506, correct: 26
Epoch: 90/500, loss: 34.03388249547173, correct: 26
Epoch: 100/500, loss: 33.59235320011549, correct: 26
Epoch: 110/500, loss: 32.59088729418243, correct: 35
Epoch: 120/500, loss: 30.16550578293635, correct: 38
Epoch: 130/500, loss: 24.71272793295187, correct: 44
Epoch: 140/500, loss: 17.30517791323801, correct: 44
Epoch: 150/500, loss: 14.056162668927234, correct: 47
Epoch: 160/500, loss: 11.168442816292313, correct: 48
Epoch: 170/500, loss: 16.21915577193999, correct: 43
Epoch: 180/500, loss: 6.777178114874448, correct: 49
Epoch: 190/500, loss: 5.642823244051069, correct: 49
Epoch: 200/500, loss: 5.046526734179954, correct: 49
Epoch: 210/500, loss: 6.142577611578187, correct: 49
Epoch: 220/500, loss: 7.750125842307782, correct: 46
Epoch: 230/500, loss: 5.386492999998033, correct: 49
Epoch: 240/500, loss: 3.636143820807454, correct: 49
Epoch: 250/500, loss: 3.1939230022841336, correct: 50
Epoch: 260/500, loss: 2.991502203792977, correct: 50
Epoch: 270/500, loss: 2.7901790785914375, correct: 50
Epoch: 280/500, loss: 2.6671768762288606, correct: 50
Epoch: 290/500, loss: 3.5961595580554473, correct: 49
Epoch: 300/500, loss: 4.316501233144905, correct: 49
Epoch: 310/500, loss: 15.166622372831975, correct: 45
Epoch: 320/500, loss: 2.5346562430507547, correct: 49
Epoch: 330/500, loss: 2.137100077929961, correct: 50
Epoch: 340/500, loss: 2.0040555644953035, correct: 50
Epoch: 350/500, loss: 1.8922172755994358, correct: 50
Epoch: 360/500, loss: 1.7930851288483467, correct: 50
Epoch: 370/500, loss: 1.7031437276398136, correct: 50
Epoch: 380/500, loss: 1.6239755351789176, correct: 50
Epoch: 390/500, loss: 1.5577672481304603, correct: 50
Epoch: 400/500, loss: 1.4826569801786673, correct: 50
Epoch: 410/500, loss: 1.4203027157070138, correct: 50
Epoch: 420/500, loss: 1.3619192622723328, correct: 50
Epoch: 430/500, loss: 1.3074777624026974, correct: 50
Epoch: 440/500, loss: 1.255620066308014, correct: 50
Epoch: 450/500, loss: 1.21212185241042, correct: 50
Epoch: 460/500, loss: 1.173348398745447, correct: 50
Epoch: 470/500, loss: 1.138572453023877, correct: 50
Epoch: 480/500, loss: 1.0983679071006964, correct: 50
Epoch: 490/500, loss: 1.0610191473698982, correct: 50
Epoch: 500/500, loss: 1.0255816962379973, correct: 50

Time per epoch: 0.150s. 


2. Diag

<img width="769" alt="image" src="https://github.com/user-attachments/assets/eb2572c5-07fc-4212-84b4-12244ef8468b">

<img width="762" alt="image" src="https://github.com/user-attachments/assets/85b8a6ca-7191-43f8-9578-577897ad659b">

<img width="764" alt="image" src="https://github.com/user-attachments/assets/16edcc04-dd15-4183-ab37-7285532bfff2">

<img width="704" alt="image" src="https://github.com/user-attachments/assets/dd1143c6-cc48-4ce8-80bf-646e1f985072">

Epoch: 0/500, loss: 0, correct: 0
Epoch: 10/500, loss: 17.266846109273946, correct: 42
Epoch: 20/500, loss: 12.849827227647463, correct: 42
Epoch: 30/500, loss: 9.667077109019173, correct: 44
Epoch: 40/500, loss: 8.247851843590954, correct: 49
Epoch: 50/500, loss: 7.435323461608583, correct: 50
Epoch: 60/500, loss: 6.766992687430632, correct: 49
Epoch: 70/500, loss: 6.2146118385753875, correct: 48
Epoch: 80/500, loss: 5.756354499772747, correct: 48
Epoch: 90/500, loss: 5.371865503136427, correct: 48
Epoch: 100/500, loss: 5.046202867096814, correct: 48
Epoch: 110/500, loss: 4.768901885514996, correct: 48
Epoch: 120/500, loss: 4.5304598391688105, correct: 48
Epoch: 130/500, loss: 4.323475940899568, correct: 48
Epoch: 140/500, loss: 4.142046986700364, correct: 48
Epoch: 150/500, loss: 3.9815243939498397, correct: 48
Epoch: 160/500, loss: 3.6216871940974245, correct: 48
Epoch: 170/500, loss: 3.463584101948923, correct: 49
Epoch: 180/500, loss: 3.3602262103385945, correct: 49
Epoch: 190/500, loss: 3.2676227624284273, correct: 49
Epoch: 200/500, loss: 3.1841009684622548, correct: 49
Epoch: 210/500, loss: 3.1089476825365705, correct: 49
Epoch: 220/500, loss: 3.039543646815619, correct: 49
Epoch: 230/500, loss: 2.975333020157258, correct: 49
Epoch: 240/500, loss: 2.915236934586168, correct: 49
Epoch: 250/500, loss: 2.8583615750219264, correct: 49
Epoch: 260/500, loss: 2.8037695141739314, correct: 49
Epoch: 270/500, loss: 2.4836231832934232, correct: 50
Epoch: 280/500, loss: 2.444090585885641, correct: 50
Epoch: 290/500, loss: 2.414245745181887, correct: 50
Epoch: 300/500, loss: 2.3881529767235237, correct: 50
Epoch: 310/500, loss: 2.364589160114253, correct: 49
Epoch: 320/500, loss: 2.3423078382655804, correct: 49
Epoch: 330/500, loss: 2.3200280500749972, correct: 49
Epoch: 340/500, loss: 2.296503341208715, correct: 49
Epoch: 350/500, loss: 2.2708613208296518, correct: 49
Epoch: 360/500, loss: 2.2423628999429703, correct: 49
Epoch: 370/500, loss: 2.2099839846793734, correct: 49
Epoch: 380/500, loss: 2.1757800562277447, correct: 49
Epoch: 390/500, loss: 2.1395564484569705, correct: 49
Epoch: 400/500, loss: 2.1012957784495336, correct: 49
Epoch: 410/500, loss: 2.0614977091808586, correct: 49
Epoch: 420/500, loss: 2.020796961225865, correct: 49
Epoch: 430/500, loss: 1.9797912997327947, correct: 49
Epoch: 440/500, loss: 1.9389659749453738, correct: 49
Epoch: 450/500, loss: 1.8986710209243332, correct: 49
Epoch: 460/500, loss: 1.5965660403368698, correct: 50
Epoch: 470/500, loss: 1.5460670567181132, correct: 50
Epoch: 480/500, loss: 1.5375696956230795, correct: 50
Epoch: 490/500, loss: 1.5405573552127267, correct: 50
Epoch: 500/500, loss: 1.5489788565304081, correct: 50

Time per epoch: 0.147s.


3. Split







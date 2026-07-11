# qingdao-badaguan-threejs-model-comparisons

My experiments comparing different models by building Qingdao-Badaguan scenes.

## Prompt

```text
請把「青岛八大关」做成一個美觀、有氛圍的 three.js 互動虛擬景觀網頁。

要求：
- 玩家可以用滑鼠/鍵盤自由移動、旋轉視角
- 有適當的光影與大氣效果
- 場景要能傳達出該地點的**真實**氛圍
```

## Results

| how | repo | preview |
| - | - | - |
| run a workflow in omp with glm-5.2 high | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-glm-5.2 | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-glm-5.2/ |
| run a workflow in omp with gpt-5.5 medium (using xhigh as planner) | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-gpt-5.5 | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-gpt-5.5/ |
| use fable-5 xhigh to design/plan, gpt-5.5 medium to implement | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-fable-5-plan-gpt-5-5-impl | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-fable-5-plan-gpt-5-5-impl/ |
| use fable-5 xhigh to design/plan, gpt-5.5 medium to implement. attempt 2 | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-fable-5-plan-gpt-5-5-impl-attempt-2 | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-fable-5-plan-gpt-5-5-impl-attempt-2/ |
| purely using gpt-5.5-pro extended | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-gpt-5.5-pro | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-gpt-5.5-pro/ |
| purely using fable-5 xhigh | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-pure-fable-5 | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-pure-fable-5/ |
| run a dynamic workflow with fable-5 xhigh  | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-fable-5-dynamic-workflow | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-fable-5-dynamic-workflow/ |
| run a dynamic workflow with fable-5 ultracode  | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-fable-5-ultracode | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-fable-5-ultracode/ |
| using gpt-5.6-sol max in omp | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-gpt-5.6-sol-omp | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-gpt-5.6-sol-omp/ |
| run simple workflows in omp with gpt-5.6-sol max | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-gpt-5.6-sol-workflow-omp | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-gpt-5.6-sol-workflow-omp/ |
| run strict workflow combinations in omp with gpt-5.6-sol max | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-gpt-5.6-sol-strict-workflow-omp | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-gpt-5.6-sol-strict-workflow-omp/ |
| using gpt-5.6-sol max + imagegen (gpt-image-2) in codex | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-gpt-5.6-sol-codex | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-gpt-5.6-sol-codex/ |
| using gpt-5.6-sol ultra + imagegen (gpt-image-2) in codex | https://github.com/Recursive-Self-Improving/qingdao-badaguan-threejs-gpt-5.6-sol-ultra-codex | https://recursive-self-improving.github.io/qingdao-badaguan-threejs-gpt-5.6-sol-ultra-codex/ |

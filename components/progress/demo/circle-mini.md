---
order: 3
title: 小型进度圈
---

小一号的圈形进度。

````jsx
import { Progress } from 'antd';
const ProgressCircle = Progress.Circle;

ReactDOM.render(
  <div>
    <ProgressCircle percent={30} width={80} />
    <ProgressCircle percent={70} width={80} status="exception" />
    <ProgressCircle percent={100} width={80} />
  </div>
  , mountNode);
````

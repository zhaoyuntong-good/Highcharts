## 使用Highcharts时需要将汉化以及优化时间显示
### 使用cdn方式引入
```
<script type="text/javascript" src="http://cdn.hcharts.cn/highcharts-plugins/highcharts-zh_CN.js"></script>
```

### 在vue中可将本文件下载到本地并引入，例如：
```
import Highcharts from 'highcharts/highstock'
export default {
  data(){
  	return {
      factory: require('./highcharts-zh_CN.js')
  	}
  },
  created(){
    this.factory(Highcharts);
  }
}
```

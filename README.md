# refactoring-demo

- 重构手法的简单示例

## 可扩展性

- 使用继承和多态后，如果有新的剧目需要增加，则只需在工厂函数 `createPerformanceCalculator` 中增加类型判断，并且返回新的子类即可

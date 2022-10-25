# Is

类型判断库

## 安装

```bash
npm i @justichentai/is
```

## 使用

```ts
import * as is from '@justichentai/is'

const arr = []

is.isArray(arr)
```

## Api

```ts
/**  
 * 检测是否是数组  
 * @param obj  
 */  
declare function isArray(obj: any): obj is any[];  
  
/**  
 * 判断是否是空对象  
 * @param obj  
 */  
declare function isEmptyObject(obj: any): boolean;  
  
/**  
 * 判断是否是函数  
 * @param obj  
 */  
declare function isFunction(obj: any): obj is (...args: any[]) => any;  
  
/**  
 * 判断是否是 null  
 * @param obj  
 */  
declare function isNull(obj: any): obj is null;  
  
/**  
 * 判断是否是 null 或者 undefined  
 * @param obj  
 */  
declare function isNullOrUndefined(obj: any): boolean;  
  
/**  
 * 判断是否是数字  
 * @param obj  
 */  
declare function isNumber(obj: any): obj is number;  
  
/**  
 * 判断是否是对象  
 * @param obj  
 */  
declare function isObject(obj: any): obj is Record<string, any>;  
  
/**  
 * 判断是否是字符串  
 * @param obj  
 */  
declare function isString(obj: any): obj is string;  
  
/**  
 * 判断是否是 undefined  
 * @param obj  
 */  
declare function isUndefined(obj: any): obj is undefined;  
  
/**  
 * 对象是否是 window  
 * @param el  
 */  
declare function isWindow<T>(el: any): el is Window | T;
```

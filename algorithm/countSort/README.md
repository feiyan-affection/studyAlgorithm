# 计数排序算法
算法描述：将要排序的数据中包含的元素按照顺序排成一个数组，然后根据数组中
元素的个数进行逆向反查**O(k+n)**.
## 算法步骤
* 形成小的数组，并计算小数组中各个元素的个数
* 反向递推原有数组
## 算法使用场景
其中k是不同元素的长度，如果元素都不相同就不太使用这个算法，这个算法就和普通
算法是一样的**O(n^2)**的时间复杂度，在有限的状态下是线性的，k要小才有用
# 数组
1. python直接两个数组相加nums+nums
2. res.append()    
for 循环后面加:
3. ×
4. 函数Counter(nums) ,计录出现过的数
for i in range(1,len(nums)+1):  #这才是从1到n
dic.get(i)==None  #在字典dic中，value没有这个值，也可以用dic.get(i,0)==0
5. n=len(nums)
result=[0]*n  #这样创建空数组
6. set() 是Python中的集合类型，用于存储无序、不重复的元素。
if i not in p:
  res.append(i)
# 栈
1. target: List[int], n: int  
for x in range(1,target[-1]+1):#target[-1]表示数组最后一个元素  python的range左闭右开
2. str是字符串，要转化为int
stack[-1]=int(stack[-1]/x)#两个整数之间的除法总是 向零截断,直接/，-1.5会变成-2
3. stack=[] 用pop和append
res[uid]+=time-ptime+1#题目要求在时间戳的末尾结束执行
log=l.split(":")用分隔符分开的各部分也是str
# 单调栈
1. 从右向左用栈，可以画图思考情况。
此题简单写法是用哨兵st=[0],这样不用判断st(始终有值),而且直接用prices[i]-st[-1]即可
for i in range(n-1,-1,-1):从右往左
2. while st and temperatures[i]>=temperatures[st[-1]]:存的是编号
            if st:如果不为空
                ans[i]=st[-1]-i
            st.append(i)不管空不空都将当前温度加入单调栈
3. 想法：枚举i使得它是选定范围最高的柱子，只看左右比它小的第一个right和left，矩形宽度就为
right-left-1，高为height[i]  left默认-1,right默认n
zip() 将对应位置的元素组合成元组
        for h,l,r in zip(heights,left,right):
            ans=max(ans,h*(r-l-1))
# 测验1.2
1. 人工加法，for循环里面用return达到一直验末尾9的功能
2. 判断条件if left==right and left!=0 and right!=n-1:
3. 字符集合变字符串'a','b'->"ab"   ''.join()   直接哈希表用dict
left=Counter(s):哈希表（继承关系Counter → dict → object），存每个字母还有几个
ans=[]:列表（list → object），存最终需要的唯一字母
in_ans=set():集合（set → object）无序不重复   in_ans.remove()  ans.pop()
这道题每次加进来的都是ans和in_ans
# 队列
1. 参考答案更简便
2. 灵神  tk = tickets[k]
                 return sum(min(t, tk - (i > k)) for i, t in enumerate(tickets))
3. 构造函数
  def __init__(self):
          self.a,self.b=[],[]
# 堆
1. heap=[-x for x in stones]列表所有元素倒置
heapq函数:

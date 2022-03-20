今日 `= "[["+date(today)+"]]"` ，去年 `= "[["+(date(today) - dur(1 years))+"]]"`

## 我的项目
``` dataview
table owner, deadline, biz AS "后端开发",  front AS "前端", middle AS "中台", claim as "理赔", test as "测试", priority as "优先级",  memo, aone
from "pages"
where (type = "Project" or type = "Task")  and status = "todo"  and sprint = 10 and owner = "乔云"
sort priority
```

## 最近编辑
```dataview
table WITHOUT ID file.link AS "标题",file.mtime as "时间"
from !"assets" and !"journals" and !"logseq" 
sort file.mtime desc
limit 5
```


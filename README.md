# 排班休假日 ICS feed（去識別化：檔案內只有日期 + 休/例/補休/特休，不含姓名）

Google Calendar → 其他日历 → 从 URL →

https://raw.githubusercontent.com/aalizzwall/schedule-ics/main/off-days.ics

Google 每 ~8-24h 重新抓。更新方式：`parse_schedule.py <排班圖> <姓名> --ics` 后把 off-days.ics push 到此 repo。

# Hotel Ad Frequency Experiment FINAL

## 本地运行
```bash
python -m streamlit run streamlit_app.py
```

## 后台
在网址后面加：
```text
?admin=1
```

## 实验链接参数
```text
?mode=hotel&adfreq=1
?mode=hotel&adfreq=2
?mode=hotel&adfreq=3
?mode=hotel&adfreq=4
?mode=hotel&adfreq=5
?mode=ota&adfreq=1
?mode=ota&adfreq=2
?mode=ota&adfreq=3
?mode=ota&adfreq=4
?mode=ota&adfreq=5
```

## 最终数据字段
submit_time, participant_id, interface_mode, ad_frequency, ad_seen, selected_hotel_name, selected_room, room_price, total_price, paid,
ad_perceived_frequency, ad_recall_count, ad_distracting, ad_disturbing, ad_forced, ad_interfering, ad_obtrusive, ad_intrusive, ad_in_the_way, birth_year, gender

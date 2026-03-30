---
title: "오늘의 배움: Jekyll 블로그 구축"
date: 2026-03-17 00:00:00 +0900
categories: [TIL, 데이터베이스]
tags: [security, database]

## 3월 17일 화요일 데이터베이스 보안 실습에서 실습한 내용
-파이썬을 설치했다.
- 파이썬으로 패키지를 설치하고 , 연동하는 방법을 배웠다.

''' python

import mysql.connector

conn = mysql.connector.connect(
    host="localhost",
    user="root",
    password="min04181215^^",
    database="filter_db"
)

cursor = conn.cursor()

# cursor.execute("INSERT INTO users (id, name) VALUES (1, '철수')")
#conn.commit()

cursor.execute("SELECT * FROM users")
print(cursor.fetchall())

cursor.conn.cursor()

cursor.execute(update users set id = 11 where id =10')
conn.commit()

cursor,excute("SELECT * FROM students where grade = 2")
print(cursor.fetchall())

curor.close()
com.close()

       (1, '철수'),
       (2, '장미'),
       (3, '시호'),
       (4, '도일'),
       (5, '미란'),
       (6, '보라'),
       (7, '아름'),
       (8, '뭉치'),
       (9, '세모'),
       (10,'브라운'),
    




'''
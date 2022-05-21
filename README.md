# Django_CRUD

### 참고자료 
- migrate에서 오류가 발생하는경우

<https://blog.naver.com/vcacv/222630803853>

model 수정을 너무 많이 했더니 APP의 migration폴더에 뭐가 많이 생겼다. 그러면서 django.db.utils.IntegrityError오류가 생겼는데, 외부 키 참고랑 table 값에서 뭔가 오류가 생긴 듯 하다...암튼 생긴 파일들을 삭제하고 다시 makemigrationks-migrate했더니 작동함.

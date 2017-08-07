Django (1.11.3)にtimestampをつけました（formやwidgetなど、ユーザから直接受け取る部分は未実装）
'Inoue' の文字列で検索すると、追記の部分が全て出てきます。

root@debian:/usr/local/lib/python3.4/dist-packages/django# grep -r Inoue
contrib/gis/utils/layermapping.py:		models.TimeStampField: (OFTInteger)   # Added By Inoue
contrib/admin/static/admin/css/forms.css:/*Added By Inoue Start*/
contrib/admin/static/admin/css/forms.css:/*Added By Inoue Ecd*/
db/backends/mysql/introspection.py:        #FIELD_TYPE.TIMESTAMP: 'DateTimeField',   #Comment Out By Inoue
db/backends/mysql/introspection.py:        FIELD_TYPE.TIMESTAMP: 'TimeStampField',   #Added By Inoue
db/backends/mysql/base.py:		'TimeStampField': 'timestamp default \'2000-01-01\'',   #Added By Inoue
db/backends/base/operations.py:		'TimeStampField': (0, 2147483647)   #Added By Inoue
db/models/fields/__init__.py:    'TimeField', 'URLField', 'UUIDField', 'TimeStampField',   #Added By Inoue
db/models/fields/__init__.py:#Added By Inoue

# manegee DB設計
## userテーブル
|Column|Type|Options|
|------|----|-------|
|email|string|null: false|
|password|string|null: false|
|nickname|string|null: false|
### Association
- has_many :students

## studentsテーブル
|Column|Type|Options|
|------|----|-------|
|number|integer|null: false|
|name|string||
|school|string|
|profession|string|
|stage|integer|
|time|integer|
|testday1|integer|
|testday2|integer|
|other|text|
### belongs_to :user
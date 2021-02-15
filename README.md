# テーブル設計

## users テーブル

| Column   | Type   | Options     |
| -------- | ------ | ----------- |
| email     | string | null: false |
| password    | string | null: false |
| name | string | null: false |
| profile | text | null: false |
| occupation | text | null: false |
| position | text | null: false |


## prototypes テーブル

| Column | Type   | Options     |
| ------ | ------ | ----------- |
| title   | string | null: false |
| catch   | text | null: false |
| concept   | text | null: false |
| image   |  | null: false |
| user   | references | null: false |


### commentsテーブル

| Column | Type   | Options     |
| ------ | ------ | ----------- |
| text   | string | null: false |
| user   | references | null: false |
| prototype   | references | null: false |




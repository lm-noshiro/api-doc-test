# Group User

ユーザー

## ユーザー [/user]

### 個人データ取得 [GET]

- Response 200 (application/json)

  - Body

    ```json
    {
      "user": {
        "id": 123456789,
        "name": "the40san",
        "avater_id": 1,
        "rank": 123,
        "exp": 12345678
      }
    }
    ```

### ユーザー設定変更 [PATCH]

- Attributes

  - name: `` (string, optional) - ユーザー名
  - avater_id: `` (string, optional) - アバター ID

- Request example ユーザー名変更 (application/json)

  - Body

    ```js
    {
      "name": "つよい"
    }
    ```

- Request example アバター ID 変更 (application/json)

  - Body

    ```js
    {
      "avater_id": 2
    }
    ```

- Response 200 (application/json)

  - Body

    ```json
    {
      "user": {
        "id": 123456789,
        "name": "the40san",
        "avater_id": 1,
        "rank": 123,
        "exp": 12345678
      }
    }
    ```
